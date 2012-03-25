ButtonTool
===

A little HTML tool that aids in the creation of GUI elements using CSS (as opposed to an image editor such as Photoshop).

It was developed and tested in a couple of hours in Firefox, but may work on other browsers with some porting.

![Screenshot](https://github.com/ZaneA/ButtonTool/raw/master/screenshot.png "Screenshot")

Usage
---

`git clone` this repo and browse the `index.html` to use.

**Important!** ButtonTool *MUST* be run locally, that is *without* a web server. This is due to the need for canvas to grab a screenshot of the embedded iframe which current browser security restricts.

Actual usage is pretty straightforward, modify the CSS under the button preview and the results should update instantly. When you're done you can save the image that is output in the square at the top of the page. This image can then be imported into a tool such as `draw9patch` for usage in the Android SDK, etc.

Todo
---

- Less.js support; you will note that less.js is already included but not yet utilised.
- Custom width/height of output image.
- Actual (optional) 9-patch generation from within this page, to save the extra step.
