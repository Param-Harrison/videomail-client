### TODOs
| Filename | line # | TODO
|:------|:------:|:------
| src/wrappers/container.js | 302 | figure out how to fire dom's onload event again
| src/wrappers/container.js | 303 | or how to run all the scripts over again
| src/wrappers/optionsWrapper.js | 27 | fix this, it's not really an option
| src/util/audioRecorder.js | 11 | code needs rewrite
| src/util/eventEmitter.js | 6 | MAKE EVENT EMITTING IN DESPOT NOT GLOBAL BUT BY CONTAINER ID INSTEAD
| src/util/eventEmitter.js | 43 | have this emitted through a configuration because it is pretty noisy
| src/util/humanize.js | 4 | get rid of this class and use those imports directly
| src/wrappers/visuals/recorder.js | 529 | in https://github.com/binarykitchen/videomail-client/issues/142
| src/wrappers/visuals/recorder.js | 558 | retry with navigator.getUserMedia_() maybe?
| src/wrappers/visuals/recorder.js | 687 | commented out because for some reasons server does not accept such a long
| src/wrappers/visuals/recorder.js | 692 | consider removing this later or have it for debug=1 only?
| src/wrappers/visuals/userMedia.js | 290 | consider removing that if it's not the case anymore (for better performance)
| gulpfile.js | 1 | write this in ES6 once i have figured out how to
| gulpfile.js | 60 | fix this, so that it also works when not minified, this
| gulpfile.js | 65 | location is bad, should be in a temp folder or so