# brick-layout

> A [Brick](https://github.com/mozbrick/brick/) layout component.

## Demo

[Check it live!](http://mozbrick.github.io/brick-layout)

## Usage

1. Import Web Components polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/element.html">
    ```

3. Start using it:

    ```html
    <brick-layout></brick-layout>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`horizontal`  | *boolean*   | -            | Use a horizontal instead of the default vertical layout.

## Development

Brick components use [Stylus](http://learnboost.github.com/stylus/) to generate their CSS.

This repository comes outfitted with a set of tools to ease the development process.

To get started:

* Install [Bower](http://bower.io/) & [Gulp](http://gulpjs.com/):

    ```sh
    $ npm install -g bower gulp
    ```

* Install local dependencies:

    ```sh
    $ npm install && bower install
    ```

While developing your component, there is a development server that will watch your files for changes and automatically re-build your styles and re-lint your code.

To run the development server:

* Run `gulp server`
* Navigate to `http://localhost:3001`

To simply build and lint your code, run `gulp build`.

You can also push your code to GitHub Pages by running `gulp deploy`.
