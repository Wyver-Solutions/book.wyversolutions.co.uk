---
title: How to help improve this book
---
To build this book, I used the open-source [gitbook](#) toolchain.

This allows me to write the content once, in a series of [Markdown](#) files. Then gitbook creates the book in HTML, pdf and ebook (epub) formats.

The book is stored on [Github](#). If you want to suggest changes to it, you can either [post a comment](#) or fork the project and make a pull request.

## Notes to developers

To work on this project, you will need to have node installed.

After forking the project, you will need to install the dependendencies (some additional node modules).

`gitbook install`

To test the project on your local system:

`gitbook serve`

To create a static site:

`gitbook build`

To deploy the static site to github (after adding and committing):

`git subtree push --prefix _book origin gh-pages`
