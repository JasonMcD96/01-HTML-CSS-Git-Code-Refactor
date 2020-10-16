# 01 HTML CSS Git: Code Refactor

## Description

```
01 HTML CSS Git: Code Refactor was an exercise for refactoring code. I looked through  
 the HTML file 'index.html' and CSS file 'style.css' to make it more accessible.  
 This included changing tags from one type of tag to another for a better semantics  
 within the HTML file, such as changing a div tag to an aside. As for the CSS file,  
 I looked for ways to make the references cleaner and to consolidate redundant references.
```

## Link to Live Webpage
```
 https://jasonmcd96.github.io/01-HTML-CSS-Git-Code-Refactor/
```

## Preview of Webpage

![code refactor demo](/assets/images/01-html-css-git-homework-demo.png)

## Report of Changes Made
```
This information is also in its own file: report.txt

------------------------------------- HTML --------------------------------------------

1. Div with class "search engine optimization" now also has ID of the same name.

2. added alt to search engine optimization img tag.

3. added alt to online reputation management img tag.

4. added alt to social media marketing img tag.

5. Changed title from "website" to Horiseon.

6. Changed the div with class "header" to an actual header tag.

7. added class of "navBar" to ul in header. Just as a way to clearly describe the <ul>'s purpose.

8. added alt to lead generation img tag.

9. added alt to brand awareness img tag.

10. added alt to cost management img tag

11. Changed div with class of 'footer' to an actual footer tag.

12. Changed div with class 'content' to a main tag for better semantics.

13. Changed div with class 'benefits' to an aside tag for better semantics.

14. Added class of 'navContainer' to div in header


-------------------------------------- CSS --------------------------------------------

1. Due to changing '<div class="header">' to <header>, references of '.header' were changed to 'header'.

2. Due to changing '<div class="footer">' to <footer>, references of '.footer' were changed to 'footer'.

3. 'header h1 .seo' changed to '.seo' same result with less Code.

4. consolidated the 3 references to '.search-engine-optimization', '.online-reputation-management', and '.social-media-marketing' img tags to one reference for the parent class of    
    all three items: class="content"

5. consolidated the 3 references to 'search-engine-optimization', 'online-reputation-management', and 'social-media-marketing' h2 tags to one reference for the parent class of
    all three items: class="content"

6. Changed reference 'header div' to 'navContainer'

7. Changed 'header div ul' to '.navBar'

8. Consolidated .benfit-lead, brand, and cost into one line '.benefit-lead, .benefit-brand, .benefit-cost' since the 3 seperate references all did the same action.

9. consolidated benefit-lead, brand, and cost references to h3 tags into one reference using the parent class: class=".benfits"

10. consolidated benefit-lead, brand, and cost references to img tags into one reference using the parent class: class=".benfits"

11. consolidated .search-engine-optimization, .online-reputation-management, .social-media-marketing references into one reference since they were all doing the same thing
```