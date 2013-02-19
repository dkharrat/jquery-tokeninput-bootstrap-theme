# Bootstrap theme for jQuery Tokeninput

This repository contains a .less file that provides a [Boostrap](http://twitter.github.com/bootstrap/) theme for the [jQuery Tokeninput](http://loopj.com/jquery-tokeninput/) plug-in.

## Screenshot
<img src="http://i.imgur.com/DT1OkbB.png" width=525 />

## How to Use

1. Copy the `token-input-bootstrap.less` file to your app assets directory. If you're using Rails, it would go under `vendor/assets/stylesheets`
2. In your app's master less file, import `token-input-bootstrap`:
3. Enable the plug-in on an input field, with the `theme` option set to `bootstrap`

### Example
```
$(".token-input").tokenInput([
        {id: 7, name: "Ruby"},
        {id: 11, name: "Python"},
        {id: 13, name: "JavaScript"},
        {id: 17, name: "ActionScript"},
        {id: 19, name: "Scheme"},
        {id: 23, name: "Lisp"},
        {id: 29, name: "C#"},
        {id: 31, name: "Fortran"},
        {id: 37, name: "Visual Basic"},
        {id: 41, name: "C"},
        {id: 43, name: "C++"},
        {id: 47, name: "Java"}
    ], {
        theme: "bootstrap",
        preventDuplicates: true,
        tokenLimit: 5,
        hintText: null,
        animateDropdown: false
    });
```

