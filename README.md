# Best Practices and Style Guides for Labs

## HTML
* As per [https://cosdev.readthedocs.io](COS dev docs), we use 4-space soft tabs for HTML.
* Unless otherwise specified, we use [@mdo's style guide](http://codeguide.co/#html) for HTML.

## SCSS
* As per [https://cosdev.readthedocs.io](COS dev docs), we use 4-space soft tabs for (S)CSS.
* Unless otherwise specified here, use the [airbnb](https://github.com/airbnb/css) SCSS styleguide.
* We don't use the [Block-Element-Modifier](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/) naming convention because we believe that SCSS renders it unnecessary, and that, on small, closely-coordinated teams, we can expect a higher standard of reusability.
* We **do** use [Object Oriented CSS](https://github.com/stubbornella/oocss/wiki)
* Default to [osf style](https://centerforopenscience.github.io/osf-style/) whenever there's uncertainty about whether or not something will fit in, look good, or be consistent.

## Javascript

## Ember
* We use a pod-based component structure, where every entry in the `app/components` folder is a subdirectory `component-name` with files `template.hbs` and `component.js` inside.
* Every component should have a comment at the beginning of the template with the component's name.
