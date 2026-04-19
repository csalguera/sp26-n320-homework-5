# WaveForm Landing Page — GSAP Animation (Homework 5)

## What This App Is

This project is a single-page music startup landing page called WaveForm. It showcases a product concept through animated storytelling as users move through the page sections.

The page experience includes:

1. A hero section that introduces the brand and core message.
2. A stats section that presents growth metrics with animated counters.
3. A features section that highlights product capabilities.
4. A playlist section that simulates interactive track selection.
5. A pricing section with plan cards and a featured call-to-action.

The primary purpose of the app is to demonstrate GSAP-based animation techniques for section reveals, timelines, staggered motion, and interaction feedback.

## Animation Features

The animation logic in [animations.js](animations.js) includes:

1. Hero sequence animations

- Navbar fade/slide intro
- Timeline-based hero text and CTA reveals
- Staggered float-card entrance

2. Stats ticker animations

- Section reveal animation
- Animated counters for users, tracks, and artists
- Delayed funding value display

3. Features section animations

- Header timeline
- Staggered feature card reveal
- Hover lift and scale interactions

4. Playlist section animations

- Header slide-in timeline
- Staggered track entrance
- Click-to-highlight track interaction

5. Pricing and footer animations

- Pricing header stagger
- Bounce-in pricing cards
- Repeating pulse for featured CTA button
- Footer fade-in

6. Readability improvements in code

- Concise inline comments explaining key animation flow and interaction logic

## Tech Used

1. JavaScript
2. GSAP (loaded by CDN)

## Running the Project

1. Open [index.html](index.html) in a browser.
2. Keep internet enabled so the GSAP CDN loads correctly.
3. Refresh the page after JavaScript edits to test animation changes.
