# IDNTRAP COMING SOON

IDNTRAP is a modern and lightweight CSS framework designed to help you build web interfaces quickly and easily.Modern and responsive interface

---

## Key Features

- **Responsive Design:** Fully supports desktop, tablet, and mobile devices.
- **Ready-to-Use Components:** Buttons, cards, navbars, forms, and more.
- **Easy Customization:** CSS variables for theme adjustments.
- **Lightweight and Fast:** Small file size for optimal performance.

---

## Installation

### 1. Via CDN

Add the following link to the `<head>` of your HTML file:

```html
<link rel="stylesheet" href="https://cdn.idntrap.com/latest/idntrap.min.css">
```

### 2. Via NPM

If you're using Node.js, install IDNTRAP via npm:

```bash
npm install idntrap
```

Import IDNTRAP in your CSS or JavaScript file:

```css
@import 'idntrap';
```

### 3. Manual Download

Download the CSS file from [IDNTRAP's official website](https://idntrap.com) and add it to your project:

```html
<link rel="stylesheet" href="/path/to/idntrap.min.css">
```

---

## Usage

### Basic Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IDNTRAP Example</title>
    <link rel="stylesheet" href="https://cdn.idntrap.com/latest/idntrap.min.css">
</head>
<body>
    <div class="container">
        <h1 class="tx-center">Welcome to IDNTRAP</h1>
        <button class="btn idnt-btn-blue">Click Me</button>
        <i class="idn-name icon"></i>
    </div>
</body>
</html>
```

### Core Components

1. **Buttons:**
   ```html
   <button class="btn idnt-btn-blue">Blue</button>
   <button class="btn idnt-btn-white">White</button>
   <button class="btn idnt-btn-red">Red</button>
   ```



---

## Customization

Use CSS variables to change themes and colors:

```css
:root {
    --white: #ffffff;
    --black: #000000;
    --red: #ff0000;
    --green: #00ff00;
    --blue: #0000ff;
    --yellow: #ffff00;
    --cyan: #00ffff;
    --magenta: #ff00ff;
    --gray: #808080;
    --silver: #c0c0c0;
    --maroon: #800000;
    --olive: #808000;
    --lime: #00ff00;
    --teal: #008080;
    --navy: #000080;
    --fuchsia: #ff00ff;
    --aqua: #00ffff;
    --orange: #ffa500;
    --purple: #800080;
    --pink: #ffc0cb;
    --brown: #a52a2a;
    --beige: #f5f5dc;
    --gold: #ffd700;
    --peach: #ffdab9;
    --violet: #ee82ee;
    --lavender: #e6e6fa;
    --turquoise: #40e0d0;
    --indigo: #4b0082;
    --coral: #ff7f50;
    --salmon: #fa8072;
    --tan: #d2b48c;
    --khaki: #f0e68c;
    --plum: #dda0dd;
    --periwinkle: #ccccff;
    --chartreuse: #7fff00;
    --limegreen: #32cd32;
    --seagreen: #2e8b57;
    --forestgreen: #228b22;
    --darkgreen: #006400;
    --darkblue: #00008b;
    --darkred: #8b0000;
    --darkorange: #ff8c00;
    --darkviolet: #9400d3;
    --crimson: #dc143c;
    --firebrick: #b22222;
    --mediumvioletred: #c71585;
    --steelblue: #4682b4;
    --royalblue: #4169e1;
    --skyblue: #87ceeb;
    --lightblue: #add8e6;
    --powderblue: #b0e0e6;
    --darkslategray: #2f4f4f;
    --dimgray: #696969;
    --lightgray: #d3d3d3;
    --slategray: #708090;
    --darkorchid: #9932cc;
    --mediumorchid: #ba55d3;
    --lightpink: #ffb6c1;
    --hotpink: #ff69b4;
    --darkgoldenrod: #b8860b;
    --goldenrod: #daa520;
    --wheat: #f5deb3;
    --moccasin: #faebd7;
    --papayawhip: #ffefd5;
    --blanchedalmond: #ffebcd;
    --cornsilk: #fff8dc;
    --linen: #faf0e6;
    --seashell: #fff5ee;
    --mistyrose: #ffe4e1;
    --lavenderblush: #fff0f5;
    --oldlace: #fdf5e6;
    --gainsboro: #dcdcdc;
    --lightcyan: #e0ffff;
    --lightgoldenrodyellow: #fafad2;
    --lightgray: #d3d3d3;
    --lightsteelblue: #b0c4de;
    --mediumslateblue: #7b68ee;
    --darkseagreen: #8fbc8f;
    --lightseagreen: #20b2aa;
    --palegreen: #98fb98;
    --mediumaquamarine: #66cdaa;
    --mediumturquoise: #48d1cc;
    --lightcoral: #f08080;
    --indianred: #cd5c5c;
    --chocolate: #d2691e;
    --saddlebrown: #8b4513;
    --sienna: #a0522d;
    --peru: #cd853f;
    --burlywood: #deb887;
    --tan: #d2b48c;
    --rosybrown: #bc8f8f;
    --lightpink: #ffb6c1;
    --palevioletred: #db7093;
    --mediumvioletred: #c71585;
    --darkmagenta: #8b008b;
    --darkviolet: #9400d3;
    --darkslateblue: #483d8b;
    --mediumslateblue: #7b68ee;
}

:root {
    --white-glass: rgba(255, 255, 255, 0.7);
    --black-glass: rgba(0, 0, 0, 0.7);
    --red-glass: rgba(255, 0, 0, 0.5);
    --green-glass: rgba(0, 255, 0, 0.5);
    --blue-glass: rgba(0, 0, 255, 0.5);
    --yellow-glass: rgba(255, 255, 0, 0.5);
    --cyan-glass: rgba(0, 255, 255, 0.5);
    --magenta-glass: rgba(255, 0, 255, 0.5);
    --gray-glass: rgba(128, 128, 128, 0.5);
    --silver-glass: rgba(192, 192, 192, 0.5);
    --maroon-glass: rgba(128, 0, 0, 0.5);
    --olive-glass: rgba(128, 128, 0, 0.5);
    --lime-glass: rgba(0, 255, 0, 0.5);
    --teal-glass: rgba(0, 128, 128, 0.5);
    --navy-glass: rgba(0, 0, 128, 0.5);
    --fuchsia-glass: rgba(255, 0, 255, 0.5);
    --aqua-glass: rgba(0, 255, 255, 0.5);
    --orange-glass: rgba(255, 165, 0, 0.5);
    --purple-glass: rgba(128, 0, 128, 0.5);
    --pink-glass: rgba(255, 192, 203, 0.5);
    --brown-glass: rgba(165, 42, 42, 0.5);
    --beige-glass: rgba(245, 245, 220, 0.5);
    --gold-glass: rgba(255, 215, 0, 0.5);
    --peach-glass: rgba(255, 218, 185, 0.5);
    --violet-glass: rgba(238, 130, 238, 0.5);
    --lavender-glass: rgba(230, 230, 250, 0.5);
    --turquoise-glass: rgba(64, 224, 208, 0.5);
    --indigo-glass: rgba(75, 0, 130, 0.5);
    --coral-glass: rgba(255, 127, 80, 0.5);
    --salmon-glass: rgba(250, 128, 114, 0.5);
    --tan-glass: rgba(210, 176, 140, 0.5);
    --khaki-glass: rgba(240, 230, 140, 0.5);
    --plum-glass: rgba(221, 160, 221, 0.5);
    --periwinkle-glass: rgba(204, 204, 255, 0.5);
    --chartreuse-glass: rgba(127, 255, 0, 0.5);
    --limegreen-glass: rgba(50, 205, 50, 0.5);
    --seagreen-glass: rgba(46, 139, 87, 0.5);
    --forestgreen-glass: rgba(34, 139, 34, 0.5);
    --darkgreen-glass: rgba(0, 100, 0, 0.5);
    --darkblue-glass: rgba(0, 0, 139, 0.5);
    --darkred-glass: rgba(139, 0, 0, 0.5);
    --darkorange-glass: rgba(255, 140, 0, 0.5);
    --darkviolet-glass: rgba(148, 0, 211, 0.5);
    --crimson-glass: rgba(220, 20, 60, 0.5);
    --firebrick-glass: rgba(178, 34, 34, 0.5);
    --mediumvioletred-glass: rgba(199, 21, 133, 0.5);
    --steelblue-glass: rgba(70, 130, 180, 0.5);
    --royalblue-glass: rgba(65, 105, 225, 0.5);
    --skyblue-glass: rgba(135, 206, 235, 0.5);
    --lightblue-glass: rgba(173, 216, 230, 0.5);
    --powderblue-glass: rgba(176, 224, 230, 0.5);
    --darkslategray-glass: rgba(47, 79, 79, 0.5);
    --dimgray-glass: rgba(105, 105, 105, 0.5);
    --lightgray-glass: rgba(211, 211, 211, 0.5);
    --slategray-glass: rgba(112, 128, 144, 0.5);
    --darkorchid-glass: rgba(153, 50, 204, 0.5);
    --mediumorchid-glass: rgba(186, 85, 211, 0.5);
    --lightpink-glass: rgba(255, 182, 193, 0.5);
    --hotpink-glass: rgba(255, 105, 180, 0.5);
    --darkgoldenrod-glass: rgba(184, 134, 11, 0.5);
    --goldenrod-glass: rgba(218, 165, 32, 0.5);
    --wheat-glass: rgba(245, 222, 179, 0.5);
    --moccasin-glass: rgba(250, 235, 215, 0.5);
    --papayawhip-glass: rgba(255, 239, 213, 0.5);
    --blanchedalmond-glass: rgba(255, 235, 205, 0.5);
    --cornsilk-glass: rgba(255, 248, 220, 0.5);
    --linen-glass: rgba(250, 240, 230, 0.5);
    --seashell-glass: rgba(255, 245, 238, 0.5);
}
:root {
    --box-shadow-color: rgba(0, 0, 0, 0.5);
    --box-shadow-color-alt: rgba(37, 252, 255, 0.37);
    --box-shadow-light: rgba(255, 255, 255, 0.3);
    --box-shadow-dark: rgba(0, 0, 0, 0.8);
    --box-shadow-blue: rgba(0, 123, 255, 0.5);
    --box-shadow-green: rgba(40, 167, 69, 0.5);
    --box-shadow-purple: rgba(108, 117, 255, 0.5);
    --box-shadow-black: rgba(0, 0, 0, 0.6);
    --box-shadow-gold: rgba(255, 193, 7, 0.5);
    --box-shadow-red: rgba(220, 53, 69, 0.5);
    --box-shadow-cyan: rgba(23, 162, 184, 0.5);
    --box-shadow-gray: rgba(108, 117, 125, 0.5);
    --box-shadow-pink: rgba(255, 102, 204, 0.5);

    --box-shadow-blue-soft: rgba(0, 123, 255, 0.2);
    --box-shadow-green-soft: rgba(40, 167, 69, 0.2);
    --box-shadow-purple-soft: rgba(108, 117, 255, 0.2);
    --box-shadow-red-soft: rgba(220, 53, 69, 0.2);
    --box-shadow-cyan-soft: rgba(23, 162, 184, 0.2);

    --box-shadow-gradient-1: linear-gradient(45deg, rgba(0, 123, 255, 0.5), rgba(40, 167, 69, 0.5));
    --box-shadow-gradient-2: linear-gradient(45deg, rgba(255, 193, 7, 0.5), rgba(220, 53, 69, 0.5));
    --box-shadow-gradient-3: linear-gradient(45deg, rgba(108, 117, 255, 0.5), rgba(255, 102, 204, 0.5));
}
```

---

## Contribution

We highly appreciate your contributions to IDNTRAP. Please fork this repository, make changes, and submit your pull requests.

### Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/username/idntrap.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

---

## License

IDNTRAP is released under the MIT license. You are free to use it for personal or commercial projects.

---

## Full Documentation

Visit :Soon for detailed documentation and guides.

---

## Contact

If you have any questions or suggestions, reach out to us at: Soon