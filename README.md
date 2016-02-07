# ![Post Apocalypse Flexbox](post-apocalypse-flexbox.jpg)

> List of tricks to help implement the [flexbox](http://www.w3.org/TR/css3-flexbox/) features in a world where it does not exist.

## What is the purpose of this project?
Create a fun way solutions that can help to implement the with progressive enhancement and learning and testing new technologies.

[![gitter.im](http://img.shields.io/badge/gitter-join%20chat%20%E2%86%92-brightgreen.svg?style=flat-square)](https://gitter.im/afonsopacifer/post-apocalypse-flexbox)

## Not know flexbox?
See the [Awesome Flexbox](https://github.com/afonsopacifer/awesome-flexbox) project.

## Rules

**Basic**

- No javascript.
- No css pre-processors.
- No css post-processors.
- We will create our tricks in two modes: **Apocalypse Zombie** and **Revelation Robots**.

**Apocalypse Zombie rules:**

- Use only properties with [support](http://caniuse.com/#search=flexbox) equal to or less than the flexbox.

**Revelation Robots rules:**

- Be happy with [variables](http://www.w3.org/TR/css-variables/), [grid layout](http://www.w3.org/TR/2015/WD-css-grid-1-20150917/) and what you want ;D

## Flex container
*Properties for the Parent.*

- **display** [flex](flex-container/display/flex.md) | [inline-flex](flex-container/display/inline-flex.md)
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

## Contributing

See the [project roadmap](https://github.com/afonsopacifer/post-apocalypse-flexbox/issues/1) and follow these [recommendations](CONTRIBUTING.md).

## Licence

[MIT License](LICENSE.md) © [Afonso Pacifer](https://github.com/afonsopacifer)
