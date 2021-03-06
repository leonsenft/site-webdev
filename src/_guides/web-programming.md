---
title: "Overview: Web Libraries"
short-title: "Web Libraries"
description: "What libraries are available for writing web apps in Dart?"
---

The [Dart SDK][] contains [dart:html][] and other libraries
that provide low-level web APIs.
You can supplement or replace these APIs using
[web packages,][web packages]
such as those in the [AngularDart][] framework.

[Dart SDK]: /tools/sdk
[dart:html]: {{site.dart_api}}/{{site.data.pkg-vers.SDK.channel}}/dart-html/dart-html-library.html
[web packages]: https://pub.dartlang.org/web
[AngularDart]: /angular


## SDK libraries

The Dart SDK contains dart:html and other libraries
that provide low-level web APIs.

[Low-level web tutorials](/tutorials/low-level-html)
: An overview of DOM, CSS, and HTML concepts, with information on
  how to include a Dart script in an HTML page and
  how to add and remove elements from a web page.
  These tutorials feature interactive examples in
  [DartPad.]({{site.custom.dartpad.direct-link}})

[Tour of the dart:html library](/guides/html-library-tour)
: An example-driven tour of using the dart:html library.
  Topics include manipulating the DOM programmatically,
  making HTTP requests, and using WebSockets.

[dart:html API reference][dart:html]
: Complete reference documentation for the dart:html library.


## Web packages

Many packages support web development with Dart. Here are a few:

|-----------------+---------------------------------+--------------------------|
| Library         | Packages                        | Notes                    |
|-----------------|---------------------------------|--------------------------|
| AngularDart     | angular*                        | Useful for complex apps that support features such as event handling and dependency injection. More info: [AngularDart documentation](/angular), [AngularDart Components](/angular/components) | 
| Material Design | [md_core,][] [m4d_components][] | Basic Material Design components. |
| React           | [react][]                       | Bindings for the ReactJS library. |
| Vue             | [vue][]                         | Bindings for the Vue.js library. |
{:.table .table-striped}

[md_core,]: {{site.pub-pkg}}/m4d_core
[m4d_components]: {{site.pub-pkg}}/m4d_components
[vue]: {{site.pub-pkg}}/vue
[react]: {{site.pub-pkg}}/react

To find more libraries that support writing web apps, search for
[web packages.][web packages]


## JS interop

With the [`js` package,]({{site.pub-pkg}}/js), also known as _package:js,_
you can use one of the many existing libraries written in JavaScript.
For help using the `js` package, see the following:

[js_facade_gen](https://github.com/dart-lang/js_facade_gen)
: A tool that generates Dart code from JavaScript libraries that have
  [TypeScript type definitions.](http://definitelytyped.org/)

[dart_js_interop](https://github.com/matanlurey/dart_js_interop)
: Examples of using the `js` package,
  with comparisons to old code that uses the dart:js library.

[Packages that depend on `js`]({{pub-pkg}}?q=dependency%3Ajs)
: Published packages that have `js` in their pubspec.

{% comment %}
Check out these pages:

https://github.com/TheBosZ/dartins
https://medium.com/@thebosz/creating-a-dart-to-javascript-interop-library-c97da204c34a#.up26ibqyb
{% endcomment %}


---

Also see the [FAQ.](/faq)

[AngularDart]: /angular
