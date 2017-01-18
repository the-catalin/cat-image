[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/the-catalin/cat-image)

# &lt;cat-image&gt;

`<cat-image>` is a [Polymer](https://github.com/Polymer/polymer) element that displays an image with different possible effects: Ken Burns (zoom effect) and text appearance effects. The text is displayed via [&lt;cat-text&gt;](https://github.com/the-catalin/cat-text) element.

## Demo

## [LIVE DEMO with Config Panel](http://webcomponents.online/cat-image/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install --save cat-image
```

Or [download as ZIP](https://github.com/the-catalin/cat-image/archive/master.zip)

## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/cat-image/cat-image.html">
    <link rel="import" href="bower_components/cat-text/cat-text.html">
    ```

3. Start using it!

	```html
	<cat-image src="your-image.jpg">
		<cat-text>First sample text</cat-text>
		<cat-text>Second one</cat-text>
	</cat-image>
	```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

For detailed changelog, check [Releases](https://github.com/the-catalin/cat-image/releases).

## License

[The MIT License (MIT)](https://opensource.org/licenses/MIT)

Copyright (c) 2017 Catalin Ungureanu