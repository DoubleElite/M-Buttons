# M-Buttons

M-Buttons is a CSS3 SASS button library designed around modular classes and ease-of-use.

## Install

### Method 1: SASS import

This method is the most configurable as it ties directly into your existing sass workflow. Add a new import `import 'm-buttons'` at the bottom of your main sass file. This will let you reference your own sass variables for the configuration of m-buttons.

### Method 2: CSS href

Either use the existing `m-buttons.css` file or compile it from the sass source and `<link>` it in your head tag.

## Default Usage

To use M-Buttons it's as simple as applying `m-button` to an anchor tag.

## Demo + Examples

To view live examples with code you can view my blog post on it [here](http://maxmckinney.com/?p=1185&preview=true)

## Modular Classes

M-Buttons is designed around the idea of modular classes. After applying the base `m-button` class you can append any of the following classes to modify the button appearance.

| Class     | Description       |
|------------|-----------------------------------------------------|
| m-wide     | Increases the horizontal length of the button       |
| m-round    | Increases the border-radius of the button           |
| m-large    | Increases the overall size of the button            |
| m-positive | Sets the color of the button to be a positive color |
| m-negative | Sets the color of the button to be a negative color |
| m-inline   | Decreases the size to be used in inline cases       |
