ARTemplating
============

A simplistic and unscientific performance comparison of mustache.js in UIWebView/WKWebView and GRMustache.

The test is simply to repeatedly render a fairly trivial template. This isn't a real-world test.

Rendering the example from [mustache.github.io](http://mustache.github.io/#demo) on an iPhone 6 running iOS 8.1:

> JavaScript in UIWebView: 1000 renderings took 0.523 seconds

> JavaScript in WKWebView: 1000 renderings took 0.125 seconds

> GRMustache in native view controller: 1000 renderings took 0.253 seconds

In all cases the template was pre-compiled.
