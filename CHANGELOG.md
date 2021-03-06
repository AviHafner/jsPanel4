## CHANGELOG

### Version 4.0.0-beta.3 *released 2018-02-17*

+ **added** property **globalCallbacks** to the global object **jsPanel** lets you add callback functions to all or a limited set of jsPanels at once
+ **change:** as of version 4.0.0-beta.3 jsPanel uses built-in SVGs for the controls icons. SVGs are stored in the new property **icons** of the global object jsPanel. So the directory **fonts** with all the _jsglyph_ icontfont files is obsolete
+ **change:** use of the PointerEvent API is turned off, only touch events and/or mouse events are used
+ **improved:** panel is fronted upon click in content section even if content is an iframe
+ **change:** *start, drag/resize, stop* callbacks of options **dragit/resizeit** now accept an array of functions
+ **change:** all **option.on...** callbacks except option.onwindowresize now accept an array of functions. **This change might necessitate a modification of your code**
+ **various bugfixes and improvements in js and css**
+ **ADDED** folder **es6module** with all necessary files to run jsPanel as native ES6 module

### Version 4.0.0-beta.2 *released 2018-01-08*

+ **new** setting **trigger** for option.dragit.snap
+ **new** setting **containment** for option.dragit.snap
+ **new** setting **repositionOnSnap** for option.dragit.snap
+ **new** setting **resizeToPreSnap** for option.dragit.snap
+ **new** panel property **snapped**
+ **option.syncMargins**, if used, will set option.dragit.snap.containment to *true*
+ **new** options **contentSize** and **panelSize** now accept percentage values
+ **change** in options contentSize and panelSize: if a string has only one value the second one is set to the first by default
+ **new** setting **ttipEvent** for tooltip extension
+ **added** polyfills to improve compatibility with IE11
+ **various bugfixes and internal improvements**

### Version 4.0.0-beta.1 *released 2017-12-07*

First public beta version of jsPanel version 4
