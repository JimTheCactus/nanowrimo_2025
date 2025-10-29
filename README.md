# NaNoWriMo 2025
A repository for my NaNoWriMo 2025 novel. This repository will accept chapters of a book and publish them via github pages.

## Specifications
* There will be a GitHib Actions workflow to publish the chapters to github pages on commit
* The site will be hosted on github pages
* Input chapters are provided as markdown files
* The header and footer of each chapter will have a link to the home page as well as a link to the next and previous chapters
* The pages will be styled such that they look like a green screen terminal (black text on a green background)
* The home page will have a table of contents with a list of the chapters that are links to the chapter pages
* The HTML/CSS/JavaScript will be generated using a standard static site generator like Jekyll or Hugo
* The site will be responsive and mobile-friendly
* Automatic generation of the table of contents (TOC) from chapter files during the build
* Word count tracking per chapter and total, with progress toward 50,000 words
* Support Obsidian-style wiki-links (e.g., [[Chapter Title]]) resolved to chapter URLs

## Stretch goas
* Ideally as files in an Obsidian vault using the Git plugin
* The bottom of the screen will have a command line interface for the user to interact with the book (such as navigating to new chapters via "cat chapter 2" or something similar)
* The site will be hosted on a custom domain
