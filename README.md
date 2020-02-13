# kakao-clone-examples

- Code Reference: https://github.com/search?q=kakao+clone+examples

# Git: Version Control System

- Tracking history of editing file/document/code
- repository is folder that git is looking at it
- commit is a record change of file change

# 1-8

- Browser is chrome, safari, firefox …
- HTML is Markup. It is telling/marking browser what is what. Telling browser that this is header, putter …
- CSS is telling browser how everything looks like(design).

# 2-2

- HTML is consisted of tag.
- HTML document is just text with lots of tags into.

# 2-3 Anatomy of HTML tag

- webservers are configured to check index.html first.

# 2-4 First HTML Doc

- You should tell Google chrome browser that this document is HTML by Doctype tag
- "html:5" to initialize html document

# 2-5 metatags

- meta means extra information
- meta charset is preventing ??? incidents
- meta descriptions are important s ince it is breif description (especially in google search result)
- head tag is information which is invisible for user
- meta information is for the browser, not visible for users
- body tag is visible content which is for the user
- These are meta information which google understands: https://support.google.com/webmasters/answer/79812?hl=en
- meta tag document: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta

# 2-6 semantic vs non semantic tags

- semantic tags means something
- for example, h1 means header, section mean this is particular section
- These are semantic tags: https://www.w3schools.com/html/html5_semantic_elements.asp
- non-semantic tags on the other hand, doesn't mean anything
- for example, div, span tag doesn't mean anything
- div is just default container that we put stuffs inside.

# 2-7 baptizing/differentiating our tags a name: id and class

- Differentiating same tags are necassary, for css work later on.
- id is like passport number. id is unique.
- class is like nationality. class is not unique
- sharing same class and having different id is possible
- when somethings have in common, then it should share same class
- for example chat messages are class: because there are many of them.
- but individual chat messages are id.

# 3-2 CSS Syntax

- Selector for the tag
- Instead of inline css, which is using style tag, use separate css file
- DON'T FORGET SEMICOLON ;

# 3-4. Box Model

- Content, Padding, Border, Margin: https://www.pinterest.com/pin/426856870909031540/
- Margin is outside of box, padding is inside of box.

# 3-5. Inline vs Block vs Inline Block

- Block : block vertically next to each other (no horizontal onese)
- Inline: only text
- Inline block: block horizontally next to each other

# 3-6. Position Property

position: fixed;

- Like fixed excel bar on the top, it stays on the screen when scrolling down

position: static;

- It sticks on the webpage, disappears when scrolled down.
- default setting

position absolute;

- positioning based on relative position of body.
- Else, it will position based on HTML as a whole

# 3-7. Flexbox

- practice with flexbox with the link below
  **http://flexboxfroggy.com/#ko**

- display:flex; to initialize flex function.
- you talk to the father, and that guy is flex.
- you move children
- Flexbox is easily aligning items, just like powerpoint options
- flex-direction: row; or flex-direction: column;
- Flexbox is only applied on father.
- flex-wrap: wrap; is breaking line (on mobile) and moves box onto the next line, keeping the size of the box.
- flex-wrap: no-wrap; is default. shrinking box, keeping the line

# 3-8. CSS Selectors and Pseudo Selectors

- Selecting element without tag name, class name, id.
- pseudoselector is selector, but not element
- .box:nth-child(3n+2)
- for tutorial for "nth-child and nth-of-type", refer to http://www.topdesignagencies.com/nth-test/

# 3-9. Element States with CSS

- hover
- active
- focus
- visited