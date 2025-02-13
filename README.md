# WebTV HD
![WebTV HD logo](https://skcro.github.io/WebTV-HD/Logo.svg)

<sub>Previously known as "WebTV-CSS-Remake".</sub>

A project that is a fork of [WebTV-HD](https://skcro.github.io/WebTV-HD/)

**Original WebTV-HD made by SKCro!**

## How do I try it out?
### Head on over to the **[GitHub Pages instance](https://soyfeo123.github.io/PabWebTV-HD/)** if you'd like to try it out.

If anything is broken for you, **please file a bug report** and tell me the issue, which browser you used, and your screen resolution. Provide a screenshot if possible.

## How do I use the code?
**Important:** If you're planning to use this for a project or website, please credit me when possible.
 
Click the "Code" button at the top and click "Download ZIP". Unzip wherever you want and host the directory with a server - a lot of things don't work correctly if you just open the `index.html` file in your web browser due to cross-origin stuff.
 
![Screenshot of the "Code" button being pressed.](https://i.imgur.com/bXnlbAJ.png)

If you prefer (or are stuck with) with a command line interface, you can run `git clone https://github.com/SKCro/WebTV-HD.git`, and copy all the resources over by entering the WebTV-HD directory, and running `cp -r ./* <your location>`.

## What are your goals for this project?
- Get the style to look as accurate as possible.
- Remake some of the Page Builder styles and separate the service page style from the base WebTV stuff (like the statusbar and buttons).
- ~~Make the style work better on mobile devices (or create a new one specifically designed for them).~~ Finally done! The sidebar now slides in and out via a button.
- Get the selection box to move via the arrow keys (and maybe gamepad), just like real WebTV. This would make big-screen browsing easier. Partially done with tab navigation.
- Possibly make an MSN TV 2 style (although I'd probably make a second repo for that).
- ~~\[Unlikely\] Make this into a browser extension of some sort that adds a WebTV overlay and allows navigation with your keyboard or a gamepad.~~ Unfortunately, this is probably impossible due to the way WebTV HD works - it embeds the page into an iframe so that WebTV elements like the status bar draw on top of the page (and aren't a part of it). The problem is that a lot of big websites don't allow embedding (for security reasons) - you can try this yourself: open the Go To panel and try to go to a popular site like YouTube. It will probably give you either nothing at all or an error message.
- \[Very Unlikely\] Try to make this into a WTVP-to-HTML interface. Essentially, make it into a WebTV client. This would be very complicated (I have no backend skills and would definitely need help from others), but it is something I'm looking forward to getting working eventually (even at a very basic level).

If you'd like to suggest something, fill out the [feature suggestion template](https://github.com/SKCro/WebTV-HD/issues/new?assignees=SKCro&labels=enhancement&projects=&template=feature-request.md&title=%5BRequest%5D+) to let me know what you'd like to see added to WebTV HD.

## TODO:
- ~~Flesh out everything.~~ Pretty much done.
- ~~Make the status bar look better on non-widescreen display sizes.~~ Done.
- Recreate more service pages like ~~login,~~ ~~mail,~~ ~~settings,~~ favorites, etc.
- ~~Add functionality with JavaScript.~~ Done.
- Fix the dang selection box scrolling bug. This is partially done by simply not updating the `top` attribute when scrolling, but it doesn't fix the root problem - clicking something else while scrolled down still results in the bug.
- ~~Make Dialing.html actually work better by making it show a splash at 100% progress, along with redirecting to Home.html.~~ Done by nitrate92.
- ~~Flesh out Home.html.~~ Done.

## What if I need help using this code?
If you need help for any reason, feel free to contact me on Twitt- I mean X; username is `@pabtsm`

**Original WebTV-HD by SKCro, he did a great job!**
