# yUML diagrammer
Allows the creation of offline UML diagrams based on the [yUML Syntax](http://yuml.me/).

## Features
* Currently, the following diagram types are supported: 
  + Class
  + Activity 
  + Use-case
  + State
  + Deployment
  + Package
  + Sequence
* Additional directives for altering diagram type and orientation
* Embedded rendering engine: **No need to call an external web service**

## yUML syntax
Please refer to the [wiki page](https://github.com/jaime-olivares/yuml/wiki)

## Invocation methods

````
Code sample here
````

## Dependencies
This npm package depends only on the [jsdom npm package](https://www.npmjs.com/package/jsdom), which is cross-platform and is installed automatically.

Also, it contains a frozen version of viz-lite.js (see [viz.js](https://github.com/mdaines/viz.js)). Newest versions have a bug that caused [issue #23](https://github.com/jaime-olivares/vscode-yuml/issues/23).
No other product or library is needed and thus the installation process is quite simple across platforms.

## Issue reporting
If you have experience developing Visual Studio Code extensions, please propose a detailed solution for any reported issue or feature request.

## Contributing
For pull requests, please read [CONTRIBUTING.md](https://github.com/jaime-olivares/yuml/blob/master/CONTRIBUTING.md)

## Credits
* Syntax and some examples taken from [yuml.me](http://yuml.me/diagram/scruffy/class/samples)
* This package uses a Javascript port of [Dot/Graphviz](http://www.graphviz.org/) called [viz.js](https://github.com/mdaines/viz.js)
* The yuml-to-dot translator is loosely based on a Python project called [scruffy](https://github.com/aivarsk/scruffy)
* The new sequence diagram is based on [this github fork](https://github.com/sharvil/node-sequence-diagram)