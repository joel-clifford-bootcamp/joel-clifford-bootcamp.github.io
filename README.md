# homework-1
Homework Assignment 1: Code Refactor

# Repo Contents

## index.html 

Root page for website

## style.css

Website styling

## Various images

Website content


# Change Log

1. Removed span with class="seo" breaking up header text seemed arbitrary and class "seo" does not extend the base h1 styling in any way ("seo" callout removed from css as well)
    - Not sure of how seo works, could this seo have been borken out for search-engine optimization purrposes?

2. Added "search-engine-optimization" id tag to appropriate element to fix broken header link.

3. Replaced <div> with class tag "hero" with image with same sourced tagged as class "hero" to meet client reqirement that source code contain all semantic elements.

4. Added alt text to all images per client requirement

5. Changed title element to "Horiseon"

6. Changed footer heading form h2 to h4 to continue pattern of shrinking heading size

# Assignment Outline:
## 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

### Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

