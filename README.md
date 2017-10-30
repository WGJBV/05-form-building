![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 05: Form Building Workshop
===

## Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[HighlightJS Docs](https://highlightjs.org/)

[MarkedJS Docs](https://github.com/chjj/marked)

## Configuration
_Your repository must include:_

```
05-form-building
├── .eslintrc.json
├── .gitignore
├── LICENSE
├── README.md
├── index.html
├── new.html
├── scripts
│   ├── article.js
│   ├── articleView.js
│   └── blogArticles.js
├── styles
│   ├── base.css
│   ├── fonts
│   │   ├── icomoon.eot
│   │   ├── icomoon.svg
│   │   ├── icomoon.ttf
│   │   └── icomoon.woff
│   ├── icons.css
│   ├── layout.css
│   └── modules.css
└── vendor
    └── styles
        ├── default.css
        ├── normalize.css
        └── railscasts.css
```


## Feature Tasks

- Continue styling the app using SMACSS practices. Take a few minutes for code review of your partner's CSS and decide how to incorporate it into your paired lab. You can choose one partner's CSS structure, or you can combine them as you see fit. Seek to optimize and organize your CSS as much as possible!

*As a user, I want to be able to add new articles to my blog app so that it can stay current over time.*

- Review the image `preview.png` in the lab directory to get an idea of what we will be building.
- Focus on the functionality of adding a new article through a form submission by completing the TODOs in articleView.js.
- The new page with the form should provide a JSON string which can be copy/pasted into the data file to add articles to the blog.

*As a developer, I want to make the user experience easy to understand so that the user will want to return to the blog.*

- We now have two pages in our blog app, each of which need different initialization. There is a skeleton of a method in articleView.js to get this started for the new page; be sure to examine how this is now being done for the index page.
- The new page with the form will need event handling and a template. Where should these pieces go in the code?
- The new page should not display any other articles

### Stretch Goal
*As a user, I want to add highlighting and Markdown formatting so that it is attractive to guests visiting my app.*

- We have two new libraries that we can add: HighlightJS (provides syntax highlighting of code blocks) and MarkedJS (allows use of Markdown format text). Link to (or include) these two libraries and implement them.

## Documentation
_Your README.md must include:_

```md
# Project Name

**Author**: Garrett Johnson
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
This application is meant to add a new user-generated article to our Kilovolt Blog page. We're building it to get a better understanding of how to process user input using jQuery.

## Getting Started
1. Ensure the main .tab-content area is revealed.
2. Have the new articles be copy and pasted into our source data file.
3. Add an event handler to update and preview.
4. After refactoring the HTML into using handlebars, put this new article into the DOM
5. Look up hljs in order to activate all the highlighted code.
6. Export the new article to JSON

## Architecture
I used jQuery, hljs, handlebars, CSS, HTML and JS.
