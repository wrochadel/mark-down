# &lt;mark-down&gt; & &lt;mark-down-editor&gt;

Web Component wrapper for Markdown using Polymer.

> Maintained by [Rob Dodson](https://github.com/robdodson).

## Demo

> [Check it live](http://robdodson.github.io/mark-down).

## Usage

1. Include platform.js and polymer.js:

  ```html
  <script src="./bower_components/platform/platform.js"></script>
  <script src="./bower_components/polymer/polymer.js"></script>
  ```

2. Include [marked][]:

  ```html
  <script src="./bower_components/marked/lib/marked.js"></script>
  ```

3. Import Custom Element:

  ```html
  <link rel="import" href="elements/mark-down.html">
  ```

4. Start using it!

  ```html
  <mark-down>Hello, **world!**</mark-down>

  <!-- or -->

  <mark-down-editor>Hello, **world!**</mark-down-editor>
  ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.1.0 October 02, 2013
  * Initial commit
* v0.2.1 October 03, 2013
  * Add mark-down-editor tag
* v0.2.2 October 07, 2013
  * Added text attribute so change handlers work
  * Added old and new syntax for styling host elements
* v0.2.3 October 09, 2013
  * Correct improper bower `main`
* v0.3.0 December 07, 2013
  * Do setup work in `ready` callback instead of `created`
* v0.4.0 December 07, 2013
  * Switch to [marked][] library

## License

[MIT License](http://opensource.org/licenses/MIT)

[marked]: https://github.com/chjj/marked