# Gamepad Viewer Nintendo Switch Pro Controller Skin
the odds of me updating this if anything on gamepad viewer changes enough to break it are very low <br/>
It's a repo for a thing!

This is a Nintendo Switch Pro Controller skin created for Gamepad Viewer that, afaik, only works if used inside of OBS studio*. <br/>
All images were made by me, Soveliss. <br/>
The CSS is based off that of the example custom CSS provided by the creator of gamepad viewer, and I also referenced the CSS behind skins by Million Lights and HawkyYT to help me understand what was going on (though it ended up being trial and error mostly) <br/>

This works by creating a browser source in OBS, linking it to "https://gamepadviewer.com/?p=1&s=1" <br/>
and then pasting the contents of the CSS file (Switch-Format.css) into the custom CSS box underneath that <br/>
Voila! <br/>
Here's a screenshot of what it looks like 18 feb 2022: (and again with the whole window 22 feb 2022):<br/>
<img width="296" alt="Screen Shot 2022-02-18 at 9 47 08 AM" src="https://user-images.githubusercontent.com/99949632/154735360-39105df9-4cea-4308-9a84-8482951de909.png"> <img width="721" alt="Screen Shot 2022-02-22 at 4 43 02 PM" src="https://user-images.githubusercontent.com/99949632/155244134-a2c90936-07e0-4921-94f5-957d9663ed07.png"> <br/>
Note I set my browser window size to 630x528 pixels b/c that's the size of the images used.

The Illustrator file included contains everything that's been exported to the basic assets as of some point (might not stay updated), should you wish to customize this and make your own repo with your own skins.
Each group in the Illustrator file can be exported as a .png at 1x resolution and renamed to the name of the group, then in the CSS you will need to change only the filepath to reach wherever you're hosting your files (the links should be obvious, if you make your own github repo then change them to https://raw.githubusercontent.com/username/repository/filepath/6thumbs.png or etc) <br/>
Exporting assets after moving anything, modifying sizes, modifying export sizes, or other changes besides color/inside clip groups/etc may require changes to the CSS to make it look right, no guarantees.



*It'll probably also work if you know another way to make gamepad viewer actually read the css instead of trying to read it from rawgit... <br/>
That's because Gamepad Viewer assumes it can pull the repo's files from rawgit despite it being nearly 4 years out of service,
and so it dead-ends there when attempted on the actual website, unless you're using an old enough skin or self-hosting the css somewhere besides github (github.io might work but I'm too lazy to try) <br/>
