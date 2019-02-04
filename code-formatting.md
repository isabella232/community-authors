# Prisma Tutorials Code Formatting

In order to maintain code formatting consistency between articles in the [Prisma Community Tutorials](https://www.prisma.io/tutorials/), we recommend using **Prettier** to standardize any example code. [Prettier](https://prettier.io/) is an opinionated code formatter and automatically formats any code run through it.

All code in Prisma Community Tutorials should be run by Prettier, whether in a code editor, or within the [Prettier Playground](https://bitly.com/2Sp0d3a). Prettier works with many editors, including _VS Code_, _Atom_, and _Sublime Text_, and the full list can be found on the Prettier site.

In addition to the standard Prettier configuration, Prisma Community Tutorials should also use the the following Prettier options:

```
{
  "singleQuote": true,
  "semi": false,
  "trailingComma": "all"
}
```



