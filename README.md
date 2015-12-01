# AngularJS - MarkdownDeep

This repository provides source and a demo for use of this AngularJS MarkdownDeep UI directive. 

A [**demo**](http://angularjs-markdowndeep-demo.appsoftware.com) for this project is available.

This is the markdown editor that provides markdown editing capability at [**iocontent.com**](https://www.iocontent.com/documentation/markdown-editor), see this service for a full demonstration of client and server side processing using MarkdownDeep.

MarkdownDeep is a robust markdown processing framework comprising both client and server side components. MarkdownDeep provides it's own UI library, however I needed to redesign the UI and chose to build using AngularJS. 

The markdown deep client libraries are split so that the UI is decoupleable from core markdown processing and event handling. As such only two of the client script files have been copied to this repository.

## MarkdownDeep

From [http://www.toptensoftware.com/markdowndeep/](http://www.toptensoftware.com/markdowndeep/)

> MarkdownDeep is an open-source (read license) implementation of the increasingly popular web publishing syntax Markdown. MarkdownDeep provides a high performance implementation for ASP.NET web-servers along with a compatible JavaScript implementation for client side use.

Please check the original MarkdownDeep project licences before inclusion in your project it may differ from the licence we have granted for use of code specific to this repository.

## MarkdownDeep Versions

At the time of writing, the client and server libraries available at [https://github.com/toptensoftware/markdowndeep](https://github.com/toptensoftware/markdowndeep) are several revisions ahead of the files that can be downloaded from the [official project home page](http://www.toptensoftware.com/markdowndeep/).

We needed bug fixes that have been included since the latest stable version release, and have forked the GitHub repo to [https://github.com/appsoftware/markdowndeep](https://github.com/appsoftware/markdowndeep).

While our fork may not track future bugfixes in MarkdownDeep, it is compatible with this AngularJS directive. .NET C# server side processing code is available in this repository also. 

Please see official documentation for the [API reference](http://www.toptensoftware.com/markdowndeep/api).


## Demo Project Styling

This project includes some rough styling to demonstrate the split screen preview and synced scrolling mechanism. It is expect that anyone integrating this project will update they stylesheet(s) according to their own tastes and requirements.
