# The Centre Cannot Hold Website Redesign

Date: April 21, 2026

## Overview

This repository contains a single-page public project website for the accessibility-led redesign of **The Centre Cannot Hold**, a Postmarginal digital portal. The page presents the project for a non-specialist audience by combining a short project summary, client context, research findings, moodboards, user testing outcomes, a Figma prototype link, and visual documentation of the design outcome.

The site is built as a simple static website so it can be deployed easily through GitHub Pages.

## Motivation

The Centre Cannot Hold already has a strong artistic identity: dark visual atmosphere, immersive pacing, layered imagery, and a non-linear approach to encountering artists and creative work. The redesign project was motivated by the need to preserve that experiential quality while making the website clearer, more readable, and more accessible.

Research and user testing showed that visitors needed stronger context, more predictable navigation, clearer page hierarchy, readable typography, and better accessibility support. The redesign responds to those needs without removing the original site's sense of discovery.

## Purpose

The purpose of this website is to document and communicate the redesign project clearly. It explains:

- Who the client is: The Centre Cannot Hold, directed by Peter Farbridge.
- Why the redesign was needed.
- How accessibility, WCAG goals, and artist-centered navigation shaped the work.
- What moodboards, prototypes, and user testing contributed to the final direction.
- Where viewers can access the Figma prototype and visual design documentation.

## Website Content

The page includes these main sections:

- **Client**: Introduces The Centre Cannot Hold and Peter Farbridge.
- **Short Summary**: Summarizes the redesign goals and outcomes.
- **Moodboards**: Shows three visual process boards. Each moodboard opens in a larger in-page modal.
- **Research**: Summarizes accessibility needs from project notes and interviews.
- **Process**: Explains moodboards, low fidelity work, component thinking, and design direction.
- **Accessibility Lessons**: Highlights screen reader, keyboard, ARIA, and prototype structure considerations.
- **User Testing**: Presents clearer testing findings with icons for each tested area.
- **Figma Prototype Link**: Links to one final prototype in Figma.
- **Design Outcome**: Summarizes the final direction and embeds the redesign deck.

## Design Direction

The visual style references The Centre Cannot Hold through:

- A dark green and yellow palette.
- Frosted glass interface elements.
- The Centre Cannot Hold logo.
- Mycelium imagery in the landing and Design Outcome sections.
- IM Fell Great Primer for title elements.
- Simple, mostly static interactions to support WCAG-friendly readability.

## Accessibility Considerations

The website prioritizes:

- Semantic section structure.
- Clear navigation labels.
- Visible focus states.
- Larger body text.
- Accessible moodboard modal behavior.
- Descriptive image alt text.
- Reduced animation and simple interaction patterns.
- Text contrast and readable spacing.

The moodboard modal can be closed with the visible **Close** button, the Escape key, or by clicking outside the modal panel.

## Local Preview

Run the local server from the repository root:

```powershell
node server.mjs
```

Then open:

```text
http://127.0.0.1:5173
```

## GitHub Pages Deployment

This project is intended to deploy from the `PostMarginalWebsite484` branch using GitHub Pages.

Recommended GitHub Pages settings:

- Branch: `PostMarginalWebsite484`
- Folder: `/`

## Key Files

- `index.html`: Main website content and modal behavior.
- `styles.css`: Visual design, responsive layout, and accessibility styling.
- `server.mjs`: Small local static server.
- `assets/images/`: Moodboards, logo, and mycelium imagery.
- `assets/documents/`: Embedded redesign PDF documentation.

## Credits and Sources

- Client/project inspiration: The Centre Cannot Hold.
- Director: Peter Farbridge.
- Project context: Postmarginal collaboration and TCCH UX Accessibility notes.
- Moodboards: Extracted from project documentation.
- Mycelium imagery: Public-domain Wikimedia Commons source.
- Icons: Inline SVG icons based on open-source outline icon conventions.
