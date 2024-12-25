CSS Assignments: Chapters 10 and 11
Chapter 10: Introducing CSS
Assignment 1: Style a Heading and Paragraph
1. Create a webpage with:
   - One heading (<h1>)
   - One paragraph (<p>)
2. Use CSS to:
   - Change the heading's text color to blue.
   - Make the paragraph text italic.
Assignment 2: Internal CSS Practice
1. Create a simple webpage with:
   - A heading
   - A paragraph
2. Use internal CSS (inside <style> tags) to:
   - Center the heading.
   - Change the paragraph's font size to 18px.
Assignment 3: Using Selectors
1. Create a webpage with:
   - Two paragraphs.
2. Style the first paragraph with a class to make its text red.
3. Style the second paragraph using an ID to make its text green.
Inline, Internal, and External CSS
Inline CSS:
   - Applied directly within HTML elements using the "style" attribute.
   - Example: <div style="color: red;">Hello</div>

Internal CSS:
   - Placed inside <style> tags in the <head> section of the HTML document.
   - Example:
     <style>
       body { color: blue; }
     </style>

External CSS:
   - Created in a separate .css file and linked to the HTML document using a <link> tag.
   - Example:
     <link rel="stylesheet" href="styles.css">
Chapter 11: Color
Assignment 4: Adding Background Colors
1. Create a webpage with:
   - One heading
   - One paragraph
2. Use CSS to:
   - Add a light yellow background to the webpage.
   - Add a light blue background to the paragraph.
Assignment 5: Using Named Colors
1. Create a webpage with three headings.
2. Use CSS to:
   - Style the first heading with the color red.
   - Style the second heading with the color green.
   - Style the third heading with the color blue.
Assignment 6: Transparency
1. Create a webpage with a <div> containing some text.
2. Use CSS to:
   - Set the <div> background color to semi-transparent red using rgba(255, 0, 0, 0.5).
Combined Assignment: Simple Webpage with Styles
1. Create a webpage with:
   - A heading
   - Two paragraphs
   - A button
2. Use CSS to:
   - Style the heading to be bold and green.
   - Give the paragraphs different text colors.
   - Style the button with a light blue background and white text.
CSS Selector Precedence Assignments
Assignment 7: ID Selector Precedence
1. Create a webpage with:
   - A heading
   - A paragraph
2. Use the following CSS:
   - Style the heading with a color of red using a class selector.
   - Use an ID selector to override the color of the heading to green.
   - Verify that the ID selector takes precedence and makes the heading green.
Assignment 8: Class Selector Precedence
1. Create a webpage with:
   - Two paragraphs
2. Use the following CSS:
   - Style both paragraphs with a class selector to make their text blue.
   - Use a type selector to set the color of the second paragraph to black.
   - Use the class selector with higher specificity to keep the first paragraph blue.
   - Verify which selector wins in the second paragraph.
Assignment 9: Type Selector Precedence
1. Create a webpage with:
   - A list of items (unordered list)
2. Use the following CSS:
   - Style the entire list with a type selector to set the list item color to orange.
   - Use a class selector to change the color of one specific list item to purple.
   - Verify that the class selector overrides the type selector for that item.
Assignment 10: Universal Selector Precedence
1. Create a webpage with:
   - A paragraph
   - A heading
2. Use the following CSS:
   - Apply a universal selector (*) to set the background color of all elements to light gray.
   - Use a type selector to change the paragraph's background to white.
   - Verify that the universal selector applies to all elements except the paragraph.
