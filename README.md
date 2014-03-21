cf-icons
========

Custom icon font for Capital Framework.

This component can be used by itself, but it was made for Capital Framework, a new front end framework developed at the [Consumer Financial Protection Bureau](http://cfpb.github.io/).

If you would like to take advantage of more components or if you're new to Capital Framework, we encourage you to [start here](/cfpb/capital-framework).

## Contributing

We welcome your feedback and contributions.

- [Find out about contributing](/cfpb/cf-icons/blob/master/CONTRIBUTING.md)
- [File a bug](/cfpb/cf-icons/issues/new?body=%23%23%20URL%0D%0D%0D%23%23%20Actual%20Behavior%0D%0D%0D%23%23%20Expected%20Behavior%0D%0D%0D%23%23%20Steps%20to%20Reproduce%0D%0D%0D%23%23%20Screenshot&labels=bug)


## Building the component

### Requirements

- [npm](https://npmjs.org/)
- [grunt-cli](http://gruntjs.com/getting-started)
- That's it! NPM will help you install everything else you need.

### Workflow

1. Clone the repo and `cd` into its root
2. `npm install` – Initializes Grunt in this folder and installs dependencies.
3. `grunt vendor` – Pulls in Bower components.
4. `grunt` – Compiles LESS files and generates the docs and demo pages.


## Using cf-typography independent of Capital Framework

If you're already using [Bower](http://bower.io/), simply add cf-typography as a dependency and integrate it into your build process.

It's not currently in the Bower registry, so you'll have to point to this Git repo's URL.