# Grid css

simple better than complex

## How to use

The grid css provides a simple system to create responsive layouts.
in the table `i` is any number from 1 to 32

| Class  | Explanation  |
|---|---|
| `.grid_container`  | area that will be use for grid |
| `.columns-i`  | ammount of columns that the container will have  |
| `.column-fill-i`  | ammount of columns that an element inside the `.grid_container` will occupy  |

## Responsiveness

any class except `.grid_container` can have the delimiter `sm:`, `md:`, `lg:`, `xl:` in front of them, in syntaxis similar to **Tailwind**, responding to the following screen sizes.

| Delimiter  | Screen Size  |
|---|---|
| none | `0px` and beyond |
| sm | `640px` and bigger  |
|  md | `768px` and bigger  |
| lg  | `1024px` and bigger  |
| xl  | `1280px` and bigger  |

## Example

```html
<div class="grid_container columns-10 sm:columns-2">

    <div class="
    column-fill-1
    sm:column-fill-1
    md:column-fill-2
    lg:column-fill-2
    xl:column-fill-4">
        Lorem Ipsum
    </div>
</div>
```

### For bootstrap users

as you may have noticed there are a group of files with the bootstrap denotation these ones uses a bootstrap like syntaxis for the responsive sizes, with the same behavoir.

```html
<div class="grid_container columns-10 columns-sm-2">

    <div class="
    column-fill-1
    column-sm-fill-1
    column-md-fill-2
    column-lg-fill-2
    column-xl-fill-4">
        Lorem Ipsum
    </div>
</div>
```

## Download

go to the css folder and download the version that suits you most.
