ClaferToolsST
=============

v0.3.7

Integration of [Clafer Tools](http://clafer.org) into [Sublime Text 2/3](http://www.sublimetext.com/).

Contributors
------------

* [Michał Antkiewicz](http://gsd.uwaterloo.ca/mantkiew), Main developer.

Features and Usage
------------------

* Syntax highlighting
* Compilation `<CTRL>+b`
* Instance generation using
   * Alloy-based instance generator with simple scope inference `<CTRL>+i, g, s`
   * Alloy-based instance generator with full scope inference `<CTRL>+i, g, f`
   * Choco-based instance generator with simple scope inference `<CTRL>+i, g, c`
   * Z3 SMT-based instance generator with simple scope inference `<CTRL>+i, g, m`

Installation
------------

0. Install [Sublime Text 3](http://www.sublimetext.com/3) or [Sublime Text 2](http://www.sublimetext.com/2)
1. In Sublime Text
   * Install [Package Control](https://sublime.wbond.net/installation)
   * Install packages SublimeREPL, ClaferToolsST, and, optionally, SidebarExtensions 
      * `Preferences->Package Control->Install Package` 
      * type the name of the package
   * Open the `Packages` folder 
      * `Preferences->Browse Packages...`
      * `cd ClaferToolsST3`
      * Copy the folders `Clafer` and `SublimeREPL` from this project into your Sublime's `Packages` folder
4. Download the latest binary distribution of Clafer Tools
   * [Clafer Tools](http://gsd.uwaterloo.ca/clafer-tools-binary-distributions)
   * Unzip the contents of the folder `clafer-tools-0.3.*` into `Packages/Clafer`
      * Make sure the folder structure is NOT `Packages/Clafer/clafer-tools-0.3.*`

Planned Improvements
--------------------

* Code snippets for quantified expressions such as `[ all disj x1; x2 : X | ... ]`
* Ease installation via Package Control directly