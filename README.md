# Firefox Developer Tools

These are the tools provided by [Firefox](https://www.mozilla.org/firefox/) for developers to inspect Web code.

We abide by our [code of conduct](CODE_OF_CONDUCT.md), and expect all contributors to do the same.

## Documentation

* [End user guides](https://developer.mozilla.org/en-US/docs/Tools).
* [Developers documentation](http://docs.firefox-dev.tools/).

## News and demos

We publish news and updates to two blogs:

* [Nightly](https://blog.nightly.mozilla.org/tag/devtools/) for features newly added to Firefox Nightly. This is the place to request feedback from early adopters!
* [Hacks](https://hacks.mozilla.org/category/developer-tools/) when features reach more stable versions of Firefox.

You're more than encouraged to talk, write articles, or [make demos](https://github.com/devtools-html/devtools-demos) about the tools. Let us know 🙂

## Getting in touch

* Bug reports or feature requests:
  * [File bugs in Mozilla's Bugzilla](https://bugzilla.mozilla.org/enter_bug.cgi?product=DevTools) (please respect the [etiquette](https://bugzilla.mozilla.org/page.cgi?id=etiquette.html))
  * or under each repository in [devtools-html](https://github.com/devtools-html) for code in GitHub.
  * Report vulnerabilities to `security@mozilla.org`. [More info](https://www.mozilla.org/en-US/security/#For_Developers).
* [List of open bugs](http://bugs.firefox-dev.tools/). Might be interesting if you want to contribute.
* [DevTools forum](https://discourse.mozilla-community.org/c/devtools).
* [Mailing list](https://groups.google.com/forum/#!forum/mozilla.dev.developer-tools).
* Team weekly video call: [Vidyo room DevTools](https://v.mozilla.com/flex.html?roomdirect.html&key=n9vJUD3L1vRMHKQC5OCNRT3UBjw), Tuesdays 9AM Pacific time. [Meeting notes](https://docs.google.com/document/d/1pUx9xq6L7bonSrDpyUNTQkQxTxAsULLu4kkHZLMEq6w/edit).
* Chat:
  * Join the [Firefox DevTools Slack](https://devtools-html-slack.herokuapp.com/),
  * or IRC: `#devtools` channel on `irc.mozilla.org`.
* Twitter: [@FirefoxDevTools](https://twitter.com/FirefoxDevTools).

## Processes

Most changes will be done via either the "pick a bug and send a patch" or "send a PR" processes.

For substantial changes, we ask that a "request for comment" (RFC) document is provided first, so we can examine what the implications of a change will be. Here is [how to follow the RFC process](https://github.com/devtools-html/rfcs/).

### People and modules

The tools are broadly divided into panels. Each panel has one or more owners, who mostly work(s) on that panel and are the best people to ask if you have specific questions about the code.

* about:debugging: jdescottes, ochameau, ladybenko
* Animation Inspector: gl, pbro, daisuke
* Canvas Debugger: `<unmaintained>`
* Console: bgrins, nchevobbe
* Debugger: jlast, dwalsh
* DOM: honza
* Font Editor: rcaliman, gl, pbro
* Framework: Browser integration, toolbox and test infrastructure: jryans, bgrins, ochameau, honza
* Inspector: gl, pbro, jdescottes, tromey, rcaliman, mtigley, bwerth
* JSON Viewer: honza
* Memory: gregtatum
* Network Monitor: honza
* Performance: gregtatum, julienw
* Remote protocol and server infrastructure: jryans, ochameau, yulia
* Responsive Design Mode: jryans, gl, bwerth
* Scratchpad: jdescottes
* Shader Editor: `<unmaintained>`
* Style Editor: gl
* Storage Inspector: mikeratcliffe
* Themes: bgrins, ntim
* Web Audio Editor: `<unmaintained>`
* WebIDE: jryans, ochameau, jdescottes
