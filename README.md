# RASSAR324_FTO2401_GROUPA2_RasheedaSarguro_SDF09
TailwindCSS project

In this project I demonstrate my understanding and application of TailwindCSS properties within an HTML file.
The footer.HTML file is located in the 'build' folder.

First I was confused by the initial installation process of tailwind. I think there is some confusion for me as to why we're linking a css sheet to the file, when there was already a tailwindcss link given to us in the starter code.

While working through the document, I would get confused between what the TailwindCSS documentation said to do, versus what was given to us in the starter code and the LMS. For example, on TailwindCSS it says that if you wanted to set the text color of an element to white, to use: text-white. In the LMS though, they gave us the example to use of: dark:text-white. I didn't understand how it could be both dark and also white. After some investigation, I realised that is included for when the user's screen is switched to dark mode, so that the text will appear white. Seeing as that wasn't part of the deliverables, I didn't focus too much attention on it. 

When doing this project, I constantly checked out how it was responding using Devtools. When trying to add a hover effect to my button, it worked for large screen devices. But once I switched to smaller screens, it wouldn't apply when hovered while using devtools. I couldn't understand why that was the case, but I believe it's a function of devtools itself.

I also struggled with setting the dimensions on the input and button. When I viewed everything on the iphone SE screen, the sizes of the input and button field matched the reference picture. Whereas when viewing it on the iPad mini and desktop view, the h1 element would be too small. I couldn't understand what was actually causing the issue.
I managed to get my h1 to function responsively, whereas the button and input field took me surprisingly long to figure out. Was it related to the size of the columns, the margins placed, the lack of a max-width? I wasn't sure. I tried various approaches such as setting a max-width on them, but then it would appear too small on desktop view. I tried making them the width size 'full' based on the viewport, but then that would extended it too far. Eventually I settled on adding enough margin so that it wouldn't bleed to the edge of the screen when the view size changed. I would like to know what I could have done instead to make that specific issue work better.

Lastly, I found that ARIA labels are challenging. There are so many various labels and scenarios where they can be applied, but equally there are situations where they shouldn't be applied. Trying to find simple language that explained when to use and when not to use aria labels was more complicated than I anticipated. One site suggested that if you have links, they should be included in 'nav' tags. When I did that though, my links all lined up horizontally, and I couldn't figure out what needed to be changed to avoid that. So I opted to remove the nav tags instead. I can see why adding aria-labels can be challenging if one doesn't fully understand the function they represent. 

I made sure to download a screenreader to test my code to see how it would respond, and from what I can tell, it seems to be working well. I made sure to include hover focus and active tags to my classes so that they could all be individually targeted.

All in all, I will say that I really enjoyed this project. It was fun to work with and try to recreate an image. The onlly thing I still am unsure of is exactly what font was used in the original images. I know my font isn't the same one, but because there are so many font types out there, it was almost impossible to find the matching font. 