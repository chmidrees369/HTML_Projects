# Chess Board

This project features a simple HTML representation of a chess board using a table layout. The board consists of alternating white and black squares, arranged in an 8x8 grid to mimic a standard chess board design.

## Features

- **Responsive Layout:** The board is centered on the page with a fixed width and height.
- **Simple Color Scheme:** The squares alternate between white and black, creating the classic chess board appearance.
- **Easy to Customize:** The HTML structure allows for straightforward modifications to colors, sizes, and styles.

## HTML Structure

- **DOCTYPE and Language:** The document is defined as an HTML5 document with English as the primary language.
- **Head Section:**
  - Sets the character encoding to UTF-8.
  - Ensures compatibility with Internet Explorer.
  - Configures the viewport for responsive design.

- **Body Section:**
  - Contains a centered header (`<h1>`) titled "Chess Board".
  - A table (`<table>`) that forms the chess board:
    - The table consists of 8 rows (`<tr>`), each containing 8 cells (`<td>`).
    - Each cell has a fixed width of 100 pixels and height of 50 pixels, with alternating background colors for visual distinction.

## Usage

To view the chess board, open the HTML file in a web browser. You can modify the colors and dimensions of the cells to customize the appearance of the chess board as desired.

## Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chess Board</title>
</head>
<body>
    <h1><center>Chess Board</center></h1>
    <table width="500" height="100" border="1" align="center">
        <!-- Table rows and cells go here -->
    </table>
</body>
</html>

