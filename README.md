# Form helpers – TWIG

This [Twig Bundle](https://github.com/nystudio107/twig-bundle-installer) allows to reuse some helpful Form elements ... as [Twig Macros](https://twig.symfony.com/doc/3.x/tags/macro.html).

**WARNING:** as always when working with forms ... the view isn't the (only) place to verify if a user is allowed to send specific information ... if you disable a form element or make it read only in the view, you also want to prove the data sent does not contain that specific value changed!

## Data structures

As always, a template is using a dedicated data structure to be transferred into a view ... So the following section is on how the data has to be structured for the usage of the provided macros:

### Form

The `form` macro is using a Bootstrap-DIV-based layout and can be adapted easily.

### Form Element
