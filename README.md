# jsdom-little
Lightweight cut down version of [jsdom](https://github.com/tmpvar/jsdom).

## Removed dependencies:
* **contextify**
* xmlhttprequest
* request

## Removed features:
* Running JavaScript code in browser context
* Fetching or processing external rewsources
* Events
* XmlHttpRequest
* jsdom.env(...)

## What it is good for?
* You need something from jsdom (DOM, parsing, etc.) but full browser emulation is overkill.

## Why not use original jsdom?
* jsdom uses native module [contextify](https://github.com/brianmcd/contextify), see [link](https://github.com/tmpvar/jsdom#contextify).
