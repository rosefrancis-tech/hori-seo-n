# &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Hori*seo*n  

[Summary](#Summary) &nbsp; &nbsp; [Introduction](#Introduction) &nbsp; &nbsp; [User Story](#User-Story) &nbsp; &nbsp; [Acceptance Criteria](#Acceptance-Criteria) &nbsp; &nbsp; [Mock-Up](#Mock-up) &nbsp; &nbsp; [Code Review](#Review) &nbsp; &nbsp; [Acknowledgements](#Acknowledgements)  

 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [***Live Project***](#Live-Project)

## Summary 
This project is an on-the-job ticket for a feature request of an existing website of 'Horiseon'.

## Introduction
Horiseon is a marketing agency. The company wants their website to follow ***accessibility standards***.  
This will make their website optimized for search engines.

## User Story
<details>
<summary>Expand</summary>  

    AS A marketing agency
    I WANT a codebase that follows accessibility standards
    SO THAT our own site is optimized for search engines 
</details>

## Acceptance Criteria
<details>
<summary>Expand</summary>

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
</details>

## Mock-Up
The following image shows the web application's appearance and functionality.

Mock-up image: ![Mock-up image](/assets/images/mock-up.png "Mock-up image")

## Code Review
These are the major refactorings made in the code
      
HTML  
- Changed title into consice and descriptive
- Introduced five major elements in the body: Header, Section(for Hero), Main, Aside, Footer
- Changed divs inside the Main and Aside into article and sectio elements respectively
- Fixed header links
- Removed classes for div elements after they are made semantic
- Added anchor element for h1 in the header
- Added alt description for all images including icons in less than 125 words each
- Gave proper indentations
- Added comments
      
CSS
- Grouped and rearenged the selectors and properties
- Made corresponding semantic element changes
- Removed duplication of styles  
- Added comments
    
The completed project is uploaded in Github for approval.  
Please review it in the repository link below:  
> [https://github.com/rosefrancis-tech/hori-seo-n](https://github.com/rosefrancis-tech/hori-seo-n)

## Live Project
Deployed Application url: [https://rosefrancis-tech.github.io/hori-seo-n/](https://www.markdownguide.org "markdownorg.com")

## Acknowledgements
1. [Ticket Source](https://courses.bootcampspot.com/courses/484/assignments/7224?module_item_id=111994 "courses.bootcamp.com")
2. [Mark Down Guide](https://www.markdownguide.org "markdownorg.com")
3. [Mark Down Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Github")
4. [Advanced Markdown](https://github.com/DavidWells/advanced-markdown/blob/master/README.md "Github")
5. [steemit.com](https://steemit.com/markdown/@jamesanto/how-to-add-multiple-spaces-between-texts-in-markdown)
6. [Alt attributes for icons](https://dev.to/nadiarasul/do-icons-need-alt-attributes-5g52#:~:text=If%20an%20icon%20is%20added,%3Cimg%20src%3D%22icon. "dev.to")
7. [Google Image Best Practices](https://developers.google.com/search/docs/advanced/guidelines/google-images?hl=en&visit_id=637427119836065408-1354604991&rd=1 "google.com")
