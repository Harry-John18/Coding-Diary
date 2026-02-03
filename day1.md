Day 1: 29/01/2026
What I Learned - 
[Basics of Html]
Description: Moving beyond basic text tags to build accessible, meaningful page structures and handling user input.
Key Concepts:
Semantic Tags (<nav>, <article>, <aside>, <section>) vs. <div>.
Forms & Inputs (Text, Password, Checkbox, Radio, Submit buttons).
Media Elements (Images, Audio, Video, SVGs).
Hyperlinks and Anchors (Absolute vs. Relative paths).
Diary Task: Build a "Registration Page" with a name field, dropdown menu for country, and a bio text area.

Problems Faced
Broken Images: My profile picture showed a broken icon because I didn't understand how to step up a folder level (../images/pic.jpg) in the file path.
Form Refresh: Every time I clicked the "Submit" button, the page refreshed instantly, and I lost all the data I just typed.
Nesting Errors: I accidentally put a <div> inside a <p> tag, and the browser rendered it weirdly because block elements shouldn't go inside inline elements.

How I Solved Them
Broken Images: I moved my images into a dedicated assets/images folder and updated the path to src="./assets/images/pic.jpg". I also learned to use VS Code's autocomplete to verify the path exists.
Form Refresh: I looked up the <form> element and realized action defaults to the current page. For now, I added onsubmit="return false" to stop the reload while I test the layout.
Nesting Errors: I used the W3C HTML Validator tool, which flagged the invalid nesting. I replaced the inner <div> with a <span> since it's an inline element.
