
Design Document: Photo Blog Homepage
Overview

This project is a responsive urban photography blog homepage, designed for the BCIT MDIA-1190 Web Technologies Assignment 2. The site uses modern CSS techniques—Flexbox, CSS Grid, responsive units, custom typography, media queries, transitions, and keyframe animations—to provide an engaging and accessible experience on all devices.
1. Navigation Bar (Flexbox)

    Layout: Horizontal navigation bar at the top using Flexbox.
    Content: At least three links (e.g., Home, Posts, Newsletter).
    Behavior:
        Remains fixed at the top as the user scrolls (sticky/fixed positioning).
        Well-designed with clear, interactive styling.
    Interactivity: CSS transitions for smooth hover effects on links.

2. Blog Post Previews (CSS Grid)

    Layout:
        Below navigation, display at least six blog post preview cards in a CSS Grid.
        Cards include: post title, short excerpt, and a "Read More" link.
    Responsiveness:
        Grid displays 2–3 columns on desktop.
        Stacks to a single column on screens 600px wide or less (using media queries).
    Animation:
        Each card animates into view on page load using a CSS keyframe (e.g., fade in and slide up).

3. Single Blog Post Page

    Structure: Separate HTML page for a single post.
    Layout:
        Uses CSS Grid with named grid areas.
        Includes: header, main content, sidebar (e.g., author info or related posts), and footer.
        Layout defined with grid-template-areas.
    Styling:
        Responsive units for spacing and font sizes.
        Custom typography for readability.
        At least one media query for mobile layout.
        At least one CSS transition or animation for interactivity.

4. Responsive Units

    Usage:
        Use %, em, rem, vw, vh for margins, paddings, font sizes, and widths.
        Avoid fixed pixel values where possible.

5. Custom Typography

    Fonts:
        Use at least one custom font from Google Fonts or Adobe Fonts (for headings or body).
    Readability:
        Apply thoughtful font sizing, line height, font weight, and letter spacing.

6. Media Queries

    Mobile Layout:
        At least one media query for screens ≤600px wide.
        Blog post cards stack vertically on small screens.
        Adjust navigation and grid as needed.

7. Transitions

    Effects:
        CSS transitions on navigation links and/or "Read More" links.
        Example: smooth color or underline animation on hover.

8. Keyframe Animation

    Effects:
        Animate blog post cards as they appear on page load.
        Example: fade in and slide up with a slight delay for each card.

9. Version Control

    Git:
        Initialize a git repository for the project folder.
        Make regular, meaningful commits throughout development.
        Push the finished project to a public GitHub repository.
        Ensure the repository contains commit history and is linked in the README.

Deliverables

    Project folder with HTML, CSS, and asset files (images, fonts, etc.).
    README.md with:
        Brief project description.
        Instructions for viewing the blog homepage.
        Link to the GitHub repository.
    Public GitHub repository with project files and commit history.

Tips

    Use Google Fonts for easy custom typography.
    Apply media queries for responsive design.
    Use transition and :hover for interactive elements.
    Use @keyframes and animation for card entrance effects.
    Commit and push code regularly.

