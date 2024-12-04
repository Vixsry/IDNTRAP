# IDNTRAP

IDNTRAP is a modern and lightweight CSS framework designed to help you build web interfaces quickly and easily. Its concept is similar to Bootstrap but more streamlined, focusing on the needs of developers.

---

## Key Features

- **Responsive Design:** Fully supports desktop, tablet, and mobile devices.
- **Ready-to-Use Components:** Buttons, cards, navbars, forms, and more.
- **Easy Customization:** CSS variables for theme adjustments.
- **Lightweight and Fast:** Small file size for optimal performance.
- **Shell Icon Support:** Includes pre-designed shell icons for seamless integration.

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
        <h1 class="text-center">Welcome to IDNTRAP</h1>
        <button class="btn btn-primary">Click Me</button>
        <i class="icon-shell"></i>
    </div>
</body>
</html>
```

### Core Components

1. **Buttons:**
   ```html
   <button class="btn btn-primary">Primary</button>
   <button class="btn btn-secondary">Secondary</button>
   <button class="btn btn-danger">Danger</button>
   ```

2. **Grid System:**
   ```html
   <div class="row">
       <div class="col-6">Column 1</div>
       <div class="col-6">Column 2</div>
   </div>
   ```

3. **Cards:**
   ```html
   <div class="card">
       <div class="card-header">Header</div>
       <div class="card-body">This is the card content.</div>
       <div class="card-footer">Footer</div>
   </div>
   ```

4. **Shell Icons:**
   ```html
   <i class="icon-shell"></i>
   <i class="icon-shell-outline"></i>
   <i class="icon-shell-filled"></i>
   ```

---

## Customization

Use CSS variables to change themes and colors:

```css
:root {
    --primary-color: #00aaff;
    --secondary-color: #004466;
    --font-family: 'Poppins', sans-serif;
    --icon-color: #008080;
    --background-theme: #e0f7fa;
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

Visit [idntrap.com/docs](https://idntrap.com/docs) for detailed documentation and guides.

---

## Contact

If you have any questions or suggestions, reach out to us at: support@idntrap.com.
