# practice_chrome_extension
Change the background colour of a page

# FILES
* manifest.json - components must be registered here
* background.js - gives the extension instructions (Most API's must be registered under "permissions" in manifest)
* popup.html - html of the popup (file designated as a popup under "page_action" in manifest)
* popup.js - gives colour to the button and changes the background colour of page
* options.html - more colour options (register in manifest under "options_page")
* options.js - changes the colour option in the extension
* images - for the toolbar icon ("default_icon" in manifest)

# SETUP
* Create manifest file.
* Open the Extension Management page - chrome://extensions
* Enable Developer Mode.
* Click Load Unpacked.
* Select extension directory.

Click the reload icon when there are any changes.
