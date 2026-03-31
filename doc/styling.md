
# Styling Guidelines

## Purpose

The purpose of this example project is to introduce the class to CI/CD and infrastructure as code through several exploration assignments.

This document serves as the technical brand specification for developers and designers building applications for Oregon State University.

## Styling

Since this is an Oregon State University project, style all user interfaces with the OSU colors and fonts and identity as described in this document.

## Brand Positioning

With steadfast determination, people from Oregon and around the globe gather to explore the unknown and solve today’s most pressing issues. Together, we innovate to deliver far-reaching solutions that guarantee the prosperity of our state and world, enriching the lives of all people. We transform learners into leaders. We are unwavering and accountable, because the world counts on us for a healthier, more sustainable future.

## 1. Core Color Palette (Heritage)

The primary palette must dominate the UI to maintain brand recognition.

| Element          | Hex Code   | RGB             | CMYK           | Usage                          |
|:-----------------|:-----------|:----------------|:---------------|:-------------------------------|
| **Beaver Orange**| `#D73F09`  | `215, 63, 9`    | `0, 80, 100, 0`| Action buttons, links, accents |
| **Paddletail Black** | `#000000` | `0, 0, 0`      | `0, 0, 0, 100` | Primary text, headers, nav     |
| **Bucktooth White** | `#FFFFFF` | `255, 255, 255`| `0, 0, 0, 0`   | Backgrounds, cards, negative space |

### Secondary Palette (Accents)

Use these sparingly for data visualization, alerts, or category distinctions.

* **High Tide (Teal):** `#00859B`
* **Stratosphere (Blue):** `#006A8E`
* **Pine Stand (Green):** `#4A773C`
* **Luminance (Yellow):** `#FFB500`
* **Crater (Warm Gray):** `#8E9089`

---

## 2. Typography

For digital applications, accessibility and legibility are prioritized.

### Primary Typeface: Open Sans

Used for body copy, UI labels, and general interface text.

* **Weights:** Regular (400), Semi-Bold (600), Bold (700).
* **Source:** Google Fonts (Free/Open Source).

### Serif Accent: Georgia

Used for editorial headers or high-level storytelling sections.
* **Usage:** H1 or H2 titles only. Do not use for long-form body text.

### Headings (CSS Reference)

```css
h1, h2 {
  font-family: 'Georgia', serif;
  font-weight: 700;
  color: #000000;
}

body, button, input {
  font-family: 'Open Sans', sans-serif;
  font-weight: 400;
  color: #000000;
}

a {
  color: #D73F09;
  text-decoration: underline;
}