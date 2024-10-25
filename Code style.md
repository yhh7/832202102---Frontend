# Code style

**Source:** This code style guide is based on [JavaScript](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API) ,  [HTML](https://web.dev/learn/html/apis?hl=zh-cn), [CSS](https://developers.google.com/comparison-shopping-services/api/reference/rest?hl=zh-cn)

## Languaged Used:

- **JavaScript:   **adds interactivity and dynamic behavior to web pages.
- **HTML（HyperText Markup Language）：** provides the structure of web pages.
- **CSS（Cascading Style Sheets）：**styles and layouts the web pages. 

## CodeStyle：

#### JavaScript：

1.  **Indentation and Line Length**：
   - Use spaces or tabs consistently for indentation to enhance code readability.
   - Limit the line length to a specific number of characters, often around 80 or 120, to prevent the need for horizontal scrolling.
2. **Braces and Semicolons**：
   - Decide on a convention for placing braces (e.g., same line or next line).
   - Determine whether to always use semicolons at the end of statements to avoid automatic semicolon insertion (ASI) issues.
3. **Descriptive Naming**：
   - Use descriptive and consistent naming conventions for variables, functions, and classes to make the code more understandable.

#### HTML:

1. **Indentation and Line Length**:
   - **Indentation**: Use two or four spaces for indentation to improve readability. Indentation should reflect the hierarchy of elements.
   - **Line Length**: Similar to other programming languages, it’s a good idea to keep lines under 80 or 120 characters long. Long lines can be broken at appropriate points, such as after attributes.
2. **Tags and Attributes**:
   - **Lowercase Tags**: Use lowercase for all HTML tags to maintain consistency.
   - **Attribute Quotes**: Always use double quotes around attribute values to avoid issues with certain characters and to maintain consistency.
   - **Attribute Spacing**: Put a space before the value in an attribute, but not at the end of the tag.
3. **Self-Closing Tags**:
   - Use self-closing tags for void elements like `<img>`, `<input>`, and `<br>`. For example: `<img src="image.jpg" alt="Image" />`.
4. **Doctype and Encoding**:
   - Always declare the doctype at the beginning of your HTML document to ensure the browser renders the page in standards mode.
   - Include the character encoding declaration (`<meta charset="UTF-8">`) as early as possible in the `<head>` section.

#### CSS:

1. **Consistent Indentation**:
   - Use two or four spaces for indentation to reflect the hierarchy of selectors and properties, which is crucial for readability and understanding the structure of your CSS.
2. **Property Order**:
   - Alphabetize properties or group them by function within a selector to make it easier to find and manage specific styles.
3. **Comments**:
   - Use comments to explain complex sections or to provide context, which is essential for maintainability and for other developers to understand the code.
4. **Selector Naming Conventions**:
   - Use descriptive, lowercase names with hyphens for classes and IDs to ensure that your CSS is clear and easy to understand, which is key for reusability and collaboration.

## File Naming：

- HTML file should be named `index.html`
- JavaScript file should be named `element.js`
- CSS file should be named `element.css`