# SCSS-files-structure

# Abstracts


## Functions 
It's a file for SCSS/SASS functions.
Link: https://sass-lang.com/documentation/at-rules/function 

## Mixins 
It's a file for SCSS/SASS mixins. You can use mixins for media queries or when you need to write the same code over and over again. For instance, in the file, you can see @mixin absCenter. Instead of writing that four lines inside of it on your own, you can just write @include absCenter; in your other scss files.
Link: https://sass-lang.com/documentation/at-rules/mixin

## Variables
It's a file for SCSS/SASS variables. 
Link: https://sass-lang.com/documentation/variables

# Base

## Animations
It's a file for CSS animations.

## Base 
It's a file for base styles like for HTML tag, body tag, * or ::selection. Styles in it are for the whole website, not one page of it.

## Typography 
It's a file for typography like p tag, headings and etc.

## Utilities 
It's a file for utilities. Utilities is a supporting class that you can use in multiple blocks on the website. 

# Layout 
It's a folder for files with styles of parts of the website which are on every page. Such as navigation, header, footer and etc. You can add as many files there as you want, but each file should be for one part of the website.

# Components
It's a folder for files with styles of components. For instance, if you do English for kids, the component can be a card with a word, Train/Play mode switch button, statistics table, "Start game" button and etc. For each component, you should create a separate file. 

# Pages
It's a folder for files with styles of pages of the website. Such as home page, contacts page, about us page, products page and etc.

# Style.scss
This is a file where you import all of the SCSS/SASS files. Don't write any styles there! This is a file that you import in your main js file, for example, index.js.
