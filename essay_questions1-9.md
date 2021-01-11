### Styling with Scss

- What is a Scss mixin?
  - It is a tool that can hold css code that you can share through @include with other elements of a page.
- Will Scss render in the browser? Why or why not?
  - No, the browser only reads html and CSS.
- How do you assign a variable in Scss and give me a use case
  - you use the $ symbol. ex = $variable
- What is Variable Scope?
  - it is where a variable is available for use. there are 2 global and local.
- What is Pseudo Selector Nesting?
  - it allows you to add a behaviors to an element such as :hover (using the & to nest it inside an element)
- Why would you use default variables in Scss?
  - it allows you set a value that will always work in case something else doesn't
- What is the purpose of Scss?
  - to make css more gloabal and organized
- What are some differences between Sass and Scss?
  - Sass is the first version of Scss and now the new main syntax is SCSS
- What is the Scss @import Directive used for?
  - this allows you to use a different files content in another
- What is the porpose of the @content Directive in Scss?
  - allows for mixin extensions.

### CSS GRID BASICS

- What is the main purpose of CSS Grid?
  - It's main purpose is to align items and elements in a grid pattern.
- How do you start using CSS Grid with css?

```
    $ display: grid;
```

- What is grid gap used for?
  - it is used to define the gap between the grid elements.
- What are grid columns?
  - they are X-axis elements.
- What is the CSS grid repeat function?
  - repeat allows you to define how many columsn or rows you have through this syntax repeat(4, 1fr);
- What does 1fr represent?
  - 1 Fractional Unit
- What are grid rows?
  - the y-axis elements in a grid
- What is the purpose of Justify Items?
  - to move items horizontally
- What is the purpose of Align Items?
  - to move items vertically
- What does grid-column-start do?
  - defines an elements starting position

### Flexing with Flexbox

- What is the main purpose of Flex Box?
  - to organize a pages elements.
- How do you start using Flex Box with css?

```
    $ display: flex;
```

- Which should you use? Flex Box or CSS Grid?
  - it depends on your goal and design. you can use one or the other or both on a project.
- After declaring display flex, which elements are going to be affected by your flex styles?
  - all of the children elements of that parent div
- What is the purpose of Flex Direction?
  - to define the direction of the elements
- What is the purpose of Justify Content?
  - to move and align items horizontally
- What is the purpose of Flex Grow?
  - defines how fast an elemt grows
- What is the purpose of Flex Shrink?
  - defines how fast an element shrinks
- What is the purpose of Flex Wrap?
  - can allow items to wrap onto a new line if needed
- What is the purpose of Align Items?
  - aligns items vertically
