# HandyTab Remix Icons

This is a customized version of the Remix Icon library, tailored for the HandyTab project. It includes a curated set of icons and custom additions.

## Usage

### Webfont Usage

#### Installation

If you publish this package to npm under the name `handytabremixicons`, you can install it via:

```bash
npm install handytabremixicons --save
```

Then, import the CSS into your project's main entry file:

```javascript
import 'handytabremixicons/fonts/handytabremixicons.css'
```

#### CDN

Once published, you can use a CDN link. For example, with jsDelivr:

```html
<link
    href="https://cdn.jsdelivr.net/npm/handytabremixicons@1.0.0/fonts/handytabremixicons.css"
    rel="stylesheet"
/>
```

#### Manual Usage

1.  Copy the `fonts/` directory into your project.
2.  Add the following link to the `<head>` tag of your HTML document:

```html
<link rel="stylesheet" href="path/to/your/fonts/handytabremixicons.css">
```

### How to Use

Add icons using an `<i>` tag with the appropriate class name. The class name rule is `htri-{name}-{style}`.

```html
<i class="htri-admin-line"></i>
<i class="htri-admin-fill"></i>
```

#### Sizing

You can resize icons using the integrated CSS classes. Icons inherit the `font-size` of their parent.

```html
<div style="font-size: 24px;">
  <i class="htri-admin-line htri-fw"></i> <!-- fixed width -->
  <i class="htri-admin-line htri-xxs"></i> <!-- 0.5em -->
  <i class="htri-admin-line htri-xs"></i> <!-- 0.75em -->
  <i class="htri-admin-line htri-sm"></i> <!-- 0.875em -->
  <i class="htri-admin-line htri-1x"></i> <!-- 1em -->
  <i class="htri-admin-line htri-lg"></i> <!-- 1.3333em -->
  <i class="htri-admin-line htri-xl"></i> <!-- 1.5em -->
  <i class="htri-admin-line htri-2x"></i> <!-- 2em -->
  <i class="htri-admin-line htri-3x"></i> <!-- 3em -->
  ...
  <i class="htri-admin-line htri-10x"></i> <!-- 10em -->
</div>
```

### SVG Sprite Usage

Use the `handytabremixicons.symbol.svg` file with a `<use>` element:

```html
<svg class="remix">
    <use xlink:href="your-path/handytabremixicons.symbol.svg#htri-admin-fill"></use>
</svg>
```

```css
.remix {
    width: 24px;
    height: 24px;
    fill: #333;
}
```

## Icon Search Keywords

The [`tags.json`](./tags.json) file is used to manage search keywords for the icons. You can edit this file to improve searchability for your custom set.

## License

This library is based on the [Apache License Version 2.0](./License). The original Remix Icon is licensed under the same. Feel free to use these icons in your products and distribute them. The only thing we ask is that these icons are not for sale.