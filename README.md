# Naming Convention Converter

I was fed up with naming files, so I created this web page to make it easier. The page allows you to convert a string to a different naming convention. The naming conventions supported are:

- camelCase
- PascalCase
- snake_case
- kebab-case
- UPPER_UNDERSCORE
- HungarianNotation

The following programming languages and their recommended naming conventions are also shown on the page:

- JavaScript: camelCase
- Python: snake_case
- Java: camelCase
- C#: PascalCase
- PHP: camelCase / snake_case
- Ruby: snake_case
- Go: camelCase

## Live Demo

You can try out the naming convention converter by visiting the [live demo](https://filename-generator.netlify.app/).

## How to Use

1. Enter the string you want to convert in the "Input String" field.
2. Select the naming convention you want to convert to from the "Naming Convention" drop-down menu.
3. If you want to add a file extension to the output string, select it from the "File Extension" drop-down menu.
4. Click the "Convert" button to convert the string to the selected naming convention.
5. The converted string will appear in the "Output String" field.

## How it Works

The page uses JavaScript to convert the input string to the selected naming convention. The conversion functions are:

- `convertToCamelCase`: Converts the string to camelCase.
- `convertToPascalCase`: Converts the string to PascalCase.
- `convertToSnakeCase`: Converts the string to snake_case.
- `convertToKebabCase`: Converts the string to kebab-case.
- `convertToUpperUnderscore`: Converts the string to UPPER_UNDERSCORE.
- `convertToHungarianNotation`: Converts the string to HungarianNotation.

Each function takes a string as input and returns the converted string.

The page also displays a table showing the recommended naming convention for each programming language.
