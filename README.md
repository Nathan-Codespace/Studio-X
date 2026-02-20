# Studio X - Creative Digital Solutions

A modern, minimal, and editorial-style landing page built to practice advanced CSS positioning and typography.

---

## Project Overview

This project is a concept for a creative studio landing page. The primary objective was to achieve a high-end, clean aesthetic through the use of serif typography and a structured, minimal layout.

---

## Tech Stack

- **HTML5:** Semantic structure.
- **CSS3:** Custom fonts, absolute positioning, and layout management.
- **Google Fonts:** Integration of Cormorant, Antic Didone, and DM Serif Display.

---

## What I Learned

In this project, I focused on several key frontend concepts:

- **Advanced Positioning:** Implementing `position: absolute` and `transform: translate` to place decorative elements, such as the large background "X", without disrupting the document flow.
- **Typography Design:** Learning how to pair different serif fonts to create a professional, magazine-like visual hierarchy.
- **Layout Organization:** Utilizing containers to manage white space and ensure proper alignment across various sections.

---

## Challenges and Mistakes

- **Positioning Issues:** I initially struggled with the large background element. I discovered that using percentages for `top` and `left` in combination with the `transform` property is a more reliable method for centering elements.
- **Layout Flow:** I used `display: inline-block` for the feature cards. I realized this can lead to unexpected spacing issues between elements, and I intend to transition to Flexbox for more robust layouts.
- **Unit Selection:** I noticed that using fixed units like `rem` for large horizontal margins can cause layout breaks on smaller screens. This highlighted the importance of responsive design and fluid units.
