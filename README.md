<h1 align="center">
  MiConcierge JavaScript Standard
</h1>

This guide it's primarly based on [Standard JS] (https://github.com/standard/standard/blob/master/README.md)

# StandardJS Rules

- **2 spaces** – for indentation
- **Single quotes for strings** – except to avoid escaping
- **No unused variables** – this one catches *tons* of bugs!
- **No semicolons** – [It's][1] [fine.][2] [Really!][3]
  - [More details][4]
- **Space after keywords** `if (condition) { ... }`
- **Space after function name** `function name (arg) { ... }`
- Always use `===` instead of `==` – but `obj == null` is allowed to check `null || undefined`.
- Always handle the node.js `err` function parameter
- Declare browser globals with `/* global */` comment at top of file
  - Prevents accidental use of vaguely-named browser globals like `open`, `length`,
    `event`, and `name`.
  - Example: `/* global alert, prompt */`
  - Exceptions are: `window`, `document`, and `navigator`


# Extra

## React Guide
  - TODO

## Issues
  - TODO
  - More consise guide https://guides.github.com/features/issues/

## Pull Request
  - TODO
