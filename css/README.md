## SCSS Styleguide Linter

These SCSS rules are the result of effort to standardize code during Spree Themes development; it's the fruit of discussions initiated by:

- Carlos Mumo
- Fernando Perales
- Herman Moreno
- Edmundo Perez
- Emmanuel Delgado

Currently Copied from: [Spree Themes: Scss Lint](https://github.com/magma-labs/spree-themes-source-code-/blob/master/.scss-lint.yml)

It's not intended to be the Holy Grail but the very basis towards high quality styling.

### Configuration

[Scss-lint](https://github.com/brigade/scss-lint) to
do an automated syntax analysis of your SCSSS; please refer to the [documentation](https://github.com/brigade/scss-lint#editor-integration) for editor integration.

Basically, you'll need to copy the `.scss-lint.yml` to your project's root folder.

### Some Tips

#### Fonts

It's a good practice to use `10px` attached to the `html` element in
order to express all the required font size changes on `rem` and make
those calcutations easy to perform.


```
html {
  font-size: 10px;
}
```

With this, if the design guideline requires a 64px font, the CSS will
look like this:

```
p {
  font-size 6.4rem;
}
```

### TODO:

- Update with more tips
- Add references to styleguides
- Add linter for plain css
- Create a Wiki (?)
