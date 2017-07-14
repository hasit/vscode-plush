# vscode-plush

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