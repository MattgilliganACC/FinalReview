## Question A (40% credit):

In CSS3, how would you select:

  - Every `<a>` element whose `href` attribute value begins with “https”.
  - Every `<a>` element whose `href` attribute value ends with “.pdf”.
  - Every `<a>` element whose `href` attribute value contains the substring “css”.

## Question B (30% credit):

What is the purpose of the z-index and how is it used? What possible values does the z-index take (e.g. one of the is "auto")?

## Question C: (30% credit) 

Explain the difference between `visibility: hidden` and `display: none` in CSS3.



A:
a[href="https"]
a[href$=".pdf"]
a[href*="css"]

B.
The z-index property specifies the stack order of an element; used to pull a page together for any non-static box.
It will have integer values.

C:
Hidden gives an element space on the page but it isn't seen, whie None doesn't appear at all and no space is allocated for it, though it can still be interacted with via the DOM.
