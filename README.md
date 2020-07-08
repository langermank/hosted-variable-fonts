# hosted-variable-fonts
A place to store and host open source variable fonts to use outside of my own domains

[Cabin Variable](https://github.com/impallari/Cabin)

[Source Sans Pro Variable](https://github.com/adobe-fonts/source-sans-pro)

[Source Serif Pro Variable](https://github.com/adobe-fonts/source-serif-pro)

## To use
Import the `font-face` def file into your CSS:

`@import url("https://langermank.github.io/hosted-variable-fonts/css/fonts.css");`

Set font-family

```
.cabin {
  font-family: "Cabin Variable", sans-serif;
  font-variation-settings: "wght" 94, "wdth" 100;
  font-feature-settings: "salt";
}
```

Look at `test.css` for more examples
