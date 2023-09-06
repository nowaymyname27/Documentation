### HTML Cheat Sheet

- **Headings**: `<h1>heading</h1>`
- **Paragraphs**: `<p>paragraph</p>`
- **Break Line**: `<br />`
- **Horizontal Line**: `<hr />`
- **Unordered lists**: `<ul> <li></li> </ul>`
- **Ordered lists**: `<ol> <li></li> </ol>`
- **Anchor Element**: `<a href="link">This is a link</a>`
- **Image Element**: `<img src="" alt=""/>`

#### Attributes:
Attributes provide additional information about an element. They always come in name/value pairs:
- **alt**: This attribute is used in the `<img>` tag to provide a text description of the image. It is important for accessibility and in case the image fails to load. E.g., `<img src="image.jpg" alt="Description of image">`
- **href**: This attribute is used in the `<a>` tag to specify the URL of the page the link goes to. E.g., `<a href="https://www.example.com">Visit our site</a>`
- **src**: This attribute is used in the `<img>` tag to specify the source URL of an image. E.g., `<img src="image.jpg" alt="Description of image">`
- **draggable**: This attribute is used to specify whether an element is draggable or not. It is mostly used in drag-and-drop interfaces. Values can be "true", "false", or "auto". E.g., `<img src="image.jpg" draggable="true">`
- **id**: This attribute is used to specify a unique id for an HTML element. You can use the id to select a specific element with JavaScript or CSS. E.g., `<div id="header">This is the header</div>`
- **class**: This attribute is used to specify one or more classnames for an element. The class is often used to point to a class name in a style sheet. It can also be used by JavaScript to access and manipulate elements with the specific class name. E.g., `<div class="header">This is the header</div>`

#### CSS
- **Inline**: `<html style="property: value"></html>`
- **Internal**: `<style> html {property: value; } </style>`
- **External**: `<link rel="stylesheet" href="./styles.css"/>`
