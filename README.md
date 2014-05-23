# &lt;embed-jsfiddle&gt;

Web Component wrapper for [jsFiddle's widgets](http://doc.jsfiddle.net/use/embedding.html) using [Polymer](http://www.polymer-project.org/).

> Maintained by [Varun Malhotra](https://github.com/softvar).

## Demo

> [Check it live](http://softvar.github.io/embed-jsfiddle).

## Installation

1. Using [bower](bower.io) to install. 

    ```sh
    $ bower install embed-jsfiddle
    ```

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/polymer.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/embed-jsfiddle.html">
    ```

3. Start using it!

    ```html
    <embed-jsfiddle></embed-jsfiddle>
    ```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

Or, you can have a bare minimum local server using python.


1. Clone this repo.

    ```sh
    $ git clone https://github.com/softvar/embed-js
    ```

2. Change the drectory-path in terminal.

    ```sh
    $ cd /path/to/this/dir
    ```

3. Run a local server 

    ```sh
    # to run local server on specified `PORTNUMBER`
    $ python -m SimpleHTTPServer `PORTNUMBER` 
    ```
    
    ```sh
    # to run local server on port:8000
    $ python -m SimpleHTTPServer
    ```

4. Open and point your browser to [http://locahost:8000](http://locahost:8000).

## Options

### &lt;embed-jsfiddle&gt;

Attribute  | Options                    | Default                                                | Description
---        | ---                        | ---                                                    | ---
`user`     | *string*                   | ``                                                     | User who created it
`fiddleid` | *string*                   | ``                                                     | The ID of the Fiddle
`skin`     | `light`, `presentation`    | `light`                                                | The skin layout
`tabs`     | `result,js,html,css`       | `result,js,html`                                       | The tabs that are going to be rendered
`width`    | *int*                      | `800`                                                  | The width of the element
`height`   | *int*                      | `300`                                                  | The height of the element

> See jsFiddle Embed Options [official documentation](http://doc.jsfiddle.net/use/embedding.html).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/softvar/embed-jsfiddle/releases).

## License

[MIT License](http://opensource.org/licenses/MIT) © Varun Malhotra
