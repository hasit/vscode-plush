# vscode-plush

Plush syntax support for VSCode

## Snippets and Bindings

| Snippet | Prefix | Output |
| ------- |:------:| -----: |
| expression tag | ple | <% expression %> |
| print tag | plp | <%= expression %> |
| if block | plif | <%= if (condition) { %> \<!-- some html here --> <% } %> |
| if else block | plie | <%= if (condition) { %> \<!-- some html here --> <% } else { %> \<!-- some other html here --> <% } %> |
| map | plm | <% let name = {key: value} %> |
| array | pla | <% let name = [values] %> |
| for | plf | <%= for (key, value) in expression { %><%= key %> <%= value %><% } %> |

## Release Notes

### 0.1.0

Initial release. Support for all basic Plush tags.

## References

[Plush](https://github.com/gobuffalo/plush)