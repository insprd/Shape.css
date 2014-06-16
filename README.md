# shape.css
*Grab-bag of CSS primitives, icons, and other shapes*

`shape.css` is a library of insertable shapes for you to use in your projects. Great for icon alternatives, popups, badges, and so on.

# Usage
Drop the stylesheet into your document's `<head>`, and add the corresponding shape class, and the class `shape` to any element in the `<body>`:

```html
<head>
  <link rel="stylesheet" href="animate.min.css">
</head>
```

```html
<i class="shape curved-arrow"></i>
```
*Note: the class `shape` adds the property `display: inline-block` to inline elements like `i` and `span`. this is necessary for CSS shapes to work properly on these elements. If this display property doesn't make sense for your use case, simply add a different display property using another selector with greater hierarchy.*

# Autoprefixer

Since browser support for CSS3 and prefixes are constantly changing, `shape.css` does not include them. You should implement [Autoprefixer](github.com/ai/autoprefixer) (recommended), or [-prefix-free](http://leaverou.github.io/prefixfree/).

You can also parse the prefixes yourself if you want to support certain vintage browsers.

# Shapes included:

- Curved arrow
- Star
- Heart