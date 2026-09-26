## Markdown

1. Headings
Markdown supports six levels of headings.
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
The number of # symbols determines the heading level.
Example
# Web Development
## Frontend Development
### HTML
### CSS
### JavaScript

## Backend Development
### Node.js
### Python
Important Rule
There should be a space between the # and the heading text.
Correct:
# My Heading
Incorrect:
#My Heading

2. Paragraphs
Normal text can simply be written as a paragraph.
Markdown is easy to learn.
It is commonly used for documentation.
A blank line separates paragraphs.

3. Line Breaks
You can create a new line by using two spaces at the end of a line.
Hello World
Welcome to Markdown.
However, in most cases, separating paragraphs with a blank line is preferred.

4. Bold Text
To make text bold, surround it with two asterisks.
**This is bold text**
Result:
This is bold text
You can also use double underscores:
__This is bold text__


5. Italic Text
Use one asterisk around the text.
*This is italic text*
Result:
This is italic text
You can also use underscores:
_This is italic text_

6. Bold and Italic
You can combine both.
***This is bold and italic***
Result:
This is bold and italic

7. Strikethrough
Strikethrough is commonly supported by GitHub and many Markdown editors.
Use two tilde characters:
~~This text is no longer correct~~
Result:
This text is no longer correct

8. Blockquotes
A blockquote is created using the > symbol.
> This is a quotation.
Result:
This is a quotation.
You can create multiple levels:
> This is the first level.
>
> This is another line.
Blockquotes are useful for:
• Quotes
• Important notes
• Referencing another person's statement
• Highlighting information

9. Unordered Lists
Use -, *, or +.
Example:
- HTML
- CSS
- JavaScript
- Node.js
Result:
• HTML
• CSS
• JavaScript
• Node.js
Using * also works:
* HTML
* CSS
* JavaScript
It is generally better to choose one style and remain consistent.

10. Ordered Lists
Use numbers followed by a period.
1. Install Node.js
2. Create a project
3. Install dependencies
4. Start the application
Result:
1. Install Node.js
2. Create a project
3. Install dependencies
4. Start the application

11. Nested Lists
Lists can contain other lists.
- Frontend
- HTML
- CSS
- JavaScript
- Backend
- Node.js
- Express
- PostgreSQL
Result:
• Frontend
• HTML
• CSS
• JavaScript
• Backend
• Node.js
• Express
• PostgreSQL
Indentation is important.

12. Checklists / Task Lists
Markdown can create task lists.
- [ ] Install Node.js
- [ ] Create project
- [ ] Configure database
- [x] Create README
Result:
■ Install Node.js
■ Create project
■ Configure database
■ Create README
[ ] means incomplete.
[x] means completed.

Checklists are especially useful for:
• Project tasks
• GitHub issues
• Documentation
• Tutorials
• Project planning

13. Links
Create a link using:
[Link Text](URL)
Example:
[Visit GitHub](https://github.com)
The displayed text is:
Visit GitHub
Link to Another Section
You can also link to headings within a Markdown document, depending on the platform rendering the Markdown.

14. Images
Markdown can display images using:
![Alternative Text](image-url)
Example:
![Company Logo](https://example.com/logo.png)
The structure is:
![alt text](image location)
The alternative text describes the image if the image cannot be displayed.

15. Horizontal Lines
You can create a horizontal line using three or more hyphens.


16. Inline Code
Use backticks around a small piece of code.
Use the `ls` command to list files.
Result:
Use the ls command to list files.
This is useful for:
• Commands
• Variable names
• Function names
• File names
• Small code snippets
Example:
Run `npm install` to install dependencies.

17. Code Blocks
For multiple lines of code, use triple backticks.
const name = "Goodluck";
console.log(name);
The language can be specified after the opening backticks.
For example:
print("Hello World")
or:


npm install npm run start
or:
SELECT * FROM users;
This is called syntax highlighting.

18. Common Code Block Languages
You can specify languages such as:
javascript
typescript
python
java
c
cpp
html
css
bash
shell
sql
json
yaml
xml
markdown
Example:
function greet(name: string): string { return Hello ${name}; }

19. Tables
Markdown can create tables using pipes | and hyphens -.
Example:
| Name | Age | Role |
|------|-----|------|
| John | 25 | Developer |
| Mary | 30 | Designer |
Result:
Name Age Role
John 25 Developer
Mary 30 Designer


20. Aligning Table Content
You can control alignment using colons.
Left aligned
| Name |
|:-----|
| John |
Center aligned
| Name |
|:----:|
| John |
Right aligned
| Name |
|-----:|
| John |
Example:
| Product | Price | Quantity |
|:--------|------:|:--------:|
| Laptop | $800 | 2 |
| Mouse | $20 | 5 |

21. Escaping Markdown Characters
Sometimes you want Markdown characters to appear as normal characters instead of being interpreted.
Use a backslash:
\*This is not italic\*
Result:
This is not italic
Common characters that may need escaping include:
*
_
#
`
[
]
(
)
\

22. Special Characters and HTML
Markdown often supports HTML.
Example:
<strong>This is bold</strong>
Some Markdown processors allow HTML elements directly inside Markdown documents.
However, HTML support can vary between platforms.
For beginners, it is better to use normal Markdown syntax whenever possible.

23. Comments
Some Markdown environments support HTML comments.
<!-- This is a comment -->
The comment will generally not be visible when the Markdown is rendered.
Comments can be useful for leaving notes inside documentation.

24. Emojis
Many platforms support emojis directly
This project is ready! ■
Some platforms also support emoji codes, but direct Unicode emojis are usually the simplest approach.

25. Escaping Code
If you need to show triple backticks inside a code block, use four backticks around the example.
Example:
console.log("Hello");
This is useful when teaching Markdown because you can show Markdown syntax without having it rendered
