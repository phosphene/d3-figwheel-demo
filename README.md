# d3-fiqwheel-demo

Demo of d3 development using figwheel and Reagent/Re-frame with d3.js



## Overview

this is now merely a modified fork of simplecompoenent using Reagent/Re-frame with d3.js

see http://zachcp.github.io/simplecomponent/



## Setup

You will need Leiningen 2.0

https://github.com/technomancy/leiningen


Then clone this repository and type:


    lein figwheel

That will launch figwheel. This version will open your browser to  [localhost:3449](http://localhost:3449/).

Check your developer tools in your browser.

Changes to the source will be live loaded in your browser.

Other versions required the following.

To get an interactive development environment run:

    lein figwheel

and open your browser at [localhost:3449](http://localhost:3449/).
This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files:

    lein clean

To create a production build run:

    lein do clean, cljsbuild once min

And open your browser in `resources/public/index.html`. You will not
get live reloading, nor a REPL.

## License

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
