----------------------------------------------------
TITLE:  Websites by Joann
-----------------------------------------------------
DESCRIPTION OF PROJECT

This site contains a series of pages to provide information about the author, Joann Cahill, and highlight several websites that demonstrate web development skills of the author.  The site contains several pages:

1.	Portfolio – the page contains links to sites developed by the author
2.	About – the page includes information about the author and her background
3.	Contact – the page includes a form with which the user can contact the author to provide feedback or learn more about the site

-----------------------------------------------------

TECHNOLOGIES USED

The site is written using semantic HTML and CSS styling.

-----------------------------------------------------

ACCESSIBILITY

The site was evaluated using the following tools:

•	WAVE Web Accessibility Evaluation Tool (https://wave.webaim.org/). All pages passed the contrast ratio test with a ratio of 8:59:1.  Some pages returned errors which were addressed below.

•	Colbinder: Coblis Color Blind Simulator (https://www.color-blindness.com/coblis-color-blindness-simulator/)  All pages passed the contrast ration test with a ration of 8:59:1. The pages also did well for color blindness.  Each test was applied and, although the type of color impairment impacted the colors displayed on the page, the user could view details and text on the page.  

•	Review other of A11Y standards 

The following summarizes the findings of this evaluation and the actions taken to improve the accessibility of the website:

•	Portfolio page:  9 errors were reported.  These errors related to missing alternative text on linked images, used for each portfolio site.   To resolve the nine errors, I added alternative text to describe the icon and advise them that it included a link to the specified site (e.g. “icon with link to XXX Site”)

•	About Page: Contrast errors were reported on the About page that related to the header.  This is identical to the header on the other pages which had no errors.  I could not find the font colors, noted in the WAVE code provided, in my CSS.  This appeared to be a false error.

•	Form:  No errors were reported on the forms page.

Other changes made to improve the accessibility of the site:

a.	Added hidden link to allow user to skip to main content of the page.

b.	Clickable elements:  Each site, included in the home page, is displayed as a figure with a fig caption.  When displayed the element is large, spaced properly and provides sufficient size for users to click the link.  However I noticed a problem when users clicked on the bottom third of the site box in that the link was not triggered.  The href was on the icon for the site.  When the user clicked on the upper portion of the site box the site opened as expected.  However, when the user clicked on the bottom portion of the site box (e.g. where the fig caption is located) nothing happened. I added the href to the fig caption in addition to the img element so that the link triggers regardless of where in the box the user clicks.

c.	Screen Reader Notation:  Added text to the site links, that can be read only by a screen reader, to advise the user that the link will open in a new tab.

d.	Autofocus was used on the first form field on the Contact page to draw users to the first field needing input.		
