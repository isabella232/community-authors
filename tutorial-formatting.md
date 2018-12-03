# Tutorial Formatting

Prisma tutorials use MDX formatting. MDX adds a wide range of additional functionality on top of regular Markdown. All normal markdown works within MDX.

You can find a page with an example of Prisma MDX components [here](https://www.prisma.io/docs/prisma-cli-and-configuration/test-article-as9j).

### Headers

Top line headers should all be H2 (##); if you are creating subcategories, you can use H3 (###) headers. Try to avoid H4s— if you find you are getting so nested, you may want to revisit the structure of the article. Try to make your headers as descriptive as possible (a teeny summary of what’s being covered in that section), but avoid including step numbers.

### Images

Any images included in tutorials will be hosted by Prisma. When submitting your tutorials with images, please host them on imgur, and they will later be migrated.

![an image of a Prisma Diagram](https://prisma-tutorial-images.ams3.cdn.digitaloceanspaces.com/Home%20Diagram%202.png)

### Line Level Formatting

*(As adapted with some changes from the [DigitalOcean style guide](do.co/style))*

**Bold** text should be used for:

* Visible GUI text

* Hostnames and usernames

* Term lists

*Italics* should only be used when introducing technical terms. For example, *resolvers* define how GraphQL fetches data.

`In-line code` formatting should be used for:

* Command names, like npm install -g prisma

* Optional commands

* File names and paths, like .../prisma/datamodel.graphql

* Example URLs, like http://example.com

* Ports, like :3000

### Code Blocks

Code blocks can be thought of in two different categories— codeblocks for commands and codeblocks for longer code files.

#### Commands

When writing commands, you can use standard markdown to start a command block. You should not include any additional indicators of the command prompt or similar (for example, no need to have lines start with $ or #).

#### Code Blocks

Longer code blocks should be rendered with MDX. You can see an example of how this works below:

![codeblock](https://prisma-tutorial-images.ams3.cdn.digitaloceanspaces.com/codeblock.png)

With longer code blocks you have a number of additional configurations that are supported by MDX, these include:

* Highlighting specific lines (This is done with the “lines” property). This can be useful to show where an individual should make changes in a long file.

* Linking to the source of a file. You can include a link to the full file that a codeblock is from with the “source” property.

* Highlighting specific parts of the line, especially to be used as variables. (This can be done by putting the content in quotes and dollar signs. Example: “$YOUR_PRISMA_ENDPOINTS$”)

### MDX Components

In addition to the standard markdown capabilities, working with MDX gives you a range of additional component types in a tutorial.

#### Playground Link

You can have an embedded GraphQL playground component in an article, which can also open up in a separate browser window.

![Playground Link code](https://prisma-tutorial-images.ams3.cdn.digitaloceanspaces.com/Playground.png)

#### Warning/Info

You can include a note to either warn people about a specific issue or to add some additional reference on a topic. We especially recommend that the content in the info component be an extension of what is covered in the text, but not necessarily content that the article depends on.

![warning info code](https://prisma-tutorial-images.ams3.cdn.digitaloceanspaces.com/Warning-info.png)

#### Step

The steps component allows you to highlight the exact places where the reader should take an action. Highlighting exactly where an action needs to be taken ensures that individuals who are potentially re-reading an article or trying to pull a very specific piece of information from the piece can easily get all of the steps.

![step](https://prisma-tutorial-images.ams3.digitaloceanspaces.com/Step%20code.png)

#### Collapse Text

The collapsable text tutorial component allows you to add additional text to a tutorial that can then be hidden or opened. This component is best used throughout to add troubleshooting guidance when you know the reader may run into issues. Try to make the title of the component as descriptive as possible so that the reader can spot if opening the component will help them with their issue.

![collapsable text](https://prisma-tutorial-images.ams3.cdn.digitaloceanspaces.com/Collapsable%20Component.png)
