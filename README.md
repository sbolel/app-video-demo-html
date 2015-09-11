# Mobile Video Demo Template

This is a website template to display an app recording inside an iPhone 6.

## Getting Started

1. `git clone git@github.com:sbolel/app-video-demo-html.git` - clone this repository.

2. Replace `./www/sample-demo.mov` file with your own screen recording.

3. Change the video `src` in [`./www/index.html`](./www/index.html):

```html
<video autoplay width="375" height="667" name="Demo Video" src="sample-demo.mov"></video>
```

#### View demo web page in your browser

Open `./www/index.html`

#### Serve the demo application using Grunt

To serve the demo application using [Grunt](http://gruntjs.com/), you need to install [Node.js](http://nodejs.org/) and [npm](https://npmjs.org/). Note that installing Node.js should install npm as well.

Once npm is installed, run the following commands in the cloned directory:

`npm install` - Install dependencies

`grunt` - Serve the website in Google Chrome using Grunt

#### Capturing Demo Video

* The background image is of an iPhone 6
    - Video dimensions should be near 375x667 or 748×1108
* To capture a mobile demo video of a web app on OS X,
    - Use [Chrome DevTools to emulate an iPhone 6](https://developers.google.com/web/tools/setup/device-testing/devtools-emulator).
    - Use [QuickTime Player to record the portion of the screen](https://support.apple.com/kb/PH5882?locale=en_US) that shows your web app.

## Example

![demo](./doc/app-video-demo.gif)