---
title: How to implement Coding Guidelines
date: 2020-07-22T06:18:21.796Z
summary: Coding Guidelines are a crucial part of making a codebase with multiple
  contributors consistent, clean, readable and less error prone. But how do you
  make them easy to follow and how do you make sure they are met from every
  single person?
---
Coding Guidelines are a crucial part of making a codebase with multiple contributors consistent, clean, readable and less error prone. But how do you make them easy to follow and how do you make sure they are met from every single person?

The answer to that are text editor / IDE settings, formatters and linters. There are different tools for that, including the most common:

* EditorConfig (Code Editor / IDE Settings)
* Prettier (Formatter)
* ESLint (JavaScript Linter)
* Stylelint (CSS Linter)

## EditorConfig

EditorConfig defines a few basic settings for files in the code editor / IDE. They are applied when you create or save a file.

Sample .editorconfig file:

```
root = true
 
[*.{js,scss}]
charset = utf-8
indent_style = space
indent_size = 2
end_of_line = lf
trim_trailing_whitespace = true
insert_final_newline = true
```

In some code editors / IDEs you need to install a plugin to activate the settings. See <https://editorconfig.org/#download> for details.

## Prettier

Prettier is an opinionated code formatter for HTML, CSS, JavaScript, Markdown and more. It can be set up to format on save, which is very useful.

Note that it is opinionated, so you can't adjust every little detail of the formatter, but the settings that are available are enough for most modern projects. See <https://prettier.io/docs/en/options.html> for details.

## ESLint

ESLint is an unopinionated JavaScript linter, this means that all rules can be adjusted. It checks JavaScript for code errors, but also has the option to check stylistic issues. It is a good option for large or legacy projects where every rule needs to be adjustable.

During setup there are a few questions asked:

![ESLint Setup Questions](/static/img/eslint-questions.png)

See <https://eslint.org/> for details.

## Stylelint

Stylelint is an unopinionated CSS linter. Similar to ESLint all rules can be adjusted and it checks CSS for code errors, but also has the option for stylistic issues. The difference to ESLint is that it can't autofix errors.

See <https://stylelint.io/> for details.

### More on this article coming soon.