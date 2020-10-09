# BEM-Design-System
This repository is a collection of vanilla HTML/CSS components written using the BEM methodology for Hactoberfest.

## How to participate

### Initial Setup
Fork this repository

### First Pull Request
1) Write a comment and `<section>` tag in the `index.html` file:
```html
<!-- 
  Username 
  Description of component
  Available modifiers
-->
<section class="my-block">
   ...
</section>
```

2) Create a pull request for your HTML!

### Second Pull Request
1) Write your CSS block ruleset in `style.css`:
```css
/* ====================
   My Component
======================*/

/* Block */
.my-block{
  ...
}
```

2) Create a pull request for your CSS!

### Third Pull Request
1) Write your CSS __elements in `style.css`:
```css
/* Elements */
.my-block__elem1{
  ...
}

.my-block__elem2{
  ...
}

...
```

2) Create a pull request for your CSS!

### Fourth and Fifth Pull Requests
1) Write your CSS --modifiers in `style.css`:
```css
/* Modifier one */
.my-block--mod1{
  ...
}

.my-block--mod1 .my-block__elem1{
  ...
}

...
```

2) Create a pull request for your CSS!
3) Repeat the Process for each Modifier.

