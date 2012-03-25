A collection of (mostly) others sass/scss I stole

# Using

> sass pablo.sass pablo.css
> cp your app
> @import 'pablo'

# Components

_backgrounds.sass

- @mixin bordered-background-dark($color)
- @mixin bordered-background-light($color)

_clearfix.sass

- @mixin clearfix

_fonts.sass

- @mixin font-face($font-family, $font-url, $font-name, $style: normal, $weight: normal)

_forms.sass

- @mixin normaliseSelect

_images.sass

- @mixin image-link($width, $height, $image_name)

_math.sass

- @function power($x, $n)
- @function factorial($x)
- @function sin($x)
- @function cos($x)

_sprites.sass

- @mixin sprite($file, $row: 1, $col: 1, $width: 16px, $height: 16px)

_transparency.sass

- @mixin opacity($opacity)

# Libs

- _silk_sprite.sass
- css3please.sass
- ie6fixes.sass
- triangle.scss

# Resets

- ericmeyer.sass
- normalize.sass
