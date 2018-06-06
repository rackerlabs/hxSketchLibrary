# hxSketchLibrary

This repo contains libraries for use within [Sketch](https://www.sketchapp.com/) to design mockups using components in the [Helix Design System ](https://github.com/rackerlabs/helix-ui). 

There are no `.sketch` files in this repository. Sketch files are essentially just a set of JSON files, and that is how they are stored in this repo.

We use [Kactus](https://github.com/kactus-io/kactus), which serves as an interface between Sketch and Github.  Kactus provides the most common GIT actions and handles the conversion of Sketch files into, and out of, JSON, making storage on GitHub easier.

## Repo Contents

- **helix-ui-components.sketch** - Robust ui-component symbols for creating mockups in Helix.
- **helix-redline-specs.sketch** - Symbols for use in creating redline documentation for any Helix design.
- **helix-thumbnails.sketch** - Handy thumbnail symbols for the most common page types in Helix.

## Setting up the library

### A. Get Kactus and generate the Sketch files
1. [Download Kactus](https://kactus.io/) and launch the application.
2. Sign into GitHub within the Kactus UI.
3. Configure your GIT user in Kactus.
4. Clone this repository.
5. Select the library file you want and click "Regenerate Sketch File".

### B. Add the library to Sketch
1. Open Sketch’s Preferences (`Command+Comma`), and navigate to the Libraries tab.
2. Click the "Add Library" button, navigate to this file, and click "open".
3. Profit. You can now add Helix symbols to your mockup using the insert menu in Sketch.

### C. Get the library updates
1. Perform a `git pull` on the `master` branch to receive updates.
2. Click the "Regenerate Sketch File" button.

## Contributing

The Helix team will maintain this repo as the design language evolves. That being said, if you find something is amiss, you have a few methods of recourse:

1. [Open an issue](https://github.com/rackerlabs/hxSketchLibrary/issues/new)
2. Use [Kactus.io](http://www.kactus.io) to create a branch, make changes, commit changes, publish your branch, and open a pull request.

Cheers