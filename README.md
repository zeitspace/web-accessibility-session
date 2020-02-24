# The Good, the Bad, and the Ugly of Web Accessibility

Welcome to the **The Good, the Bad, and the Ugly of Web Accessibility** Zeitspace Session!
Let's make sure you're all set up.

## Setup

* Download the project files in this Github repository, by clicking the `Clone or Download` and then `Download ZIP`. This file contains all the materials for this workshop.

<img src="screenshots/github download.png" width="300">

* Extract the ZIP file.

#### Optional tools
Adobe XD is a design and prototyping tool. It is not required for this workshop but you are welcome to use it. We provide Adobe XD assets and corresponding flattened PNG images where appropriate. A trial of Adobe XD can be [downloaded from the Adobe site](http://creative.adobe.com/products/download/xd).

The XD document uses the Fira Sans typeface family as part of the webpage design. You can download them from the [Google Fonts site](https://fonts.google.com/specimen/Fira+Sans). Without this font, the XD design and text spacing will be off.

## Activity 1

The goal of this activity is to learn about document structure as it relates to accessible design. In particular, we'll explore the use of *landmarks* as a way of describing blocks of content on a web page.

#### Materials

We'll provide:

* physical printouts of several web pages, and
* images of those web pages (as PNG and ganged-up PDF) in case you'd like to try the exercise again later.

#### Tasks

Using the physical printout, think about the different sections of the web page. Are there clear separations between different types of content? Can the sections you identify be assigned a landmark role?

* Using a marker, draw lines around the different content sections you've identified.
* Assign each section one of the [eight landmark roles](https://www.w3.org/WAI/GL/wiki/Using_ARIA_landmarks_to_identify_regions_of_a_page#Description).

## Activity 2

The goals of this activity are to search for, identify, and explore possible solutions for accessibility issues within a web site and its design.

#### Materials

* Adobe XD document. This contains the design of the web page, including general layout and styling.
* Web page (HTML, images, etc.). Open up `Zeitspace Post.html` from the `Activity 2` directory.

#### Tasks

In many cases, accessibility issues span design and development work. Using the assets provided:

* identify accessibility issues, and
* decide how to solve them in the design, the implementation, or both.

#### Wrap-up

Within the `Improvement` directory, there is an improved web page. The `CHANGES.md` file describes some of the issues that were identified and addressed.

---

## Resources
* Authoritative resources
  * [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/). The W3C work related to web accessibility, including a [quick reference](https://www.w3.org/WAI/WCAG21/quickref/) and [full breakdown](https://www.w3.org/TR/UNDERSTANDING-WCAG20/Overview.html).
  * [Accessibility for Ontarions with Disabilities Act (AODA)](https://www.aoda.ca). Related content includes [how to make websites accessible](https://www.ontario.ca/page/how-make-websites-accessible) and [how to fill out an accessibility compliance report](https://www.ontario.ca/page/completing-your-accessibility-compliance-report).
* Tools
  * [AChecker](https://achecker.ca/checker/index.php). A web-based accessibility checker that can analyze an existing web site. Nicely ties any findings to WCAG 2.0 guidelines.
  * [ARC Toolkit](https://www.paciellogroup.com/toolkit/). Automated accessibility evaluation tool, available as a Chrome extension. Integrates into the Chrome developer tools.
  * [aXe plugin](https://www.deque.com/axe/). Chrome plugin for automated web accessibility testing.
  * [Stark](https://getstark.co/index.html). Plugin for Adobe XD, Figma, and Sketch intended to help designers with contrast and colour blindness.
  * [WAVE](https://wave.webaim.org/extension/). Chrome and Firefox plugins for automated web accessibility testing.
* Content
  * [18F](https://accessibility.18f.gov) is the digital design group within the US federal government. They have a useful [accessibility checklist](https://accessibility.18f.gov/checklist/).
  * Apple's [Human Interface Guidelines for Accessibility](https://developer.apple.com/design/human-interface-guidelines/accessibility/overview/introduction/).
  * Canadian Digital Service (CDS) [accessibility handbook](https://digital.canada.ca/a11y/). CDS is the digital project group within the federal Canadian government.
  * Google has some accessibility content, including [an introduction to web accessibility](https://developers.google.com/web/fundamentals/accessibility), the [Material Design section on accessibility](https://material.io/design/usability/accessibility.html), and an article on [conducting an accessibility review](https://developers.google.com/web/fundamentals/accessibility/how-to-review?utm_source=lighthouse&utm_medium=devtools).
  * Microsoft's [accessibility portal](https://www.microsoft.com/en-us/accessibility).
  * Ontario Digital Service (ODS) [article about user testing and accessibility](https://medium.com/ontariodigital/accessibility-user-testing-heres-what-we-learned-277d2aeb4af8). ODS is the digital project group within the Ontario provincial government.
  * [WCAG 2.0 Level A](https://github.com/zeitspace/web-accessibility-session/blob/master/Resources/WCAG%202.0%20Level%20A%20Checklist.pdf) and [WCAG 2.0 Level AA](https://github.com/zeitspace/web-accessibility-session/blob/master/Resources/WCAG%202.0%20Level%20AA%20Checklist.pdf) checklists, created by Zeitspace based on W3C WCAG resources.
  * [WebAIM](https://webaim.org). Collection of accessibility resources (including some [good examples of image alt text](https://webaim.org/techniques/alttext/)). WebAIM, a non-profit affiliated with the University of Utah, makes WAVE, listed above.
* Presentations
  * [Accessibility is Usability](https://www.confabevents.com/videos/accessibility-is-usability). Talk by Sarah Richards from Confab 2019.
