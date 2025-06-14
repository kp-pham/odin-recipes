# odin-recipes

This repository contains HTML documents for a recipe website. The website contains a homepage from which the user can access
pages for the recipes of traditional British dishes such as Bangers and Mash, Fish and Chips, and the English breakfast. The
recipe pages contain a brief description of the dish, the ingredients needed for the recipe, and steps of the recipe.

## Page Structure

The website adheres to HTML5, the latest version of HTML and the current standard. Pages of the website have the `<!DOCTYPE html>` declaration to ensure that the latest version of HTML is used and the `lang` attribute of the `<html>` tag specifies the language used in the HTML document as English for screen readers to properly process the text of the document. The `<head>` element is the parent of the `<meta>` element with the `charset` attribute to specify UTF-8 as the character encoding used for the document and the `<title>` element which encloses the title of the page.

## Homepage

The homepage contains the title of the project in an `<h1>` element and the relative links to the other pages of the website enclosed in `<a>` elements which are children of `<li>` elements which in turn are also children of `<ul>` elements for the links to be formatted in an unordered list instead of having the links on the same line. The `rel=noopener noreferrer` attribute is not specified for the `<a>` elements because relative links only allow for the user to access pages within the website and security vulnerabilities are a consideration when there are external links to other websites which open a new tab in other windows.

## Recipe Pages

The pages for the recipe contain the title of the recipe enclosed in an `<h1>` element and the subheadings for the sections containing the description of the recipe, the list of ingredients, and the steps of the recipe are enclosed in `<h2>` elements to distinguish between heading and subheadings. The image of the dish beneath the title of the recipe is embedded within the `<img>` element which contains the relative link to the image stored in a directory containing images on the website in the `src` attribute, the alternative text for when the image could not be loaded and for visually impaired users to understand the content of the image in the `alt` attribute, and the dimensions of the image in the `width` and `height` attributes. The description of the recipe is enclosed within a `<p>` element because the description is a block of text which is organized as a paragraph. The list of ingredients is enclosed within an `<ul>` element because the ingredients are listed in an arbitrary order. The steps of the recipe are enclosed within an `<ol>` element because the steps of the recipe need to be followed in order and are listed in numerical order.

In the description of the recipe for bangers and mash, the `<em>` element is used to place emphasis on the term <em>banger</em> because the term is a foreign phrase used as slang to refer to sausages and has historical signifance to the origins of the dish. Because the emphasis placed on the phrase changes the meaning of the word, the `<em>` element indicates for screen readers to place verbal emphasis on the term for visually impaired users to understand the term not in the colloquial  context of the word but instead in the context from which the slang originates.

In the description of the recipe for the English breakfast, the `<strong>` element is used to indicate the importance of the phrase <strong>full breakfast</strong> because the alternative name for the English breakfast provides historical context for the origins of the dish. Because the indication of importance does not change the meaning of the phrase, the use of the `<strong>` element indicates for screen readers to enunciate the tone of delivery for visually impaired users to understand the significance of the phrase towards their understanding of the background of the dish.