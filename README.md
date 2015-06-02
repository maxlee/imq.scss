# _imq.scss
Sass Media Queries including iOS devices.

## Get started
```scss
@import "imq";
```

## Example:

### Input:

```scss
body {
    width: 100%;
    @include media(iphone5) {
        width: 640px;
    }
}
```
### Output:

```css
body {
    width: 100%;
}
@media only screen and (min-device-width: 320px) and (max-device-width: 568px) and (-webkit-device-pixel-ratio: 2) {
    body {
        width: 640px;
    }
}
```

### License:

The MIT license
