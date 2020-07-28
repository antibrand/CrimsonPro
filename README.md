# serif

A variable serif font.

![cover image](https://raw.githubusercontent.com/antibrand/serif/master/cover.jpg)

## Variable

The variable version has adjustable weight.

### Variable Weight

Weight available from `100` to `800`.

## Variable Example

Check for font-variation-settings support.

```scss
h1 {
    font-family: 'serif', NonBreakingSpaceOverride, 'Hoefler Text', Garamond, 'Lucida Bright', Lucidabright, 'Lucida Serif', Lucida, 'Liberation Serif', 'Times New Roman', Constantia, Times, Georgia, serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';

    // Set font weight as bold.
    font-weight: 700;
}

    // Make slightly bolder than bold.
    @supports( font-variation-settings: wght ) {
        h1 {
            font-variation-settings: 'wght' 735;
        }
    }
```

## Static

The static versions are as follows.

### Static Styles

Two styles are available for each of the static weights.

`normal, italic`

### Static Weights

Eight weights available for each of the static styles.

`100, 200, 300, 400, 500, 600, 700, 800, 900`

`extra-light, light, regular, medium, semi-bold, bold, extra-bold, black`
