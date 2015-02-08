ShortCSS
========

Библиотека [Stylus](http://learnboost.github.io/stylus/) для короткой записи CSS-свойств

Stylus:

    body
      -bgc #000
      -c #fff

    #content
      -ff sans-serif

    #element
      -d block
      -w 150
      -h 100
      b-radius 7px
      -br 1px solid #eee

CSS:

    body {
      background-color: #000;
      color: #fff;
    }
    #content {
      font-family: sans-serif;
    }
    #element {
      display: block;
      width: 150;
      height: 100;
      -webkit-border-radius: 7px;
      -moz-border-radius: 7px;
      -o-border-radius: 7px;
      -ms-border-radius: 7px;
      -khtml-border-radius: 7px;
      border-radius: 7px;
      border: 1px solid #eee;
    }

