# HTML reload-browser (& autoprefixer) project

This project is a boilerplate to start easily projects in an environment where you can easily reload the browser when you save any file in it

## Installation

To use this tool you need to have installed (globally) in your machine [Node](https://nodejs.org/en/), [NPM](https://www.npmjs.com/) (included in the node installation) and [grunt](http://gruntjs.com/getting-started)

To download this starter you can do

    git clone https://github.com/juanmaguitar/html-reload-project.git <YOUR-PROJECT-NAME>
    cd <YOUR-PROJECT-NAME>
    rm -rf .git

_Remember to change `<YOUR-PROJECT-NAME>` by your project's name_

After that you need to install the project's dependencies by doing 

    npm install

## Start

To launch the tools just do

    grunt

This will open the folder public (and the `index.html` in it) in the browser. Also it will reload the browser any time you save any file in the project

## Autoprefix

The autoprefix tool is included in the task runned by grunt. That means that all the code you write in `/src/style.css` will be transformed into the `/public/bundle-style.css` w/ all the autoprefixes included 

You can ignore this autoprefix and work directly w/ the `index.html` as the browser will also reload when you modify it

## Deploy

If you link a remote github repo to this project you can "deploy" easily using [github's gh-pages](https://www.thinkful.com/learn/a-guide-to-using-github-pages/) feature with the command

    npm run gh-pages:deploy

    