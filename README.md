# hxSketchLibrary

This repo contains various library files for use within `sketchapp` to design with the [Helix Design System ](github.com/rackerlabs/design-system) created by the Rackspace Experience Design. 

This repo is made possible because of the excellent opensource tool [Kactus](https://github.com/kactus-io/kactus) which serves as an interface between Sketch and Github.

## Repo Contents

- `helix-ui-components.sketch` - Library of all ui-components for [Helix-ui](https://rackerlabs.github.io/helix-ui/)
- `helix-redline-specs.sketch` - Library to create the redline documentation available for viewing on [Helix documentation site](http://helix.rax.io)
- `helix-user-flows.sketch` (coming soon) - Library to map out user flows and site hierarchies in sketch

## Setting up the library

Setting up the library for use can be performed either locally or via the RED shared drive(recommended).

### Setting up via Shared Drive (Recommended) 

Note: This is only for Rackspace employees

1. Request access in #helix to the RED GoogleDrive
2. Open Sketch’s Preferences (Command-Comma), and navigate to the Libraries tab.
3. Click the ‘Add Library…’ button and path to this file and click "open"
4. Profit. You can now insert Helix symbols from the insert dropdown.

### Setting up via Local 

The process is exactly the same for this except you first need to clone this repo and instead configure the library to read the local cloned assets. 

Note: You will need to manually perform a `git pull` to receive updates to the library files rather than receiving them automagically from the shared drive setup method.

### Contributing

The Helix team will maintain this repo and update / add symbols as the design language evolves. That being said we can't catch everything. If you find something amiss you have a few methods of recourse

1. Ping us in the [Slack channel](https://rackspace.slack.com/messages/#helix) (Note: This is only for Rackspace employees)
2. Open an [issue](https://github.com/technabors/hxSketchLibrary/issues/new)
3. Clone and configure the using [Kactus.io](http://www.kactus.io), create a branch, perform your changes, and open a pull.

Cheers