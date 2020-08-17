# 01-Code Refractor
```
One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.
```
## User Story
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
## Acceptance Criteria

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
## Issues & Explanation:
```
Live Site: 
     https://EdenKhao.github.io/wk1-homework/
   
Code Repo: 
     https://github.com/EdenKhaos/wk1-homework 
  
Issues & Explainations:
     https://github.com/EdenKhaos/wk1-homework/edit/master/README.md
     
```     
## Follow psuedo code in html file (index.html)
```
1. placed full company name between title tag
2. decription of the company
3. change div to header to specifiy location on page
4. read as button and not link
5. create a nav tag to define nav bar links
6. clean up listed items in ul to bring user to section in body when link is clicked
7. change div to header closing
8 add alt to image
9. change div to section
10. add alt to image
11. add alt to image
12. add alt to image
13. add alt to image
14. change div to section closing
15. change div to section
16. add alt to image
17. add alt to image
18. add alt to image
19. change div to section closing
20. change div to footer
21. change div to footer closing
```
## Things checked for in the html.
```
1. links from nav bar go to body sections when clicked.
2. all images ahave added alt for accessibility
3. all cascading elements go in a logical and sequential order
4. overal html structure is cleaner than before and logical structure as best as I know how at the moment
6. new elements such as role="" were googlefoo for clarity to help the accessibility to function correctly by adding classification tags
```
## Follow psuedo code in css file (style.html)
```
1. remove .
2. change header background color to match the body section blue color
3. remove .
4. remove .
5. change seo color to be darker
6. remove .
7. remove . 
8. remove . 
9. remove . 
10. remove . 
```
## Things checked for in the css.
``
1. clean up nav bar color to match closer to body section blue.
2. seo lettering color change in header h1 to contrast with white color lettering around seo
3. remove "." for element class as element classes were remove or renamed under another tag type to allow the CSS to work
