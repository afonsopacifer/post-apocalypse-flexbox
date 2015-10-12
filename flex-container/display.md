# Display: [flex](#display:-flex;) | [inline-flex](#display:-inline-flex;);

## Display: flex;

### Flexbox mode:
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

### Apocalpse Zombie mode:

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

### Revelation Robots mode:

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

## Display: inline-flex;

### Flexbox mode:
```css
.container {
	display: inline-flex;
}
```

```css
.container {
	display: inline-flex;
	flex-direction: row; /* default */
	flex-wrap: nowrap; /* default */
	flex-flow: row nowrap;/* default (shorthand) */
	justify-content: flex-start; /* default */
	align-items: flex-start; /* default */
	align-content: flex-start; /* default but no effect */
}
```

[View support](http://caniuse.com/#search=flexbox)

### Apocalpse Zombie mode:

```css
.container {
	display: inline-block;
}

.flex-container > * {
	display: inline-block;
	margin-right: -4px;
}
```

[View support](http://caniuse.com/#search=CSS%202.1%20properties)

### Revelation Robots mode:

```css
.container {
	display: inline-grid;
	grid-template-columns: auto auto auto;
	grid-template-rows: auto;
}

/* Note:
In the "grid-template-columns" values,
use the "auto" equal the number of flex-items.
*/
```

[View support](http://caniuse.com/#search=CSS%20Grid%20Layout)
