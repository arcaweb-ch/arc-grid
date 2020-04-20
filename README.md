# Super tiny responsive grid system
Simple 12 column grid system in less than 2k, for your lightweight responsive project. It works with only 3 types of screen sizes: small, medium, and large to keep things as simple as possible.

## Demo
Demo page:
https://www.arcaweb.ch/arc-grid/demo

## Setup

Add arc-grid.css to your project css folder and link it in your html header:

```
<link rel="stylesheet" href="css/arc-grid.css">
```

## How to use

grid, row, col classes are required in order to work. Use s/m/l column classes with the number of column span.

### Eg. 3 column responsive grid
```
<div class="grid">
  <div class="row">
    <div class="col m4"></div>
    <div class="col m4"></div>
    <div class="col m4"></div>
  </div>
</div>
```

### Eg. 1/3/4 column layout (small/medium/large)
```
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

See demo page source for more info.
