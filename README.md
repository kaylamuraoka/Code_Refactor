# Code Refactor for Semantic Rules & Web Accessibility Standards

## Description

Horiseon's website follows a simple website design using a single HTML page and external css file (located in the assets folder). The original website design and code was provided, which I then modified to make the site further optimized for search engines.
I did this in a few steps:

1. Following HTML semantic logic, I changed the non-semantic div elements (that don't give the browser any indication of its content) to the semantic elements: header, nav, content, aside, section, and footer. This new code gives the browser and indication of the sites content and follows a logical structure.
1. Following web accessibility standards, I added proper alternative text for images by adding alt atributes to all image tags.
1. I changed the title element to have a concise, descriptive title.
1. I condensed the css style sheet code by converting redundant classes that had the same attributes to a single class that could be refrenced multiple times. For example, I changed the online-reputation-management, search-engine-optimization, social-media-marketing classes to the semantic element, section to reduce redundancy.
1. I Added a clearfix class so that any child elements using float properties wouldn't overflow outside of the parameters of its parent element.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To install this project locally clone this [**project repository**](https://github.com/kaylamuraoka/HTML_CSS_Git_Code_Refactor) to your local terminal and modify the code to your liking.

## Usage

The refactored website can be seen at: https://kaylamuraoka.github.io/HTML_CSS_Git_Code_Refactor/

The following image shows the web application's appearance and functionality:
![Screenshop of Refactored Website](./screencapture_of_website.png)

## Credits

The original website design and code was provided, which I then enhanced to make the site optimized for search engines by meeting website accessibility standards and HTML semantic rules.

## License

This project is licensed under [**GNU GPL v3**](https://choosealicense.com/licenses/gpl-3.0/).
