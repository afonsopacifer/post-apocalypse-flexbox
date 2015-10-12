# Display Flex

## Table of Content

- [Flexbox mode](#flexbox-mode)
- [Apocalpse Zombie mode](#apocalpse-zombie-mode)
- [Revelation Robots mode](#revelation-robots-mode)

## Flexbox mode
```css
.container {
	display: flex;
}
```

```css
.container {
	display: flex;
	flex-direction: row; /* default */
	flex-wrap: nowrap; /* default */
	flex-flow: row nowrap;/* default (shorthand) */
	justify-content: flex-start; /* default */
	align-items: flex-start; /* default */
	align-content: flex-start; /* default but no effect */
}
```

[View support](http://caniuse.com/#search=flexbox)

## Apocalpse Zombie mode

Using the [CSS 2.1 properties](http://www.w3.org/TR/CSS21/propidx.html)

```css
.container {
	display: block;
}

.flex-container > * {
	display: inline-block;
	margin-right: -4px;
}
```

[View support](http://caniuse.com/#search=CSS%202.1%20properties)

## Revelation Robots mode
 Using the [CSS Grid Layout Module Level 1](http://www.w3.org/TR/2015/WD-css-grid-1-20150917/)

```css
.container {
	display: grid;
	grid-template-columns: auto auto auto;
	grid-template-rows: auto;
}

/* Note:
In the "grid-template-columns" values,
use the "auto" equal the number of flex-items.
*/
```

[View support](http://caniuse.com/#search=CSS%20Grid%20Layout)

### [<-- Back to home](../../README.MD)
