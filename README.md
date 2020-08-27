# hw-01-code-refactor

## Description 

This is the homepage for Horiseon Social Solution Services. I was provided with a completed web page, but the HTML for the page was not ideal as it did not take advantage of semantic elements. I improved the semantics without making any changes to the functionality or appearance of the website.

## Changes made in HTML

Please note that none of these changes affected the appearance or functionality of the web page in any way. Still, replacing the generic element "div" with a more self explanatory semantic element makes one's code easier to read, understand, and edit.

I have added comments in the HTML file to show where each change was made

* <div class="header"> became <header>
* <div> that contains navigation links became <nav>
* <div> that contains the main page background image became <figure>
* <div class="content"> became <main>
* The <main> part of the page contains three smaller sections which were at first defined by <div>s but I changed them to <section>s.
* The <div> that floats to the right of the page became an <aside>, which also contains three <section>s
* <div class="footer"> became <footer>
* Added alt descriptions to every image, improving the page accessibility.
* CSS selectors were also updated accordingly to maintain styling.

## Improvements in redundant styling

## Screenshot of page
![Image of Screenshot](./assets/images/Horiseon_screenshot.png)

## URL

You can view the deployed site at https://judeclark19.github.io/hw-01-code-refactor/