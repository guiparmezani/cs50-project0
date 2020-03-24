# Project 0

This project is a basic website about myself. It has four different web pages that are accessible using the main nav links at the top of each page. The pictures and copies were all produced by myself. The website is responsive and should work in any kind of device that runs a browser.

## Files

- **/README.md**: Text file that details what this project is;
- **/index.html**: HTML file that serves as front page to the website. The content consists in an image and some paragraphs about myself ;
- **/work.html**: HTML file that serves as front page to the website. The content consists in an image and some paragraphs about what I do for a living;
- **/hobbies.html**: HTML file that serves as front page to the website. The content consists in an image and some paragraphs about hobbies I have;
- **/travels.html**: HTML file that serves as front page to the website. The content consists in an image and some paragraphs about travels I've done in the past;
- **/styles/variables.scss**: Contains SCSS variables that are used to generate CSS values to the main stylesheet;
- **/styles/main.scss**: The SASS version of the main stylesheet. Contains the styles that should be read by the browser when the website is rendered. Imports "variables.scss";
- **/styles/main.css**: The main stylesheet CSS file that's read by the browsers. This file is a result of the compilation of the SASS file "/styles/main.scss";
- **/styles/main.css.map**: Reference file that maps the SASS file instructions to the compiled CSS file;
- **/img/***: All files within the "img" folder are images that are rendered on each of the pages of the website;
- **/.gitignore**: Reference file that ``git`` uses in order to keep files out of the version control stream.

## How to run the site

A webserver is not necessary to run this simple website. To run it, simply open the ``index.html`` using a browser and navigate through the pages. If you wish to build the site before running it, follow these steps:
1. Open up a terminal;
2. Navigate to the project folder;
3. Navigate to the ``styles`` folder;
4. Run ``sass main.scss main.css``;
5. Open the ``index.html`` file using a browser.