  ## Motivation
I wanted to be able to download an already cleaned up `create-next-app` structure
## Changes To Original Package
### Installed SASS
- ran `npm i sass`
- added some basic global styles in the `/styles` directory
  - `_variables.scss` contains some basic variables and mixins. I mainly use the mixins for media query breakpoints.
  - `globals.scss` contains a css reset based on the reset file found [here](https://meyerweb.com/eric/tools/css/reset/)
  - `Home.module.scss` is the styling for the `/pages/index.jsx`
### Added Basic Components
- `/components/container`
  - a container element called with `<Container>`; It is a wrapper for page content currently
- `/components/header`
  - displays a header on the top of the page. It contains code for all page naviagation. 
- `/components/heading`
  - Returns either an `<h1>` or an `<h2>` element depending on the type prop set `<Heading type={"h1"}>Heading1</Heading>`
- `/components/modal`
  - Truthfully, I only included this package because it is used in the mobile nav menu. It can be used for any other modal view though.
- `/components/tables`
  - Just an example of a standard table component that can return various tables
- `/components/text`
  - A component that shows various forms of text, such as `<p>`, or `<figcaption>`
