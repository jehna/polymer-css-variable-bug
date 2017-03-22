# Polymer CSS issue

## Installing

Run the following:

```
npm install
bower install
```

This installs the dependencies needed to run this issue

## Building

To build the script, run:

```
npm run build
```

This builds the application with most recent `polymer-cli` package

## Running

To run the app, just run:

```
npm start
```

This starts a simple Python SimpleHTTPServer in the `build/` directory

# Reproduce the issue

Build and run the project. Open website http://localhost:8081/ it with one of these browsers:

* IE11
* iOS 9 Safari
* Safari 9

You will see that the words "This should also be red" are not on red background.
