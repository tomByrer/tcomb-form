v0.3.0

- complete code refactoring, fix #8

**BREAKING**

- `input` option is now `factory`
- `emptyOption` option is now `nullOption`
- no more "Choose your ..." option in selects
- no more need for `multiple` option, use `t.form.select` with lists of enums instead
- `i17n` option is now called `transformer`
- horizontal forms must be handled by the style
- custom input now must be functions with signature: `(opts, ctx) -> React Class`
- optgroup has now a `label` property instead of `group`

v0.2.3

- Always add control-label class to labels. Required for example for displaying validation states correctly.

v0.2.2

- upgrade to tcomb-validation v0.2.1
- better lists management
- `createForm` and `createList` apis are deprecated and they will be removed in the next release. Use `create` instead.

v0.2.1

- `createForm` doesn't handle correctly a `maybe(Num)` field, fix #20
- better documentation
- add a default value for the `name` attribute to all inputs, fix #17

v0.2.0

- update to React v0.12.1

v0.1.8

- repo refactoring to simplify setup (gulp)

v0.1.7

- `opts.message` can be a function

v0.1.6

- `createForm` and `createList` now return a `fieldset` tag as a top level element, fix #2 (partially)
- added `opts.i18n` (i18n support) fix #4
- added `hasError` and `message` options
- added `defaultI17n`, fix #14
- added `opts.name` to all inputs

v0.1.5

- upgrade to tcomb-validation v0.1.3

v0.1.4

- allow `hidden` type for the textbox component, fix #13
- add custom options support (allows grouped options too), fix #12
- added `create` API, fix #9

v0.1.3

- Example #7 `invalid Array.prototype.sort argument` fix #7

v0.1.2

- fix i17n related bug

v0.1.1

- Add-ons
- horizontal forms
- disabled inputs
- readOnly inputs
- control sizing
- column sizing
- i17n opt for forms and lists
- context opt for forms and lists

v0.1.0

initial release
