# RWD Week Eight and Nine · JavaScript

## Adding the time-based message code

* The [initial state of the code is available on this codepen](https://codepen.io/wilsondmmu/pen/43ef68f25d5275d02fa51d9e0298b419).
* There are two ways of adding the initial code:
1. *Inline*, which adds more code, in a different language, to an already busy page, which can confuse your text editor
2. Or as a separate JavaScript file, keeping the code separate in your editor, and making it easier to add updates and debug.

### Adding the code inline

* Go to the bottom of your HTML page (JavaScript **cannot** be added to CSS files)
* Just before the ending `<body>` tag, create a `<script></script>` tag
* Go to the codepen above
* Copy the code in the JS box
* Paste this code in between the `<script>` and `</script>` tag
* Refresh the HTML page: the code should now run.

### Adding the code as a separate file

* Go to the bottom of your HTML page (JavaScript cannot be added to CSS files)
* Just before the ending `<body>` tag, create a `<script src=""></script>` tag
* Create a folder to hold your JavaScript file (usually named `js`)
* Create a new file in your text editor
* Go to the codepen above
* Copy the code in the JS box
* Paste the JS code into your new file in your text editor
* Save the code with a sensible filename and a .js file extension, e.g. `time.js`
* Go to your HTML and in the `<script src=""></script>` add the path to your file
* In this example it would look like this: `<script src="js/time.js"></script>`
* Refresh the HTML page: the code should now run.

### Problems you may run into

* Old browsers might not run this code: if so, update your browser if possible
* Internet Explorer may not run the code if the HTML page is not online: Chrome and Firefox seem to be fine
* Don't add this code to the `<head>` of your page, as the DOM - defined in the lecture – needs to be created before the code can work correctly
* Remember you have the console available in the web developer inspector in Chrome and Firefox to help if you are having problems - check the network tab and the console tab for errors.

### Things to do to customise the code for your site

* Change the message
* Change the hours
* Think about what might happen if the site visitor is not in the same country as you. Are they getting the right information if their computer is set to a different time-zone?
* Add more message options
* Anything else you think might be of use to a site visitor: just make sure that you are progressively enhancing the page, and that users without JavaScript won't be unduly penalised compared to users who do have JavaScript turned on.


## Adding the user tracking code


* Remember this code will not do anything visible on the page. You will need to open the console in your web browser to see it working.
* The console on mobile browsers is quite difficult to access. It’s much easier to use a desktop computer to see what’s going on.

### Implementing the code

* The code you need is [viewable on GitHub](https://github.com/mmu-webdesign/l4-IWD-web-term2/blob/master/tracker.js). **Don’t** use `file -> save as...` from this page as you’ll get the entire HTML of the GitHub page, instead read on...
* Either click on 'RAW' or [use this link to get the JavaScript code](https://raw.githubusercontent.com/mmu-webdesign/l4-IWD-web-term2/master/tracker.js) in a form that you **can** use `file -> save as...` to download the code to your computer.
* Add the code to last week’s JavaScript. 
* Remember: at the moment it is best practice to have a single JavaScript file if you are adding your code as a separate file, as it takes time for the browser to fetch each files - fewer files to fetch, the earlier the page is ready for the user to start interacting with it. 
* Use the console to verify the code is working correctly, or if it isn’t, then use the errors in the console to fix the problems you find.

### Adding things to the code

* There are some suggestions on moodle about how you might want to ‘extend’ this code – it’s entirely up to you at this point. You may want to get the code working and then continue getting the rest of your site ready for submission. 
* If you do decide to modify the code, this [introduction to events at MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events) could be useful to explain how web browsers listen out for things happening in your documents.
* As before, make sure that you are progressively enhancing the page, you are considering the user’s privacy, and that users without JavaScript won't be unduly penalised compared to users who do have JavaScript turned on.


[Return to the Top](#contents)
