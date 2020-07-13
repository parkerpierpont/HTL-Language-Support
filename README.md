# htl-language-support README

Extremely basic comment, and snippet support for AEM HTML Template Language.

## Features

**Conveniences**:

- Properly formats comments

- Automatically closes variable brackets

- Automatically closes other brackets as well

**Snippets**:

- 'component' -> Creates a component.

- 'template' -> Creates a component markup and references a template.

- 'sly' -> Creates a sly tag with a data-sly attribute.

- 'sly.resource' -> Creates a sly element with a data-sly-resource attribute.

- 'sly.test' -> Creates a sly element with a data-sly-test attribute.

- 'sly.test.var' -> Creates a sly element with an identified data-sly-test attribute.

- 'sly.list' -> Creates a sly element with a data-sly-repeat and a dynamic tag element (It's recommended to use data-sly-repeat instead of list)

- 'sly.repeat' -> Creates a sly element with a data-sly-repeat and a dynamic tag element.

- 'sly.clientlib' -> Creates a sly element with a data-sly-use clientlib definition.

- 'sly.call' -> Creates a sly element with a data-sly-call attribute.

- 'sly.call.param' -> Creates a sly element with a data-sly-call attribute and a parameter.

- 'sly.include' -> Creates a sly element with a data-sly-include attribute.

- 'data-sly-include' -> Creates a data sly include attribute.

- 'data-sly-call' -> Creates a data sly call attribute.

- 'data-sly-element' -> Creates a data sly element attribute.

- 'data-sly-attribute' -> Creates a data-sly-attribute attribute.

- 'data-sly-attribute-map' -> Creates a data-sly-attribute-map attribute.

- 'data-sly-use' -> Creates a data sly use attribute.

- 'data-sly-use.var' -> Creates a data sly use attribute with var name.

- 'data-sly-use.var.param' -> Creates a sly data use with a var name and one parameter.

- 'sly.i18n' -> Creates an I18n call.

- 'sly.i18n.hint' -> Creates an I18n call with a hint.

- 'sly.i18n.locale' -> Creates an I18n call with a locale attribute.

- 'sly.i18n.source' -> Creates an I18n call with a source attribute.

- 'sly.i18n.2param' -> Creates an I18n call with two dynamic parameters.

- 'sly.i18n.1param' -> Creates an I18n call with one dynamic parameter.

- 'sly.i18n.full' -> Creates an I18n full tag.

- 'sly.join' -> Creates a sly join.

- 'sly.context' -> Creates a sly context.

- 'sly.inStr' -> Creates an 'in' relational string operator.

- 'sly.inArray' -> Creates an 'in' relational array operator.

## Notes

You will most likely need to heavy-hand the use of this plugin manually, since it doesn't take priority over HTML files.
