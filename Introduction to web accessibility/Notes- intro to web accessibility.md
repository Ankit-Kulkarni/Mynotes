## DOM BEST PRACTICES

* create logical sections of doc to identify interface elements that are related, HTML5 semantic elements like nav header, h1 are useful

* all parts of controls are grouped together. Like dropdown menu and its dropdown button

* Use **css** for layout instead of **tables **

## Interactive Controls

** Use native HTML tags instead of generics divs and spans when possible **

* Example-  Instead ** <span onclick=" " .. ** Use ** <a href =" " **

Instead ** <div onclick=" " ** Use ** <button onclick=" " **

Generics divs and spans are not foucsable and respond to keyboard events.


## How to build more accessible block.

* Test your webApp always with keyboard so that you can move over controls via tabbing.Also see that space and enter can be used to invoke a control.

* manage focus of the controls
* Include alt attribute in each and every image tag . alt ="descrivtive text " or alt = "" which says to skip the screeen reader the image.

* Also put label tag to each of the names in form tag.

* also put for tag in buttons . like for = "users"