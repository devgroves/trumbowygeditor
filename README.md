<p align="center">
    <a href="http://alex-d.github.io/Trumbowyg/"><img src="banner.jpg" alt="" /></a>
</p>

<p align="center">
    <a href="https://bundlephobia.com/result?p=trumbowyg"><img src="https://img.shields.io/bundlephobia/minzip/trumbowyg.svg?style=for-the-badge" alt="Downloads" /></a>
    <a href="https://www.npmjs.com/package/trumbowyg"><img src="https://img.shields.io/npm/dm/trumbowyg.svg?color=blue&label=npm%20downloads&style=for-the-badge" alt="Downloads" /></a>
    <a href="https://github.com/Alex-D/Trumbowyg/blob/develop/LICENSE"><img src="https://img.shields.io/npm/l/trumbowyg.svg?color=blue&style=for-the-badge" alt="Licence" /></a>
    <br>
    <a href="https://www.npmjs.com/package/trumbowyg"><img src="https://img.shields.io/npm/v/trumbowyg.svg?color=blue&style=for-the-badge" alt="Version on npm" /></a>
    <a href="https://cdnjs.com/libraries/Trumbowyg"><img src="https://img.shields.io/cdnjs/v/Trumbowyg.svg?color=blue&style=for-the-badge" alt="CDNJS" /></a>
    <img src="https://img.shields.io/bower/v/trumbowyg.svg?color=blue&style=for-the-badge" alt="Version on bower" />
</p>

## Introduction

Trumbowyg is a simple and lightweight WYSIWYG editor, weight only 20kB minifed (8kB gzip) for faster page loading.

## 2.Getting Started

# Getting Started with Trumbowyg

## Using CDN

### Installation

1. Include Trumbowyg CSS and JS files in your HTML file:

    ```html
    <head>
        <title>Your Web Page</title>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/trumbowyg@2.26.0/dist/ui/trumbowyg.min.css">
        <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/trumbowyg@2.26.0/dist/trumbowyg.min.js"></script>
    </head>
    ```

2. Initialize Trumbowyg on a textarea:

    ```html
    <body>
        <textarea id="default-editor"></textarea>
        <script>
            $(document).ready(function() {
                $('#default-editor').trumbowyg();
            });
        </script>
        <div id="default-editor"></div>
    </body>
    ```

## Using npm

### Installation

1. Install Trumbowyg using npm:

    ```bash
    npm install trumbowyg
    ```

2. Include Trumbowyg CSS and JS files in your HTML file:

    ```html
    <head>
        <link rel="stylesheet" href="./node_modules/trumbowyg/dist/ui/trumbowyg.min.css">
        <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
    </head>
    ```

3. Initialize Trumbowyg on a textarea:

    ```html
    <body>
        <textarea id="default-editor"></textarea>
        <script>
            $(document).ready(function(){
                $('#default-editor').trumbowyg();
            });
        </script>
    </body>
    ```

Adjust the IDs and file paths as needed for your project.

## conclusion 
 Getting started with Trumbowyg is a straightforward process, whether you choose to include it via CDN or use npm for package management. By following the outlined steps, you can easily integrate Trumbowyg into your web project, providing users with a powerful and customizable WYSIWYG editor for content creation. Explore Trumbowyg's extensive features to enhance the text editing experience in your applications.
## License

This project is under [MIT license](LICENSE).
