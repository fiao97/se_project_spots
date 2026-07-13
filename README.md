# Project 3: Spots

An image sharing site

## Description

Spots is a responsive image-sharing page where a user can showcase photos from
places they've visited. The layout is built mobile-first and adapts fluidly from
large desktop screens down to small phones.

The page is made up of four main sections:

- **Header** — the Spots logo.
- **Profile** — the user's avatar, name, and description, along with "Edit Profile"
  and "New Post" buttons.
- **Cards** — a responsive grid of photo cards, each with an image, a title, and a
  like button.
- **Footer** — a simple copyright line.

The card grid uses CSS Grid with `auto-fit` so cards reflow into as many columns as
the screen can fit, and collapses to a single column on narrow screens. The profile
section uses Flexbox and restacks vertically below the 627px breakpoint so the avatar,
name, and buttons stay readable on mobile. Images are set to preserve their aspect
ratio and fill their card without distortion.

The project is written in semantic HTML and organized with the BEM methodology — each
block lives in its own CSS file under `blocks/`, imported through `pages/index.css`.

## Tech Stack

- HTML
- CSS
- Responsive Design

## Deployment

This webpage is deployed to GitHub Pages

- Deployment link: https://fiao97.github.io/se_project_spots/
