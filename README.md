# 🚀 DSC-Taft-2020 #

Main website for DSC Taft

## Figma ##

Wireframe: https://www.figma.com/files/project/9832364/Main-Website

## Initializing Development Environment ##

1. Run **npm install** to install dev-dependencies.
2. In the console, make sure to run **npm run watch:sass**.

## CSS Architecture ##

1. In developing the site, we will be using **SASS** for styling and the BEM **(Block Element Modifier)** architecture for naming our classes.
2. You may look at the initial code to get a glimpse on how the BEM architecture works.
3. Likewise, we will be using the **7-1** CSS file system architecture.

## 7-1 File System ##

All the files inside the folders below will be imported to main.scss as such the main.scss will be the reference point/ relative path. This should be noted when linking paths in the styles.

1. **abstracts** - where functions, mixins, and variables will be stored
2. **base** - where we will make custom animations (_animation.scss), make a universal reset and/ or initializations (_base.scss), and add custom typographies.
3. **components** - style components like buttons, cards, and other components that will be used more than once. One component is equivalent to one file (e.g button and cards = _button.scss, _card.scss).
4. **layouts** - navigation, footer, header (separated)
5. **pages** - Mostly deals with styling sections per page.
6. **themes** - adding custom themes to the website when there are special events (may not be implemented yet during this phase)
7. **vendors** - Third-party libraries like Bootstrap and/ or JQuery. (may not be implemented)