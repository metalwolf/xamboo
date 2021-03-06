@UTF-8

Xamboo for GO v0.0.2
=======================
This is the build 2

Xamboo is the result of over 15 years of manufacturing engineering frameworks, originally written for PHP 7+ and now ported to GO 1.8+

It is a very high quality framework for CMS, made in GO 1.8 or higher, fully object-oriented and strong to distribute code into Web portals with heavy load and REST APIs optimization.

Xamboo is freeware, and uses several other freeware components (XConfig)

Xamboo is an engine to build applications that distribute any type of code to the client:
It is completely independent of the generated code, i.e. you can send HTML, XHTML, XML, SGML, javascript, JS, JSON, WAP, PDF, etc.

Xamboo works on sites currently distributing more than **60 millions web pages monthly**, (that's near 500 pages per second on peak hour) it serves regular sites, and GRAPH-APIs / REST APIs to APP-mobiles.


Version Changes Control
=======================

V0.0.2 - 2018-??-??
-----------------------
> This version is working, examples are working, but the system is still incomplete
> Uses XConfig 0.0.2
- Added Context in engine and local context to calculate pages
- Added engine wrapper to call from a server (engine callback for a sub-page)
- Added support for memory caches in servers (page, instance, code)
- ".code" compiler implemented for simple pages
- Added language, template, code, library, cache servers
- Added identity server to calculate the correct identity for each page object
- Creation of Context object to send to every engine instance/page to build
- Logger implemented (now directed to stdout)
- Added VERSION constant in core/core.go

V0.0.1 - 2018-11-06
-----------------------
> Uses XConfig 0.0.1
- First commit, still not fully working

TO DO
=======================
- creates a fake SSH key cert for examples to put in examples dir
- simple code server injector
- Pass params (from url or from page call) into context, server call and wrapper
- implement nested [[BOX in simple code metalanguage
- language server compiler + injector
- template server compiler + injector
- library server/runner for GO pre-compile page with pipe data interchange
- Caches generator
- cache autocheck vs original file on HD
- page library and snippets PHP-compatible code ? (check go call PHP with pipe data interchange)
- page library and snippets JS-compatible code ? (check go call NODE with pipe data interchange)
- support for files (images, js, etc)

Manuals
=======================

- If you want to help converting the manual from text into .md file, you are most welcome.
- Translations are also welcome
