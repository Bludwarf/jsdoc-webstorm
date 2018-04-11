Status of supported JSDoc tags on Webstorm by versions.

| Tag                                               | JSDoc Example             | Webstorm   | Updated    |
|---------------------------------------------------|---------------------------|------------|------------|
| [@type](http://usejsdoc.org/tags-type.html)       | `{Array.<MyClass>}` | 🔴 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `{MyClass[]}` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `{Object.<string, number>}` | 🔴 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `{{a: number, b: string, c}} myObj` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | ("or" after previous) | 🔴 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `{?number}` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `{!number}` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `@param {...number} num` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `@param {number} [foo]` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `@param {number=} foo` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `@param {number} [foo=1]` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | `@callback myCallback` | ✅ 2017.3.4 | 2018-04-11 |
| [@type](http://usejsdoc.org/tags-type.html)       | @typedef | 🔴 2017.3.4 | 2018-04-11 |
| [@typedef](http://usejsdoc.org/tags-typedef.html) | Using the @typedef tag    | ✅ 2017.3.4 | 2018-04-11 |

# References
- JSDoc : http://usejsdoc.org/
- https://github.com/google/closure-compiler/wiki/Annotating-JavaScript-for-the-Closure-Compiler#type-expressions
- Site used to generate Markdown table : http://www.tablesgenerator.com/markdown_tables
