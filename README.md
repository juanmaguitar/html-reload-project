# HTML reload-browser (& autoprefixer) project

This project is a boilerplate to start easily projects in an environment where you can easily reload the browser when you save any file in it

## Installation

To start working w/ it you first have to do

    npm install

## Start

To launch the tools just do

    grunt

This will open the folder public (and the `index.html` in it) in the browser. Also it will reload the browser any time you save any file in the project

## Autoprefix

The autoprefix tool is included in the task runned by grunt. That means that all the code you write in `/src/style.css` will be transformed into the `/public/bundle-style.css` w/ all the autoprefixes included 

You can ignore this autoprefix and work directly w/ the `index.html` as the browser will also reload when you modify it