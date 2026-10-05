# Mahlodi Bakehouse Website

## Student Information

Name: Malete Raseroka
Student Number: ST10518036
Module: WEDE5020 - Web Development (Introduction)
Assessment: Portfolio of Evidence - Part 1 and Part 2

## Project Overview

Mahlodi Bakehouse is a fictional bakery created for the Web Development (Introduction) academic project. The website gives customers information about the organisation, its products, the enquiry process and contact details.

Part 1 built the HTML foundation. Part 2 adds CSS styling and responsive design.

## Website Goals and Objectives

1. Provide information about Mahlodi Bakehouse.
2. Display products and services.
3. Allow customers to submit enquiries.
4. Provide contact information.
5. Create an easy-to-navigate website.
6. Establish a professional online presence.

## Key Features

- Homepage, About, Products, Enquiry and Contact pages
- Navigation between all pages
- Semantic HTML5 structure
- External stylesheet with a warm bakery colour scheme
- Responsive layout for desktop, tablet and mobile
- Organised file and folder structure

## Sitemap

Mahlodi Bakehouse
- Home
- About
- Products
- Enquiry
- Contact

## Folder Structure

```
mahlodi-bakehouse/
  css/style.css
  images/
  js/
  research/
  screenshots/
  index.html  about.html  products.html  enquiry.html  contact.html
  README.md
```

## Part 1 Details

Organisation selection, project proposal, target audience, objectives, content research, image sourcing, sitemap, file organisation, initial HTML structure and navigation.

## Part 2 Details

- External stylesheet (`css/style.css`) linked to all five pages
- CSS reset and base styles (font family, size, colour scheme, spacing) using CSS variables
- Typography scale in `rem` units; Georgia headings and system sans-serif body text
- Flexbox for header, navigation and forms; CSS Grid for the card layout and homepage hero (`grid-template-areas`)
- Visual styles with `color`, `background-color`, `border`, `box-shadow`, and `:hover`, `:focus`, `:active` states
- Cascading: global element styles, then class and attribute selectors that override them for specific cases
- Responsive design with breakpoints at 1023px (tablet) and 767px (mobile), relative units (`rem`, `%`) and responsive images (`srcset`, `sizes`, `picture`)
- Tested with browser developer tools

## Responsive Design Screenshots

Desktop (1440px): ![Desktop](screenshots/desktop.png)

Tablet (768px, iPad): ![Tablet](screenshots/tablet.png)

Mobile (iPhone SE / Galaxy S20): ![Mobile](screenshots/mobile.png)

## Changelog

### Version 2.0 (Part 2)

Feedback corrections from Part 1
- REPLACE THIS LINE with each piece of lecturer feedback and exactly what you changed.
- Moved the `img` elements that were placed after the closing `</html>` tag into the page content in `index.html` and `products.html`.
- Corrected image file names with a double extension (for example `bakery-hero.jpg.jpg` to `bakery-hero.jpg`) and updated all `src` paths.
- Added `width`, `height` and `loading` attributes to images.
- Removed duplicated README content and updated the Student Information section.

New in Part 2
- Created `css/style.css` and linked it in every page.
- Added CSS reset, variables, base styles and typography.
- Built the desktop layout with Flexbox and CSS Grid.
- Added colours, borders, shadows and interactive states.
- Added media queries, relative units and responsive images.
- Added `aria-current` on the active nav link and visible focus outlines.
- Added a styled enquiry form, contact table and embedded map.

### Version 1.0 (Part 1)

- Created project folder
- Created initial HTML pages
- Added navigation
- Added semantic HTML structure
- Added website content
- Added enquiry form
- Added contact page

## References

Mozilla Developer Network (MDN). n.d. HTML elements reference. [online] Available at: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements [Accessed 1 September 2026].

Mozilla Developer Network (MDN). n.d. Structuring documents. [online] Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents [Accessed 1 September 2026].

Pexels. 2026. Pexels License. [online] Available at: https://www.pexels.com/legal-pages/license/ [Accessed 1 September 2026].

Pexels. 2026. What is the license of the photos and videos on Pexels? [online] Available at: https://help.pexels.com/hc/en-us/articles/360042295174-What-is-the-license-of-the-photos-and-videos-on-Pexels [Accessed 1 September 2026].

Mozilla Developer Network (MDN). n.d. CSS grid layout. [online] Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout [Accessed 5 October 2026].

Mozilla Developer Network (MDN). n.d. Using media queries. [online] Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries [Accessed 5 October 2026].

Mozilla Developer Network (MDN). n.d. Responsive images. [online] Available at: https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images [Accessed 5 October 2026].
