# Gamepad Viewer Nintendo Switch Pro Controller Skin
the odds of me updating this if anything on gamepad viewer changes enough to break it are very low <br/>
It's a repo for a thing!

This is a skin created for Gamepad Viewer that, afaik, only works if used in the custom css in OBS studio. <br/>
It'll probably also work if you know another way to make gamepad viewer actually read the css instead of trying to read it from rawgit... <br/>
That's because Gamepad Viewer assumes it can pull the repo's files from rawgit despite it being nearly 4 years out of service,
and so it dead-ends there on the actual website, unless you're using an old enough skin <br/>
That being said, this here is a Nintendo Switch Pro Controller skin <br/>
All images were made/edited by me, Soveliss. <br/>
The code is based off that of the example custom css provided by the creator of gamepad viewer, and I also referenced the CSS behind
 skins by Million Lights and HawkyYT to help me understand what was going on (thought it ended up being trial and error mostly) <br/>

This works by creating a browser source in OBS, linking it to "https://gamepadviewer.com/?p=1&s=1" <br/>
and then pasting the contents of the CSS file (Switch-Format.css) into the custom CSS box underneath that <br/>
Voila! <br/>
Here's a screenshot of what it looks like 18 feb 2022: <br/>
<img width="296" alt="Screen Shot 2022-02-18 at 9 47 08 AM" src="https://user-images.githubusercontent.com/99949632/154735360-39105df9-4cea-4308-9a84-8482951de909.png">

Note that the joystick movement doesn't scale with the resolution of the component parts, nothing I know how to do there - the 540p will work better for most purposes.
The Illustrator file included contains everything that's been exported to the 540p and 4k branches as of some point (might not stay updated), should you wish to customize this and make your own repo of your own skins.
If you can't open the illustrator file, converting it to a jpg/png will match the base of the skin, allowing you to modify at least the main faceplate+grips of the controller.
