# UW CSE 154 CP 1

## Development Requirements

- [x] Complete `about.html` following the `TODO` instructions in the file

- [x] Create a new html file, and link it with `about.html` by setting a hyperlink in `about.html`

    - [x] **In the second `.html` file**, you must use at least 8 different types of HTML tags total in the `<body>`, in addition to the required `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, `<link>`, and `<body>`. At least 2 of the 8 tags should be semantic tags listed under "HTML Layout Elements in More Detail" [here](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#HTML_layout_elements_in_more_detail).

        > I have `h1`, `h2`, `article`, `section`, `img`, `div`, `aside`, `header`, `main`, `footer`, `p`, etc. Among them,  `article`, `section`, `aside`, `header`, `main`, `footer` are tags listed under "HTML Layout Elements in More Detail".

- [x] You must link `styles.css` to both `about.html` and your other HTML page to style your website with a consistent look and feel.

    - [x] At least 4 additional different rulesets other than the one with the `body` selector provided in the starter file. Refer to [this page](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#Selectors) for a CSS reference of selectors. One of your rulesets must use a **combinatorial selector**, and one of your rulesets should have a **grouped (comma-separated) selector**.
    - [x] At least 5 different CSS properties defined which style content in your HTML files. The CSS properties in the starter `styles.css` will not count towards this requirement, and you may change/remove them.
    - [x] At least one [Google font](https://fonts.google.com/) of your choice imported and used with an appropriate default font (e.g. `sans-serif`) specified. **Remember to import Google fonts at the top of your CSS file, not in the HTML!**



## Documentation

- [x] Place a comment header in **each file** with your name, section, a brief description of the assignment, and the file's contents. A good file header description is typically 2-3 sentences. Examples are shown in the spec.



## Style Rrequirements

- [x] **All file names and links in your project must be lowercased without spaces** (e.g. `img/puppy.jpg` but not `img/puppy.JPG` or `img/Puppy.jpg`). This is enforced to avoid broken links commonly occurring in CP/HW submissions due to case-insensitivity of file names on Windows machines. In general, it is also just good practice for file/directory naming.

- [x] Links to **your** `.html` and `.css` files should be **relative links**, not absolute.

- [x] Your HTML and CSS should demonstrate good code quality as demonstrated in class and detailed in the CSE 154 Code Quality Guidelines. You are expected to follow all the requirements listed under HTML and CSS (ask if you have any questions!). For Module 1, common code quality requirements students miss include:

    - [x] Using consistent indentation, proper naming conventions, curly brace locations, etc. Remember that IDs and classes should be in all-lowercase conventions and multiple words are optionally separated by "-".

    - [x] Keep lines fewer than 100 characters for readability (links are an exception to this rule)

    - [x] Do not express style information in the HTML, such as through inline styles or presentational HTML tags such as `b`, `i` or `font`.

    - [x] Prefer CSS selectors instead of using [too many classes or IDs](https://courses.cs.washington.edu/courses/cse154/codequalityguide/_site/html/#unused-classes) in your HTML.

    - [x] Do not include unused, duplicate, or overridden CSS rules or rulesets and use shared CSS selectors to factor out redundancy (see Code Quality Guide for more examples). Make sure to double-check that you didn't leave any unused styles in before submitting!

        Note that we have a [CSS Redundancy Checker](https://courses.cs.washington.edu/courses/cse154/19au/resources/assets/css-redundancy-checker/index.html) linked on the resources page of the course website. Make sure to use this to check you do not have any repeated rules in your `.css` file(s)

- [x] For full credit, all HTML and CSS files must be well-formed and pass validation. The link to the W3 HTML validator can be found in the [resources](https://courses.cs.washington.edu/courses/cse154/19au/resources/) page of the course website. Warnings are ok, but you can ask if you are unsure! The HTML and CSS validator/linters will run automatically each time you commit and push your work. In order to be eligible for full points on this CP, your code **must pass all validation/linting (indicated by no errors and a green checkmark)**. See the resources page for a detailed guide explaining how to view your feedback. Note that these validators/linters may take some time to run so make sure you leave enough time to make any necessary changes before the deadline. A slow linter is not a valid reason for why an assignment was turned in late.

