# React-Data-Viewer

A simple React component to render data structures (objects, arrays or any other) in the browser.

![alt text](https://github.com/jalba/react-data-viewer/raw/master/images/react-data-viewer.png "React-Data-Viewer")

## Usage

via npm:

```
npm install react-data-viewer --save
```
Or you can just pull it from github and import it.
In case you are not using something like Babel in your project, or you are simply not comfortable
yet with ES2015 syntax, there is an ES5 version as well. Just look for the ES5 folder.

## Props

`data [any type, required]` this is the data structure to render, it can be an object, an array, or
even a boolean, number or string.

`indent [number, optional]` this the indentation of the items or attributes rendered. By default is
40 pixels.

`expanded [bool, optional]` this tells the component if it should be rendered open or closed. By 
default is open.

`className [string, optional]` this is an optional class name that you can add to the component.

## Tests
very simple test suite with mocha and React shallow rendering. Just run npm test to check it out.

## Examples

In the folder examples, you are going to be able to check a couple of very simple ones. Feel free
to play around with them to see the possibilities of the components.

To run the examples, from the root of the package:

```
cd ./examples
npm install
npm start
```

The examples are built on top of the excellent [react-hot-boilerplate](https://github.com/gaearon/react-hot-boilerplate), by Dan Abramov. 

