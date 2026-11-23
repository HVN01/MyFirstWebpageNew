# CSS-week2-HW2 — Exploring Vietnam

This repository is a copy of `repository1` updated for **Homework 2** of **Introduction to CSS3** (Web Design for Everybody Specialization), adding Skip to Main Content links, descendant selectors, CSS Grid, and Flexbox layouts.

## Repository Structure

```text
repository2/
├── README.md
├── index.html
├── places.html
├── gallery.html
├── css/
│   └── style.css
└── images/
    ├── ha-long-bay.jpg
    ├── hoi-an.jpg
    └── sapa.jpg
```

## Pages

- `index.html` — Home page with working "Skip to Main Content" link, navigation bar image, and introduction to Vietnam's top destinations.
- `places.html` — Must-Visit Places page with working "Skip to Main Content" link and a two-column `.grid` image layout.
- `gallery.html` — Photo Gallery page with working "Skip to Main Content" link and a `.flex` image layout.

## CSS Styling Summary (`css/style.css`)

- Commented out the Homework 1 `li` styling rule.
- Styled `nav` with `display: inline-block;` and `width: 80%;`.
- Styled `nav img` using a descendant selector with `width: 10%;`.
- Styled `.grid` with `display: grid;`, `grid-template-columns: 40% 40%;`, `justify-content: space-around;`, `align-items: center;`, and `row-gap: 20px;`.
- Styled `.grid img` with `width: 100%;` without affecting images in `.flex`.
- Styled `.flex` with `display: flex;`, `flex-wrap: wrap;`, and `justify-content: space-around;`.
