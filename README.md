Library-App [![Code Climate](https://codeclimate.com/github/ipcross/ansme/badges/gpa.svg)](https://codeclimate.com/github/ipcross/ansme) [![Build Status](https://travis-ci.org/ipcross/ansme.svg?branch=master)](https://travis-ci.org/ipcross/ansme) [![Test Coverage](https://codeclimate.com/github/ipcross/ansme/badges/coverage.svg)](https://codeclimate.com/github/ipcross/ansme/coverage)
=========

Example Application Tutorial for Ember.js 2.8

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

1. Clone in your project folder [repository from GitHub](https://github.com/ipcross/library-app):

    ```
    git clone git://github.com/ipcross/library-app.git
    ```

2. Change to the application directory:

    ```
    cd library-app
    ```

3. Install node and bowel install:

    ```
    npm install && bower install
    ```

4. Copy config/environment.js.example to config/environment.js and edit this file in order to configure your settings.

    ```
    cp config/environment.js.example config/environment.js
    ```


5. Launch the application with Ember server:

    ```
    ember server
    ```

6. Open the application in your browser:

    ```
    [http://localhost:4200](http://localhost:4200)
    ```


### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Thanks

Thanks to all our [awesome
contributors](https://github.com/ipcross/library-app/graphs/contributors)

## Copyright

Copyright (c) 2016 Dmitry Alifanov. See MIT-LICENSE for details.
