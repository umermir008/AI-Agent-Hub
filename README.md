AI Agent Hub

A modern, enterprise-grade front-end interface for an AI automation SaaS platform. This project features a clean, "Apple-meets-Stripe" aesthetic with a focus on usability, scalability, and performance.

🚀 Overview

AI Agent Hub is designed as a landing page and dashboard preview for a platform that allows users to build, manage, and scale autonomous AI agents. The interface is fully responsive, accessible, and features smooth micro-interactions.

Key Features

Responsive Design: Mobile-first approach using CSS Grid and Flexbox.

Dark/Light Mode: Robust theming system using CSS variables, with automatic system preference detection and a toggle switch.

Interactive Elements:

"Live" CSS-only dashboard preview in the Hero section.

Animated workflow connectors simulating data flow.

Scroll-triggered fade-up animations using Intersection Observer.

Monthly/Yearly pricing toggle with price updates.

Modern Styling:

Glassmorphism effects on the navigation bar.

Refined typography using the Inter font family.

Phosphor Icons for consistent iconography.

🛠️ Tech Stack

HTML5: Semantic structure.

CSS3: Custom properties (variables) for theming, complex animations (cubic-bezier easing), and responsive layouts. No external CSS frameworks (like Tailwind or Bootstrap) were used; everything is custom-written for maximum control.

JavaScript: Vanilla JS for logic (theme toggling, scroll observation, mobile menu).

Assets:

Phosphor Icons (via CDN)

Google Fonts (Inter)

📂 Project Structure

All code is contained within a single index.html file for portability and ease of compilation, following the "Single-File Mandate".

<head>: Contains meta tags, font imports, and the <style> block defining CSS variables and rules.

<body>:

navbar: Sticky navigation with glass effect.

hero: Main landing area with the 3D dashboard preview.

features: Grid layout of core platform capabilities.

workflow: Visual step-by-step animation.

pricing: Pricing cards with toggle logic.

footer: Links and copyright info.

<script>: Handles DOM manipulation and events.

🎨 Customization

The design relies heavily on CSS variables defined in the :root and [data-theme="dark"] blocks. You can easily change the brand colors or spacing by editing these values:

:root {
    /* Brand Colors */
    --brand-primary: #2563EB;
    --brand-accent: #059669;

    /* Spacing & Radius */
    --radius-md: 12px;
    
    /* Animation Physics */
    --ease-apple: cubic-bezier(0.16, 1, 0.3, 1);
}


🚀 How to Run

Simply open index.html in any modern web browser.

No build step or server is required.

📄 License

This project is a design template and is free to use for personal or commercial projects.
