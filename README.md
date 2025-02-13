---
title: CheerpJ - Convert Java to WebAssembly and JavaScript
---

[![Gitter chat](https://badges.gitter.im/leaningtech/cheerpj.svg)](https://gitter.im/leaningtech/cheerpj)
[![GitHub Issues](https://img.shields.io/github/issues/leaningtech/cheerpj-meta.svg)](https://github.com/leaningtech/cheerpj-meta/issues)
[![Live Demos](https://img.shields.io/badge/demo-online-green.svg)](https://leaningtech.com/demo/?cheerpjfilter)

CheerpJ is a Java bytecode to WebAssembly and JavaScript compiler, compatible with 100% of Java, which allows to compile any Java SE application, library or Java applet into a WebAssembly/JavaScript application.

**Main project link**: <http://leaningtech.com/cheerpj/>

**Download latest version**: [![Latest version](https://img.shields.io/badge/cheerpj-2.2-green.svg)](https://leaningtech.com/download-cheerpj/)  [![Latest version changelog](https://img.shields.io/badge/2.2-changelog-green.svg)](Changelog)

**Link to latest runtime**: ``https://cjrtnc.leaningtech.com/2.2/loader.js``

If you are unsure how to start, try our [Tutorial](Tutorial).

What is CheerpJ?
------

<p align="center"><img src="assets/cheerpj_visual_2.png" width="450"></p>

CheerpJ is constituted of three components:
1. The CheerpJ AOT compiler, an LLVM-based Java-bytecode to JavaScript compiler. This can be used to convert Java archives (e.g. .jar) or single .class files to JavaScript. The CheerpJ AOT compiler is available for Linux, macOS and Windows.
2. The CheerpJ runtime library, a full Java SE runtime in WebAssembly and JavaScript, that can be distributed in part or in full with applications converted with CheerpJ.
3. The CheerpJ on-the-fly Java-to-JavaScript compiler, a reduced JavaScript version of the CheerpJ compiler that can be distributed with applications converted with CheerpJ to enable dynamic features of Java such as reflection.

What is unique about CheerpJ?
-------

1. CheerpJ can convert 100% of Java including reflection and proxy class creation, with no manual intervention on the code.
2. CheerpJ works directly on Java bytecode, and does not require access to the Java source code.
3. CheerpJ comes with a full Java SE runtime, inclusive of Swing/AWT. It supports audio, printing, and any other Java SE component. The runtime supports WebAssembly for optimal performance and size.
4. The JavaScript code generated by CheerpJ is highly optimised and garbage-collectible.
5. CheerpJ enables bidirectional Java-JavaScript interoperability. JavaScript libraries, as well as the DOM, can be called and manipulated from Java. Converted Java modules can be invoked from JavaScript.
6. CheerpJ supports Java multi-threading. In addition, it allows to create concurrent applications by using WebWorkers.

Getting Started
-------

You can download CheerpJ for Linux, Windows and macOS on our website (https://leaningtech.com/cheerpj/)

To get started with CheerpJ, please refer to the following pages:
1. [CheerpJ Tutorial](Tutorial)
2. [Getting Started](Getting-Started)
3. [Command Line Options](Command-Line-Options)

Demos
------

Several demos of CheerpJ can be found at https://leaningtech.com/demo/?cheerpjfilter


Bugs and Questions
-------
 
We welcome any feedback and bug report on it through our [Issue Tracking](https://github.com/leaningtech/cheerpj-meta/issues).

You can also find us on [Gitter](https://gitter.im/leaningtech/cheerpj).
