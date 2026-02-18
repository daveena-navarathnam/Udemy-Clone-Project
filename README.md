Udemy Clone – Responsive Frontend Implementation
Overview

This project is a fully responsive front-end clone of the Udemy homepage, built using semantic HTML5 and modern CSS3. The goal of this project was to replicate a real-world production layout while applying responsive design principles and scalable CSS architecture.

The project focuses on layout structuring, Flexbox implementation, component organization, and multi-section footer design.

Live Demo

GitHub Pages Deployment:
👉 https://daveena-navarathnam.github.io/Udemy-Clone-Project/

Tech Stack

HTML5 (Semantic Structure)

CSS3

Flexbox

Media Queries

Responsive Layout Techniques

Google Fonts (Inter)

Font Awesome Icons

Git & GitHub for version control

Key Features
1. Responsive Navigation Bar

Multi-section navigation layout

Integrated search input

Interactive hover dropdown (My Learning)

Responsive behavior:

Selective content hiding at smaller breakpoints

Layout adjustments for tablet and mobile

2. Hero Section

Full-width promotional banner

Positioned content overlay using position: absolute

Responsive fallback (overlay hidden on smaller screens)

3. Course Sections

Two primary sections:

Recommended Courses

Trending Courses

Each section:

Uses Flexbox-based card layout

Maintains consistent spacing with gap system

Adjusts dynamically using flex-basis

Mobile-first responsive resizing

Responsive behavior:

Desktop: 5 cards per row

Tablet: 4 cards per row

Mobile: 2 cards per row

4. Topics Section

Flexible tag-based layout

Uses flex-wrap and proportional sizing

Hidden at smaller screen widths to improve UX

5. Multi-Level Footer Architecture

The footer is divided into four structured sections:

Promotional call-to-action section

Skill categories section

Company & legal navigation section

Bottom utility bar (logo, language, cookies)

Techniques used:

Nested Flexbox containers

Spacing control using gap

Responsive column stacking

Column reordering using flex-direction: column-reverse on mobile

Responsive Strategy

Two primary breakpoints:

@media (max-width: 800px)
@media (max-width: 600px)


Adjustments include:

Hiding non-essential navigation elements

Changing card grid proportions

Removing overlay components

Stacking footer content vertically

Optimizing spacing for small screens

Project Structure
Udemy-Clone-Project/
│
├── index.html
├── style.css
├── sale-image/
├── recommended-images/
└── README.md

Design & Layout Approach

Component-based class naming

Consistent spacing system

Flexbox-driven layout control

Hover states for interactive elements

Clean visual hierarchy using font weights and spacing

Challenges Solved

Managing Flexbox behavior across multiple screen sizes

Preventing layout collapse during responsive adjustments

Structuring a complex multi-column footer

Implementing hover dropdown using only CSS

Maintaining consistent card alignment across sections

Future Improvements

Implement mobile hamburger navigation

Improve accessibility (ARIA roles, better semantic grouping)

Refactor layout to partially use CSS Grid

Add JavaScript for enhanced interactivity

Improve performance with image optimization

Author

Daveena Navarathnam
Frontend Developer (In Progress)
Strengthen frontend development fundamentals
