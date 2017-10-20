# Best Practices and Style Guides for Labs

## HTML
* Unless otherwise specified, we use [@mdo's style guide](http://codeguide.co/#html) for HTML.

## SCSS
* Unless otherwise specified here, use the [airbnb](https://github.com/airbnb/css) SCSS styleguide.
* We don't use the [Block-Element-Modifier](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/) naming convention because we believe that SCSS renders it unnecessary, and that, on small, closely-coordinated teams, we can expect a higher standard of reusability.
* We **do** use [Object Oriented CSS](https://github.com/stubbornella/oocss/wiki)
* Default to [osf style](https://centerforopenscience.github.io/osf-style/) whenever there's uncertainty about whether or not something will fit in, look good, or be consistent.

## Javascript

## Ember
* We use a pod-based component structure, where every entry in the `app/components` folder is a subdirectory `component-name` with files `template.hbs` and `component.js` inside.
