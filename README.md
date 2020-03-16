# Claysheet

My personal (S)CSS sheet(s), an easy align-able wheel for web projects. Despite how much I love writing SCSS, I like re-using  SCSS even better.

## Structure

### Classnames

Claysheet follows the BEM pattern.

Using ``config.scss`` you have the option to add or edit a prefix to (Currently) most of the blocks/elements, should you want to avoid conflicting classnames with existing styling.

### Folders & Files

Claysheet are structured based on the SASS 7-1 pattern, where one file binds & rules them all. In Claysheet's case, ``main.scss`` imports them all.

Each subfolder contains a file named ``_all.scss`` which is used by a parent stylesheet to @import all the child stylesheets.

### Variables & Mixins

Global variables are defined in the **abstracts** folder; these are used by the elements themselves rather than being imported globally, should you want to import single SCSS files rather than "main".

### Directory tree

- main.scss
  - abstracts
  - core
  - layout
  - components
    - form
    - standalone
  - modifiers

## Default settings

(WIP)

## Currently working on

- Implementing old blocks & elements one by one.
- Refactoring form elements
- Adding missing elements, i.e. navigation
- Implementing themes
