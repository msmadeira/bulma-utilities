# Bulma Utilities

Bulma Utilities is a <a target='_blank' href='https://github.com/jgthms/bulma'>Bulma Framework</a> extension that add tons of utility classes.

## Installation

### NPM
```sh
npm install bulma-utilities
```
If you have custom Bulma variables,  you can import bulma-utilities.sass after your variables file and it will use your custom $sizes and $colors lists.

## Documentation

### Utility Classes

#### Chart legend:<br> {x} - is a number that represents the position in $sizes (Bulma's derived variable) array (Example: has-margin-3)<br>{d} - is a letter that represents the direction, b stands for bottom, l for left, r for right and t for top (b, l, r, t, bl, br, bt, lr, lt, rt, blr, blt, brt, lrt) (Example: has-margin-b-3)<br>{c} - is the color used in the class (Example: has-bg-primary)

| Class                                                 | Description                                            |
|-------------------------------------------------------|--------------------------------------------------------|
| has-margin-{x}                                        | Adds margin to element                                 |
| has-margin-{d}-{x}                                    | Adds margin to element in respective direction         |
| has-padding-{x}                                       | Adds padding to element                                |
| has-padding-{d}-{x}                                   | Adds padding to element in respective direction        |
| is-paddingless-{d}                                    | Removes padding in respective direction                |
| is-marginless-{d}                                     | Removes margin in respective direction                 |
| has-bg-{c}                                            | Changes background color to respective color           |
| is-clickable                                          | Changes cursor to pointer                              |
| is-zoom-in                                            | Changes cursor to zoom-in                              |
| is-zoom-out                                           | Changes cursor to zoom-out                             |
| is-cell                                               | Changes cursor to cell                                 |
| is-not-allowed                                        | Changes cursor to not-allowed                          |
| can-move                                              | Changes cursor to move                                 |
| is-waiting                                            | Changes cursor to wait                                 |
| has-margin-x-auto                                     | Adds 'margin: 0 auto' to element                       |
| hide-overflow                                         | Hides overflow                                         |
| hide-overflow-x                                       | Hides horizontal overflow                              |
| hide-overflow-y                                       | Hides vertical overflow                                |
| has-position-absolute                                 | Adds position absolute to element                      |
| has-position-relative                                 | Adds position relative to element                      |
| has-position-fixed                                    | Adds position fixed to element                         |
| has-flex-center-items                                 | Adds display flex and align-items center               |
| has-flex-start-items                                  | Adds display flex and align-items flex-start           |
| has-flex-end-items                                    | Adds display flex and align-items flex-end             |
| has-border-dashed                                     | Adds 'dashed' style to border                          |
| has-border-dotted                                     | Adds 'dotted' style to border                          |
| has-border-double                                     | Adds 'double' style to border                          |
| has-border-hidden                                     | Adds 'hidden' style to border                          |
| has-border-solid                                      | Adds 'solid' style to border                           |
| is-circle                                             | Makes element circular adding border-radius: 60px      |
| unbreakable-text                                      | Makes text don't break lines                           |
| has-text-underlined                                   | Adds 'text-decoration: underline' to element           |

## Copyright and license

Code copyright 2019 Matheus Madeira. Code released under [the MIT license](https://github.com/msmadeira/bulma-utilities/blob/master/LICENSE).
