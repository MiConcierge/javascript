<h1 align="center">
  MiConcierge JavaScript Standard
</h1>

Esta guia esta basada principalmente en [Standard JS] (https://github.com/standard/standard/blob/master/README.md)

# StandardJS Reglas

- **2 espacios** como sangría.
- **Usar comillas simples en cadenas de texto** con la excepción de escapado de texto
- **No dejar variables sin usar** – esta captura *toneladas* de bugs!
- **Sin punto y coma** – [Está][1] [bien.][2] [¡En serio!][3]
- **Nunca empezar una línea con `(`, `[`, o `` ` ``**
  - Este es el **único** problema al evitar punto y coma – *automáticamente verificado para ti!*
  - [Más detalles][4]
- **Espacio después de las palabras claves** `if (condition) { ... }`
- **Espacio después del nombre de función** `function name (arg) { ... }`
- Usar siempre  `===` en vez de `==` – pero `obj == null` está permitido para verificar `null || undefined`.
- Gestionar siempre el parámetro de función `err` de node.js
- Usar siempre el prefijo `window` en los globales del navegador – A excepción de `document` y `navigator` esto está bien
  - Previene el uso accidental de mal-llamados globales del navegador como `open`, `length`,
    `event`, y `name`.

# Extra

## Guia de React
  - TODO

## Issues
  - TODO
  - Guia mas concisa https://guides.github.com/features/issues/

## Pull Request
  - TODO
