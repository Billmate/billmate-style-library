# Billmate style library

A frontend styling library for using [Billmate styles](https://www.figma.com/file/mJStDGNw8r1NZWD3fAAeuS/Billmate-Design-Library?node-id=0%3A1). It is built upon the CSS framework
called [Bulma](https://bulma.io/) and contains the icon library [Font Awesome](https://fontawesome.com/).

So basically any component or styling from [Bulma documentation](https://bulma.io/documentation/) can be used 
but with a Billmate look and feel. 

## Installation

To being able to work and test this repo the following steps needs to be done.

    npm install

For development just use the command

    npm start (same as npm run css:watch)

## Commands

### CSS

The following commands are available for CSS and SASS.

#### Building

    npm run css:build

Builds the CSS files for Production.

#### Watching

    npm run css:watch

Builds the CSS and watches for changes.

#### Linting

    npm run css:lint

Lints the CSS.

#### Resources

    npm run css:resources

Moves and adds the correct resources for CSS/SASS to use.

### Styleguide

The following commands are available for Styleguide. When being compiled it ends up in the
folder called **docs**. To access it for local development the url is:

    locahost:3000

#### Building

    npm run styleguide:build

Builds the Styleguide files for Production.

#### Watching

    npm run styleguide:watch

Builds the Styleguide and watches for changes.