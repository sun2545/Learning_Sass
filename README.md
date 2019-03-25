$colors: (color1: blue, color2: red, color3: green); <br>

@each $key, $color in $colors { <br>
  .#{$color}-text {color: $color;} <br>
}
