# optimize-an-Existing-Website
https://lamhaouas.github.io/optimize-an-existing-website/

# Optimization report 

## Screenshots of Lighthouse scores before and after the optimization

### Before optimization

![before optimization](/img/Lighthouse-before.jpg)

### After optimization

![after optimization](/img/Lighthouse-after.jpg)

## Report of SEO work

Starting with a quick audit of lighthouse report to determine if the website follows SEO convention, I was able to extract the followings technical settings and accessibility issues:

### Meta tags:

* Add the title tag for the home page that reflect the brand.
* Remove the keyword meta tags.
* Improve the description using relative keywords.

### Multiple H1 tags:

* Multiple h1 titles on the same page and absence of heirarchy.

### Images:

* The images must be resized for a better navigation and add the alt attributes.

### technical issues:

* CSS and Js files: the covrage tool on lighthouse shows that we can save alot of space by deleting unused CSS and Js.
* Backlinks: all the backlinks are broken and must be removed.
* Google Analytics : Absence of the tracking code.

### Semantic tags and Alt/ARIA attributes:

The HTML5 code has a lot of divs and does not have a structure using the propre semantic tags, also absence of ARIA attributes.

### Contrast:

The contrast does not comply with WCAG 2.1 requierments (contrast ratio of at least 4.5:1).

