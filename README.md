# ![Post Apocalypse Flexbox](post-apocalypse-flexbox.jpg)

> Tricks list to help implement the [flexbox](http://www.w3.org/TR/css3-flexbox/) features in a world where it is not supported.

## Rules

**Basic**

- No javascript.
- No css pre-processors.
- No css post-processors.
- We will create our tricks in two modes: [Apocalpse zombie]() and [Revelation robots]().

**Apocalpse zombie rules:**

- Use only properties with [support](http://caniuse.com/#search=flexbox) equal to or less than the flexbox.

**Revelation robots rules:**

- Be happy with [variables](http://www.w3.org/TR/css-variables/), [grid layout](http://www.w3.org/TR/2015/WD-css-grid-1-20150917/) and what you want ;D

## Flex container
*Properties for the Parent.*

- **display:** flex | inline-flex
- **flex-direction:** row | row-reverse | column | column-reverse
- **flex-wrap:** nowrap | wrap | wrap-reverse
- **flex-flow:** shorthand
- **justify-content:** flex-start | flex-end | center | space-between | space-around
- **align-items:** flex-start | flex-end | center | baseline | stretch
- **align-content:** flex-start | flex-end | center | space-between | space-around | stretch

## Flex items
*Properties for the Children.*

- **order:** *integer*
- **flex-grow:** *number*
- **flex-shrink:** *number*
- **flex-basis:** *length* | auto
- **flex:** shorthand
- **align-self:** auto | flex-start | flex-end | center | baseline | stretch

## Learn Flexbox?
See the [Awesome Flexbox](https://github.com/afonsopacifer/awesome-flexbox) project.

## Contributing

Want to contribute? [Follow these recommendations](CONTRIBUTING.md).

## Licence

[MIT Licence](LICENCE.md) © [Afonso Pacifer](https://github.com/afonsopacifer)
