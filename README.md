# hxSketchLibrary

This repo contains various libraries for use within [Sketch](https://www.sketchapp.com/) to design mockups with using the [Helix Design System ](github.com/rackerlabs/design-system), created by the Rackspace Experience Design. 

There are no `.sketch` files stored in this repository. Sketch files are essentially just a set of JSON files, and that is how they are stored in this repo.

We use [Kactus](https://github.com/kactus-io/kactus), which serves as an interface between Sketch and Github.  Kactus provides the most common GIT actions and handles the conversion of Sketch files into, and out of, JSON, making storage on GitHub easier.

## Repo Contents

- `helix-ui-components.sketch` - Robust ui-component symbols for creating mockups using the Helix design language.
- `helix-redline-specs.sketch` - Symbols for use in creating redline documentation for any Helix design. Anytime you're creating something that doesn't exist in Helix yet, you need redline specs.
- `helix-thumbnails.sketch` - Thumbnail symbols for the most common UI page types.  These can be used to describe high-level workflows, without getting mired in the specifics.

## Setting up the library

Setting up the library for use can be performed either from the RED shared drive or locally.

### Set up from the RED shared drive for Rackspace employees (Recommended) 

1. Request access in #helix to the RED GoogleDrive
2. Open Sketch’s Preferences (Command-Comma), and navigate to the Libraries tab.
3. Click the ‘Add Library…’ button and path to this file and click "open"
4. Profit. You can now insert Helix symbols from the insert dropdown.

### Set up Locally

#### A. Get Kactus and generate the Sketch files
1. [Download Kactus](https://kactus.io/) and launch the application.
2. Sign into GitHub within the Kactus UI.
3. Configure your GIT user in Kactus.
4. Clone this repository
5. Select the library file you want and click "Regenerate Sketch File"

#### B. Add the library to Sketch
1. Open Sketch’s Preferences (`Command+Comma`), and navigate to the Libraries tab.
2. Click the ‘Add Library…’ button, navigate to this file and click "open"
3. Profit. You can now add Helix symbols to your mockup using the insert menu in Sketch.

#### C. Get the library updates
1. Perform a `git pull` on the `master` branch to receive updates.
2. Click the "Regenerate Sketch File" button.

### Contributing

The Helix team will maintain this repo and update / add symbols as the design language evolves. That being said we can't catch everything. If you find something amiss you have a few methods of recourse

1. Ping us in the [Slack channel](https://rackspace.slack.com/messages/#helix) (Note: This is only for Rackspace employees)
2. Open an [issue](https://github.com/technabors/hxSketchLibrary/issues/new)
3. Clone and configure the using [Kactus.io](http://www.kactus.io), create a branch, perform your changes, and open a pull.

Cheers