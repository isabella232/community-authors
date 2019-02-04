# Prisma Tutorials Code Formatting

In order to maintain code formatting consistency between articles in the Prisma Community Tutorials, we recommend using _Prettier_ to format any example code. [Prettier](https://prettier.io/) automatically format code run through it.

All code in Prisma Community Tutorials should go through run by Prettier, whether in a code editor, or within the [Prettier Playground](https://bitly.com/2Sp0d3a).

In addition to the standard prettier configuration, Prisma Community Tutorials should select the following Prettier options:

```
"prettier.singleQuote": true,
"prettier.trailingComma": "all",
"prettier.semi": false,
```

Prettier works with many editors, including VS Code, Atom, and Sublime Text, and the full list can be found on the Prettier site.
