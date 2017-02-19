# H Element Specification [<img src="https://rawgit.com/jonathantneal/h-element-spec/gh-pages/html-logo.svg" alt="H Element Specification" width="90" height="90" align="right">][H Element Specification]

[![Build Status][cli-img]][cli-url]
[![Licensing][lic-img]][lic-url]

The [H Element Specification] lets you use contextual headings within HTML.

```html
<body>
<h>This is a top level heading</h>
<p>....</p>
<section>
  <p>....</p>
  <h>This is a second-level heading</h>
  <p>....</p>
  <h>This is another second-level heading</h>
  <p>....</p>
</section>
<section>
  <p>....</p>
  <h>This is another second-level heading</h>
  <p>....</p>
  <section>
    <h>This is a third-level heading</h>
    <p>....</p>
  </section>
</section>
</body>
```

### Prollyfill

You can try the h element right now with [CodePen], or use it in your own projects using the [hfill] library.

[cli-url]: https://travis-ci.org/jonathantneal/h-element-spec
[cli-img]: https://img.shields.io/travis/jonathantneal/h-element-spec.svg
[lic-url]: LICENSE.md
[lic-img]: https://img.shields.io/npm/l/h-element-spec.svg

[H Element Specification]: https://rawgit.com/jonathantneal/h-element-spec/gh-pages/
[hfill]: https://github.com/jonathantneal/hfill
[CodePen]: http://codepen.io/jonneal/pen/wgombw
