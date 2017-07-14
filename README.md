# vscode-plush

[![plush version](https://vsmarketplacebadge.apphb.com/version-short/rubbersheep.vscode-plush.svg)](https://marketplace.visualstudio.com/items?itemName=rubbersheep.vscode-plush) [![plush installs](https://vsmarketplacebadge.apphb.com/installs/rubbersheep.vscode-plush.svg)](https://marketplace.visualstudio.com/items?itemName=rubbersheep.vscode-plush) [![plush ratings](https://vsmarketplacebadge.apphb.com/rating-short/rubbersheep.vscode-plush.svg)](https://marketplace.visualstudio.com/items?itemName=rubbersheep.vscode-plush#review-details)

Plush syntax support for VSCode. Currently supports snippets. Eventually, will contain support for syntax highlighting and complete autoformatting of Plush tags in HTML files.

## Snippets and Bindings

| Snippet | Prefix | Output |
| ------- |:------:| -----: |
| expression tag | ple | <% expression %> |
| print tag | plp | <%= expression %> |
| if block | plif | <%= if (condition) { %> ... <% } %> |
| if else block | plie | <%= if (condition) { %> ... <% } else { %> ... <% } %> |
| map | plm | <% let name = {key: value} %> |
| array | pla | <% let name = [values] %> |
| for | plf | <%= for (key, value) in expression { %><%= key %> <%= value %><% } %> |

## References

[Plush](https://github.com/gobuffalo/plush)