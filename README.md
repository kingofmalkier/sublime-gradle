# Origins

Forked from [the excellent start by koizuss](https://github.com/koizuss/sublime-gradle), I've kept this project separate because I think some of my changes are really philosophical departures that not everyone may want.

# Sublime Gradle

Support for use with [Gradle](http://www.gradle.org/) in [Sublime Text 3](http://www.sublimetext.com/3).

Use version:

* Sublime Text 3: Build 3059
* Gradle: 1.11

## Installation

**The easiest and best way to install is via the** [**Sublime Package Control**](http://wbond.net/sublime_packages/package_control) **plugin.** Package control makes it easier to upgrade and also ensure you won't get pre-release updates unless you specifically want to.

1. Open "Package Control: Add Repository" in your Command Palette and add to "https://github.com/kingofmalkier/sublime-gradle"

2. Open "Package Control: Install Package" in your Command Palette and search for "sublime-gradle"

(if you already have it installed, select "Package Control: Upgrade Package" to upgrade)

**To install manually and/or get the bleeding edge** using a shell/Terminal (on OS X, Linux or Cygwin), via git:

    cd ~/"Library/Application Support/Sublime Text 3/Packages/" # location on OS X; will be different on Linux & Windows
    git clone https://github.com/kingofmalkier/sublime-gradle

or, if you don't have git installed:

    cd ~/"Library/Application Support/Sublime Text 3/Packages/"
    curl -L https://github.com/kingofmalkier/sublime-gradle/tarball/master | tar xf -

The plugin should be picked up automatically. If not, restart Sublime Text.

## Usage

When using the extension .gradle, files should be automatically be detected as the Gradle type.

Project attributes (properties and methods) automatically highlight and auto-complete throughout the build file.

Typed tasks (Copy, Exec, etc.) should automatically highlight and auto complete only their own attributes, plus any attributes defined on the parent Task and Project attributes.

Recognized task types will highlight in a different color (in most color schemes) to emphasize that you are using a predefined type.

Tasks of any sort highlight as functions, which means that the "Goto Anything..." will offer them as choices when you use '@'.

## Bugs and Feature Requests

<https://github.com/kingofmalkier/sublime-gradle/issues>
