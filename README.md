# Bootstrap 5 Window 98 theme

[![Release](https://github.com/Bloafer/bootstrap5-windows98theme/actions/workflows/Release.yml/badge.svg)](https://github.com/Bloafer/bootstrap5-windows98theme/actions/workflows/Release.yml)

[![NPMJS Status](https://github.com/Bloafer/bootstrap5-windows98theme/actions/workflows/NPM.yml/badge.svg?event=release)](https://github.com/Bloafer/bootstrap5-windows98theme/actions/workflows/NPM.yml)

View live example: https://win98.example.bloafer.com/


This is a simple Windows 98 style theme for Bootstrap 5, just place the CSS file after the bootstrap CSS and you're good to go

# Installation

Assuming you already have Bootstrap 5 installed, all you need to do is run the following:

```
npm install bootstrap5-windows98theme
```

# Usage in Laravel 11 using Vite

## Plain CSS

Add the following after Bootstrap CSS files in your pre-compiled CSS (`resources/css/app.css`)

```
@import 'bootstrap5-windows98theme/dist/css/98.css';
```

## SASS

Add the following after Bootstrap CSS files SASS file (`resources/scss/app.scss`)

```
@import 'bootstrap5-windows98theme/scss/98.scss';
```

## Finally

Then just run `npm run build` assuming you're not doing live compiles in the background

Once the server is up and running you should see the updated site