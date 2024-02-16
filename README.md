# RASSAR324_FTO2401_GROUPA2_RasheedaSarguro_SDF09
TailwindCSS project

In this project I demonstrate my understanding and application of TailwindCSS properties within an HTML file.
The footer.HTML file is located in the 'build' folder.

First I was confused by the initial installation process of tailwind. 
I would get confused between what the TailwindCSS documentation stated versus what was given to us. For example, on TailwindCSS, it says that if you wanted to set the text color of an element to white, to use: text-white. In the LMS though, they gave us the example of: dark:text-white. I didn't understand how its both dark and also white. Then I realised that is included for when the user's screen is switched to dark mode, the text will appear white.

When doing this project, I constantly checked out how it was responding using Devtools. When trying to add a hover effect to my button, it worked for large screen devices. But once I switched to responsive design, it wouldn't apply when hovered to small screens. I couldn't understand why that is the case, and I'm not sure if this is just how the devtools feature works or if there is a missing part in my code.

I also struggled with setting the dimensions on the input and button. When I viewed it on the iphone SE screen, the size matched the reference picture, whereas on the iPad mini and desktop, the h1 element would be too small. I couldn't understand what was the issue that was causing the break-point of the design to not be responsive when the screen would shrink or enlarge so that the 2 elements would grow or shrink with it. Was it related to the size of the columns, the margins placed, the lack of a max-width, I wasn't sure. I tried various approaches such as setting a max-width on the elements, but it would appear too small on desktop view; making them the width size 'full' based on the viewport, but that extended it too far. 

I also found that ARIA labels are challenging. There are so many various elements and scenarios where they can be applied, but equally there are situations where they shouldn't be applied. Trying to find simple language that explained when to use and when not to use aria labels was more complicated than I anticipated. One site suggested that if you have links, they should be included in 'nav' tags. When I did that though, my links all lined up horizontally, and I couldn't figure out what needed to be changed to avoid that. So I opted to remove the nav tags instead.