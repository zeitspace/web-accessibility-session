# Activity 2 - Possible improvements

The web page provided as part of this activity had several accessibility issues. Here we describe why the initial design and implementation wasn't ideal, and some possible solutions.

## Head section

* The page title should be more descriptive so users of screen readers know where they are.

## General

* The banner, header, nav links, main, article, footer, and aside containers (recent articles, sign up) should use HTML elements or ARIA roles for landmarks.
* Complementary elements like the asides should also have `aria-label` or `aria-labelledby` for landmark navigation; otherwise they only show up as "complementary" in menus.
* Sizings in CSS should use `rem` or `em` instead of `px` to support those using larger font sizes.

## Header

* Don't use `aria-labels` to correct screen reader pronunciation (e.g., Zeitspace). Users are used to it and it can screw up braille readers.
* "The Zeitspace Post" can be a heading to help screen readers.
* The wing photos are decorative and should be hidden or use CSS backgrounds.

## Navigation
* aria hiding the "Read more about:" text removes context for screen readers.
* Links should be identified by more that just colour; use underline, arrow, bold, etc.).
* Adding clearer aria-labels for the links may be beneficial.
* The `row-reverse` flex-direction makes the tab order backwards.

## Return link

* Linking to a new page should b done with `<a>`, `<button>` is for actions, using the wrong tag can confuse screen readers.
* Links should be identified by more that just colour (use underline, arrow, bold, etc.)
* Contrast is too low.
* Should have a more descriptive `aria-label`.
* Avoid justifying text left or right. Instead, use start or end to support right to left languages.

## Hero image
* The `alt` text should describe the content of the image, not its purpose.

## Article
* All headings should use heading elements (`h1`, `h2`, etc.). Surveys have found that the most common way for users of screen readers to start navigating a webpage is using headings.
* The contrast on all headings is too low.
* The contrast on the author section is too low
* The article should use `<p>` tags instead of `<br>` tags; it styles automatically, and allows screen reader users to read paragraph by paragraph.
* Links are only denoted by colour. This can be difficult to identify for those with low vision or colour blindness.

## Recent articles aside
* Not using `tabindex="-1"` on the links surrounding the images means that tabbing through the recent articles first highlights the image, then the article title-this is inconvenient for keyboard users.

## Subscription aside
* This block is placed before the article in the document, so it creates a strange tab order despite being correctly displayed.
* Using `tabindex="1"` may make selecting the subscription form faster for keyboard and mouse users, but it creates an odd tab order for keyboard-only users.
* Representing the sign up button as an image means that screen readers have no idea what it says.
* Furthermore, representing the button as an `<img>` (not a `<button>`) makes its purpose even more elusive.
* The form should be inside a `<form>` element
* There should be a `<label>` element for the form label, this allows screen readers to know the purpose of the input.
