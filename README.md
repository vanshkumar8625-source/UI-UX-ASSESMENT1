# UI-UX-ASSESMENT1
Question1. Product Card Grid (5 marks)
Create HTML/CSS for e-commerce page:
- Header: "Shop Products" `<h1>`
- Grid of 4 product cards (`<article>`): Image placeholder (`<div class="img">`), title, price (`<span class="price">$19.99</span>`), "Buy Now" button.
- CSS: `display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem;`
- Cards: Shadow, hover darken via background color change, or use `border-width` hover instead.

 Question2. Restaurant Menu Page (7 marks)
Full page for "Delhi Dhaba Menu":
- `<nav>`: Home, Menu, Contact
- `<main>`: `<section>` for Appetizers, Mains (2 each)
- Use nested lists `<ul>` for items with prices.
- CSS: Flex nav horizontal. Two-column grid for sections. Price badges styled round.

Question3. Event Landing Page (8 marks)
"Tech Meetup 2026" page:
- Hero: Event name `<h1>`, date/time `<p>`, "Register" button
- Features grid: 3 boxes (Speakers, Venue, Agenda)
- Footer: Sponsors logos (placeholders)
- CSS: Full-height hero flex center. Features `display: grid; grid-template-columns: repeat(3, 1fr);`

Question4. Blog Homepage (10 marks)
Simple blog:
- Header with site title + search input box
- 3 blog posts: `<article>` with title, excerpt, "Read More" link, author/date
- Sidebar: Categories list
- CSS: Flex layout (main 70%, sidebar 30%). Posts as vertical stack.

Question5. Pricing Comparison Page (10 marks)
SaaS pricing tiers:
- `<h1>Choose Your Plan</h1>`
- 3 pricing cards: Basic ($9/mo), Pro ($29/mo), Enterprise ($99/mo)
- Each: Features checklist `<ul>`, price highlight, "Sign Up" button
- CSS: Central grid `grid-template-columns: repeat(3, 1fr);`. Pro card featured (larger height via padding).
