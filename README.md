# Minimalistic responsive grid system
Simple 12 column grid system that works with only 3 types of screen sizes: small, medium, and large.

[Demo page](https://www.arcaweb.ch/arc-grid/demo)

## Setup

Add arc-grid.css to your project css folder and link it in your html header:

```html
<link rel="stylesheet" href="css/arc-grid.css">
```

## Usage

grid, row, col classes are required in order to work. Use s/m/l classes to define the column width for each display size.

### Eg. 3 column responsive grid
```html
<div class="grid">
  <div class="row">
    <div class="col m4"></div>
    <div class="col m4"></div>
    <div class="col m4"></div>
  </div>
</div>
```

### Eg. 1/3/4 column layout (small/medium/large)
```html
<div class="grid">
  <div class="row">
    <div class="col m4 l3"></div>
    <div class="col m4 l3"></div>
    <div class="col m4 l3"></div>
    <div class="col m4 l3"></div>
    <div class="col m4 l3"></div>
    <div class="col m4 l3"></div>
  </div>
</div>
```

### Column hiding
```html
<div class="grid">
  <div class="row">
    <div class="col s0"></div>
    <div class="col s0 m0"></div>
  </div>
</div>
```

See demo page source for more info.
