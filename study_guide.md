# HTML
https://learn.shayhowe.com/html-css/building-your-first-web-page/

- "HTML, HyperText Markup Language, gives content structure and meaning by defining that content as, for example, headings, paragraphs, or images."

## Common Terms

### Elements

- "Elements are designators that define the structure and content of objects within a page."

### Tags

- "The use of less-than and greater-than angle brackets surrounding an element creates what is known as a tag. Tags most commonly occur in pairs of opening and closing tags."

### Attributes

- "Attributes are properties used to provide additional information about an element."

- ID: defines an element
- Class: classifies an element
- SRC: specifies a source for embeddable content
- href: provides a hyperlink reference

## Basic Structure

```
<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>
</body>
</html> 
```
## Basic Text Format

### Bold

- `<strong></strong>`
- `<b></b>`

## Italic

- `<em></em>`
- `<i></i>`

# CSS

## Common Terms

### Selectors

- "A selector designates exactly which element or elements within our HTML to target and apply styles (such as color, size, and position) to."

- Type Selectors: <d> {...}
- Class Selectors: .class {...}
- ID Selectors: #id {...}

### Properties

- "Once an element is selected, a property determines the styles that will be applied to that element."

### Values

- "Now we can determine the behavior of that property with a value."

## Referencing CSS

- Within the HTML `<head>`, you can reference the CSS document using `<link>`

```
<head>
  <link rel="stylesheet" href="main.css"> 
</head>
```


