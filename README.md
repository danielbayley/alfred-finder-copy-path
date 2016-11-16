[![badge][npm]][package]

Finder Copy Path _[Alfred]_ [workflow]
======================================
Easily copy the current Finder path in a variety of formats.

<img width="600px" src="https://media.githubusercontent.com/media/danielbayley/alfred-finder-copy-path/master/demo.gif" alt="demo"></img>  
\* Demo using the _[mnml]_ Alfred [theme].

---

This workflow will act on the first item selected in Finder, or default to the current folder path if no selection is made. The chosen path will be copied to the clipboard; A Post Notification can easily be [added] to the workflow if required.

<kbd>⌥</kbd> select to `'`quote`'` path.  
<kbd>⌘</kbd> select to `"`double quote`"` path.  
<kbd>⇧</kbd> select to append `/` to folder path.  
<kbd>⌃</kbd> select to `\` escape spaces in path, or [decode] a [URL]. Also prefix file `.`extensions.

Install
-------
This workflow requires [Node].js (easily available with _[Homebrew]_) and [Alfred] 3 with the paid _[Powerpack]_ upgrade.

~~~ sh
brew install node
npm install -g alfred-finder-copy-path
~~~

License
-------
[MIT] © [Daniel Bayley]

[MIT]:                    LICENSE.md
[Daniel Bayley]:          https://github.com/danielbayley

[alfred]:                 http://alfredapp.com
[mnml]:                   https://github.com/danielbayley/alfred-mnml-light
[theme]:                  http://alfredapp.com/help/appearance
[powerpack]:              https://alfredapp.com/powerpack
[workflow]:               http://alfredapp.com/workflows
[added]:                  http://alfredapp.com/help/workflows/outputs/post-notification
[packal]:                 https://packal.org/workflow/finder-copy-path
[awm]:                    https://github.com/jonathanwiesel/awm

[npm]:                    https://img.shields.io/npm/v/alfred-finder-copy-path.svg?style=flat-square
[package]:                https://npmjs.com/package/alfred-finder-copy-path
[node]:                   https://nodejs.org
[homebrew]:               http://brew.sh

[URL]:                    https://en.wikipedia.org/wiki/Uniform_Resource_Locator
[decode]:                 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/decodeURI
