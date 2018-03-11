# p5.js Quick Start Repo


[p5.js](https://p5js.org/) is:

> a JavaScript library that starts with the original goal of [Processing](https://processing.org/), to make coding accessible for artists, designers, educators, and beginners, and reinterprets this for today's web.

Generally you'd want to start with the web editor for p5.js, via something like

- [The super secret new editor](https://alpha.editor.p5js.org/)
- [A web based tutorial](https://creative-coding.decontextualize.com/first-steps/)
- [OpenProcessing](https://www.openprocessing.org/)

The [getting started](https://p5js.org/get-started/) page also walks you through
using sublime text for working with p5.js, but there are a couple of things missing.

This repo takes the [Complete Library](https://p5js.org/download/) download, wraps
it in a git repo, and includes a couple of extra features:

- limited typescript support including
	- typescript based autocomplete suport
	- typescript based error detection
- instructions for visual studio code
- instructions for live-server / live coding
- A self-contained single location for local use

## Setting up

1. Clone this repo:

    git clone https://github.com/EchoAbstract/p5.js-starter.git p5.js

2. Copy the example sketch to a new sketch:

    cd p5.js
    cp -R empty-example first-sketch
    
3. Setup your editor

### Setting up Visual Studio Code

Install the [live-server extension](https://github.com/ritwickdey/vscode-live-server)

Type **⌘⇧P** then enter _Install Extensions_ and search for _live-server_., reload
when prompted and you should be ready to go.

### Sublime Text

Halp!  This needs filled in!

## Typescript

The typescript support was grabbed from a
[blog post](http://processing.toolness.org/general/2016/03/16/typescript-to-the-rescue.html)
by the Friendly Error Fellowship, so it may be a bit dated, and there might
be a better way to get this set up.  I haven't had too much time to play with
it yet.



