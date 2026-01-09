Fungies Website

Fungies is a modern, responsive website about mushroom foraging.
Built with HTML5 and CSS3, organized using CSS layers for reset, base, layout, utilities, and components.

Live Demo:
https://fungies.netlify.app/

Tech Stack

HTML5 semantic markup

CSS3

CSS Variables / Custom Properties for colors, fonts, spacing

CSS Grid & Flexbox for layout

@layer reset, base, layout, utilities, components for structured styling

Responsive design (mobile-first)

Accessibility enhancements:

:focus-visible for interactive elements

.visually-hidden for screen readers

Components & Utilities

Components

Header: .site-header with .primary-navigation

Hero Section: .hero + .hero__title

Card: .card + .card__title

Button: .button with hover & focus-visible

Footer: .site-footer + .site-footer__title

Utilities

.text-center, .text-brand, .text-high-contrast

.background-light, .background-dark, .background-accent

.font-size-sm, .font-size-md, .font-size-lg

.flow > * + * – vertical spacing between elements

.grid-flow – grid layout with configurable gap

.visually-hidden – hides content visually but remains accessible to screen readers

Layout Helpers

.equal-columns – equal height columns with configurable gap and alignment

.wrapper – container with max-width and padding

Accessibility

Hover and focus states for buttons and links

.visually-hidden for accessibility text

Mobile-first and keyboard-friendly navigation

Live Link

https://fungies.netlify.app/

Notes

Uses a clean layered CSS structure:

@layer reset – normalize browser styles

@layer base – typography, colors, global styles

@layer layout – containers, spacing, columns

@layer utilities – reusable utility classes

@layer components – header, hero, card, button, footer

Fully responsive and easy to maintain

Suitable for showcasing CSS skills in a portfolio
