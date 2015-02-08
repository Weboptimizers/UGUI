#![UGUI Logo](_assets/logo/ugui-logo.png "Universal Graphical User Interface")

##Universal Graphical User Interface

**UGUI gives a face to command line programs, and that face is HTML, CSS, & JS.**

* * *

###Download

Download UGUI to use it for your project:

* Version 1.0 (Coming *very* soon) | Tutorial for Version 1.0 (Coming Soon)

* * *

###What is UGUI

UGUI is a library and framework for NW.JS (formally Node-Webkit) that is design to make creating a desktop application as easy as possible. We specifically target the creation of GUI applications for command line programs, however UGUI can also be used as a general purpose starting point for any type of desktop application.

Our goal is to allow anyone, even those with no prior coding knowledge, to create a desktop application in just 5 minutes.

* * *

###Project Roadmap

Current Version: V0.95 **almost there!**

**Phase 1: ugui.js**

* V1.0 ~~Create ugui.js that will help abstract out connecting switches through the HTML/JS, to make the process as simple as possible for front end designers.~~
* V1.0 ~~Create UGUI logo.~~
* V1.0 ~~Remove all browser specific stuff that isn't relevant like -moz, -o, -ms, filter, old -webkit, EOT, etc.~~
* V1.0 ~~Clean up template to have generic sample content.~~
* V1.0 Update GitHub project to separate repos for UGUI Framework, Templates, Website, CLI, and UGUI Designer.
* V1.0 Update layout design using Bootstrap.
* V1.0 Create About/Help modal using dynamic information. Separate user about from UGUI about markup.
* V1.0 Test out htmlEscape() to see if special characters work when sent to the commandline.
* V1.5 Add some type of JSHint-like library to UGUI Dev Tools to inform developers about syntax errors.
* V1.5 Test packaging in different OS environments.

**Phase 2: Templates and Site**

* Create several templates based on Twitter Bootstrap for different types of applications to give people quick places to start from.
 * Hardware Pack template to be created using D3.JS library to graphically display information about hardware such as CPU and RAM usage.
 * File System Pack template to be created to display information about files in a folder, file sizes, etc.
 * 3D Pack template using OpenGL and three.js to take advantage of 3D.
 * System Tray template for windowless application using native system tray and context-menu.
 * Mega Pack which combines most of the parts from all other official template packs.
 * More general templates that just focus on different visual layouts.
 * Advanced templates for more unique CMD programs.
* Create UGUI site that organizes templates and tutorials and lays everything out in a quick and easily digestible manner. Also highlights programs using UGUI.
* Create Explainer and tutorial videos.
* Advertise the existence of this project like crazy!

**Phase 3: UGUI Designer**

* Ultimately I'd like to make a program that makes this whole process far less manual. The program, *UGUI Designer*, would have the following features:
 1. Detect all JS and CSS files, uglify, minify, concat them in to one JS and one CSS doc.
 2. Remove any files not being used in the production version (git files, sass, etc.)
 3. Ability to export project to different environments (Win 32/64, Ubuntu, OSX, etc.)
 4. Eventually the exporting function would create an installer for Windows that will check if the required version of NW.js is already installed and if not download and install it, allowing for much smaller file sizes when packaging and distributing.

* * *

###Credits

* [The Jared Wilcurt](http://github.com/TheJaredWilcurt) - Creator/Maintainer
* [Hai Nguyen](http://github.com/nmhai3) - Javascript Expert
* [Alissa Renz](http://github.com/alissarenz) - Bootstrap Expert, template designs
* [NW.JS](http://nwjs.io) - The foundation of UGUI! Special thanks to Roger Wang.
 * [IO.JS](http://iojs.org)
 * [Chromium](http://www.chromium.org)
 * [V8](https://code.google.com/p/v8)
* [jQuery](http://jquery.com)
* [Twitter Bootstrap](http://getbootstrap.com)
* [Bootswatch](http://bootswatch.com)
* [strip-json-comments](https://github.com/sindresorhus/strip-json-comments)
* [DropZoneJS](http://www.dropzonejs.com)
* [Dudley Storey](http://demosthenes.info/blog/864/Auto-Generate-Marks-on-HTML5-Range-Sliders-with-JavaScript) - For range slider increments, though this will likely be replaced with [Slider for Bootstrap](http://seiyria.github.io/bootstrap-slider)
* [Cut, Copy, Paste Context Menu](https://github.com/b1rdex/nw-contextmenu)
* [Sass](http://sass-lang.com) - Just cuz it's awesome