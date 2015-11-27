# Evolving Work

A presentation based on the book [Reinventing Organizations](http://www.reinventingorganizations.com/), built using the excellent [reveal.js HTML presentation framework](http://lab.hakim.se/reveal-js/#/).

Contributions and pull requests welcome, this is a living presentation!

### Running locally

These instructions assume you have Node and npm already installed.

First, clone this repository and enter the directory:

```shell
git clone git@github.com:dzello/evolving-work.get
cd evolving-work
```

Install [harp](http://harpjs.com/).

```shell
npm install harp --global
```

Serve the `src` directory with harp via an npm command:

```shell
npm start
```

Open a browser window and you should see the presentation:

```shell
open http://localhost:9000
```

Changes that you make to the presentation will be visible immediately, just refresh the browser.

### Publishing

To publish your changes to a `gh-pages` branch run `npm run publish`. The source of the script is in `bin/publish`.

### Wow factor

This is all it takes to make a whole slide:

```jade
section
  p This presentation was created for the students of St. Jean de Passy in Paris, France.
  img(src="images/noun_school.png")
```
