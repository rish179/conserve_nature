+this HTML-CSS,bootstrap project contains 5 HTML pages with theme on "NATURE CONSERVATION".

page 1: index.html
- It is designed to be homepage.
  It contains an image "nature.jpg" ,a stylesheet and an ordered list.
  There are links to other web pages at the bottom.
page 2: index2.html
- It is designed to be "how can we save our nature".
 stylesheet contains:
                  @media query,which changes background color whenever screen size changes.
                  css selector to style paragraph based on selection(p::selection{})
   It contains an image(plant.jpg)
   It contains a table with border and cellpadding.
     to store name of donors.
   There are links to other webpages at the bottom of the page.
page 3: index3.html
-  it inherits it stylesheet from a separate .css file(style.css).
-  it contains a unordered list where each list item represents a link to saparate paragraph on the same page.
- also each link is styled with (a:hover) element thus changes color upon cursor hovering.
- each portion contains an image relating to the topic itself.
-there is hyperlink in last para to take the user to 1st para for 'threats of nature'.
-there are links for other pages at the bottom.
    style.css
    -it contains selectors .reason, .threat, a hovering element

page 4:index4.html
-this page use bootstrap4 in it.
-it includes bootstrap container class to form grid of 2 rows and 2 columns.
-it also use bootstrap card component nested inside grid columns.
-card component image at the top with card title and card text below it.
-there are links at the bottom.

page 5: index6.html
-it inherits its style sheet from a saas file.
 index5.scss:
    it contains a variabal $color.
    a class %meaasures.
     a class div which has a nested method p{}'and ul{}.
     a selector .solar, .wind, .hydro, .bio.

