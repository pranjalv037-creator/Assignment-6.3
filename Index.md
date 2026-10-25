Assignment 6.3 — Overflow & Layout Fixing

Aim

To understand CSS overflow properties and fix layout issues caused by content exceeding a container's dimensions.

CSS Overflow Properties

1. Visible: Extra content appears outside the container.
2. Hidden: Extra content is clipped and does not appear outside the container.
3. Auto: Scrollbars appear when the content overflows and scrolling is needed.
4. Scroll: Scrolling is enabled, and scrollbars are generally displayed even when they are not needed.

Fixed-Size Container

A container with a fixed height of "100px" is used to demonstrate how content behaves when it exceeds the available space.

Overflow Issue and Fix

Long text or URLs can extend beyond a container and break the page layout.

The issue is fixed using:

- "max-width: 600px" to limit the container's width.
- "box-sizing: border-box" to include padding and borders within the specified dimensions.
- "overflow: auto" to allow scrolling when content exceeds the container.
- "overflow-wrap: anywhere" to wrap long text within the available width.

Files Included

- "index.html" — HTML examples of overflow properties.
- "style.css" — CSS styling and overflow fixes.
- "overflow-screenshot.png" — Screenshot showing the overflow examples and corrected layout.
