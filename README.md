# Welcome to my "Project 1" for Code Institute Full Stack Developer course!

## About the website
 
Description

Screenshot from https://ui.dev/amiresponsive

## Features

### The header

### The logo

### The nav menu

### The hero image and cover text

### Information section

### Portifolio section

### Skills section

### Contact section

## Sources
- Website template provided by Code Institute: https://github.com/Code-Institute-Org/ci-full-template
- Footer icons provided by https://fontawesome.com/

## References
- This website was built with asistance of Code Institute professors and mentor as deliverable for "Project 1" of the course "Diploma in Full Stack Software Development (E-commerce Applications)". I extend here my gratitude for such support and material provided.

- How to reverse order of elements while using float:right for the menu items: https://stackoverflow.com/questions/4224476/floatright-reverses-order-of-spans

- Reference for aligning elemets on the top of a container: https://www.w3docs.com/snippets/css/how-to-align-inline-block-elements-to-top-of-the-container.html

- How to create a fixed header or footer using CSS: https://www.tutorialrepublic.com/faq/how-to-create-fixed-header-or-footer-using-css.php

- Control opacity of a background image without impacting other elements: https://coder-coder.com/background-image-opacity/

- Markdown guide to help builing this README.md file: https://github.com/mattcone/markdown-guide

## Bugs and resolution

### Pushing code to Github

When pushing commits to Git from Visual Studio Code, the following error may be perceived:

    `Enumerating objects: 75, done.
    Counting objects: 100% (75/75), done.
    Delta compression using up to 16 threads
    Compressing objects: 100% (51/51), done.
    error: RPC failed; HTTP 500 curl 22 The requested URL returned error: 500
    send-pack: unexpected disconnect while reading sideband packet
    Writing objects: 100% (69/69), 160.13 MiB | 5.99 MiB/s, done.
    Total 69 (delta 22), reused 0 (delta 0), pack-reused 0
    fatal: the remote end hung up unexpectedly
    Everything up-to-date`

The resolution was to set "git config http.postBuffer 524288000" as per post in Stack Overflow: https://stackoverflow.com/questions/2702731/git-fails-when-pushing-commit-to-github

### Errors in the code found upon validation

#### Errors found in the index.html file:

1. Error:

`Bad value https://www.autodesk.eu/products/3ds-max/overview?mktvar002=4417848|SEM|18880029258|142956061346|kwd-10085200&term=1-YEAR&tab=subscription&plc=3DSMAX#overview_panel_thumbnail for attribute href on element a: Illegal character in query: | is not allowed.
From line 138, column 17; to line 139, column 72
<a href="https://www.autodesk.eu/products/3ds-max/overview?mktvar002=4417848|SEM|18880029258|142956061346|kwd-10085200&term=1-YEAR&tab=subscription&plc=3DSMAX#overview_panel_thumbnail" target="_blank" rel="noopeneer" aria-label="3DSmax">`

This error cannot be resolved as Autodesk webpage uses the pipes to identify the subpage of the product.

#### Errors found in the contact.html file:

1. Error:

`Bad value text-area for attribute type on element input.
From line 41, column 17; to line 41, column 96
<input type="text-area" id="message" name="message" class="text-input" required>`

Resolved by correcting the type attribute to "text".

2. Error:

`Attribute required is only allowed when the input type is checkbox, date, datetime-local, email, file, month, number, password, radio, search, tel, text, time, url, or week.
From line 41, column 17; to line 41, column 96
<input type="text-area" id="message" name="message" class="text-input" required>`

Resolved in error 1 when the type was changed to "text".

## Testing

### User tests

The index.html and contact.html pages were tested in the following browsers:
- Google Chrome - Version 114.0.5735.198 (Official Build) (x86_64)
- Moziela Firefox - 115.0.2 (64-bit)
- Safari - Version 16.5.2 (18615.2.9.11.10)

The tests conducted analysed the behaviour of all components specially header menu and footer in different sizes, either by using Chrome Dev tools or by resizing the browser window manually.

In all sizes tested, menus, icons and content are visible and readable confirming the website responsiveness.

### Code Validation

Validation of the HTML code of both pages (index.html and contact.html) was done by using https://validator.w3.org/ and the code was fully validated with an exception, one link (href) contained in the Skills section, for the icon 3DSmax, did not pass validation for containing | (pipes), however, Autodesk webpage uses these pipes to identify the product code and redirect the visitor to the specific subpage.

The style.css file was validated by https://jigsaw.w3.org/css-validator/ and there were no errors found.

## Deployment

## Credits

- To Code Institute for providing the material in the LMS portal, specially the module "Love Runing" that shows students how to put in practice the theory learned.
- Logo created using https://looka.com/ and adjusted in Adobe Photoshop by myself.
- Hero image created using Adobe Firefly and adjusted in Adobe Photoshop by myself.
- Pictures in the Portifolio section and icons in the Skills section were provided by Ivan Gauto that kindly allowed me to create this project with his requirements for a professional architect portifolio website.