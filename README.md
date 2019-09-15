# Flexible CSS

## Description
Flexible is a bare bone flexbox row column framework

## Development
Flexible uses [sass](https://sass-lang.com) to build the css library. This is done for several reasons.
1. I  am lazy and prefer the easy syntax of sass
2. Flexible implements [normalize.css](https://necolas.github.io/normalize.css/) as a base
3. If, in the future, I decide to add more features to the framework sass make modularity easier

Flexible uses [dart-sass](https://github.com/sass/dart-sass) to compile style.sass to css.

The dev and build process require that you install dart-sass. To install the dart-sass cli, run the following command:
```
npm install -g sass 
```

Then run `npm run dev` to begin developing. There is a test directory that contains a test page. Simply open the `index.html` file in your browser.
Alternatively you can use a webserver to like one of [these](https://gist.github.com/willurd/5720255)

## Build
To build Flexible run the following command
```
npm run build
```

the transpiled CSS is outputed to `dist/flexible.css[.map]`
