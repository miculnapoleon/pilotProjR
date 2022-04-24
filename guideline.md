# Resources
- html 
- css
- JS
- NextJS
- React 
- Cypress
## Structure
- Homepage with Logo and Expandable Menu (with clickable options) and Cards with data
- The Homepage Cards: have a title, description , a picture and a name
- Expandable Menu has options with links to pages: My Recipes and Saved Items
- My Recipes page is a listing with an Add btn which opens a modal and a listing table with pagination and filters
- Saved Items - is a listing table with pagination and filters
## Components
- Buttons
- Icons
- Cards container
- Modal
- Dropdown
- Input fields
- Switch/toggle


### Learning notes
- components are functions that return a JSX element

    `return (<JSXElement/>)` 

    `return (<JSXElement>{logic}</JSXElement>)`

- all components have `props` as param
- `props` can be destructured

`const props ={name:'John'}  ->  { name }`

- all components must be exported
    - there are 2 ways of exporting a component

    `export default Component`
    `import Component from path`
    and
    `export Component`
    `import {Component} from path`


- Naming conventions:  
    1. Components names must be capital case
    