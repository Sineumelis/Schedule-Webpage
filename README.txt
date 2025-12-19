Hello, thank you for all the time, attention and stopping for Reading this :)

-The data is managed with accounts of mine using Firebase and a virtual card, it may stop working. In that case you could contact me to fix it or to help make an account for the user who runs this code in the momento in the platforms I used and make it work.

-The page is currently hosted by my GITHUB account. There shouldn't be any problem with it but migration to a more manageable place of the user of this code is advised.

-A bit of explanation: I used Firebase to save data and images. To use Firestore Database it's only needed to have an account in Firebase and add the module of it (if used in test mode remember to change the Rules to make the date of expiration a far one, i think i set this to 2056 or so). I also used the module of Firebase Storage, for this one you need to have a payment method (I used a virtual card just in case but this code only uploads 1 image at a time so the storage limit won't ever be surpassed. Another thing to know is that depending on where you set the location of your data, Storage may or not be able to be used).

-There is a CORS file that I added to the Firebase Database via commands in the terminal. Not sure if it is really needed but it helps code to show and work in some places that don't admit unsafe routes in webpages.

-Size (mostly padding) of table can be changed in "index-style.css" if needed to adjust any foreground or background to it (It's a bit rudimentary but Works) or in "Personalize.html" via changing the value of const "EXPORT_WIDTH = 1600;" AND "const EXPORT_HEIGHT = 900;"

-There is a old version in the commits of this proyect where the image would be clickable and show a full screen, loading images and everything with an OnSnapshot which didn't work in the TV but is still useful somewhere else.

-If anything fails, normally opening developer mode (Ctrl + Shift + J) should show the problema in the log of events.











