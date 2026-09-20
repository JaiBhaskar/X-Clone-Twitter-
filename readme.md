# X Clone

A responsive frontend recreation of the X (formerly Twitter) home timeline. It is built as a UI practice project using plain HTML and Tailwind CSS.

## Preview

The interface includes a three-column X-style layout with navigation, a timeline composer, sample posts, trends, suggested accounts, and responsive breakpoints for smaller screens.

## Features

- Responsive left navigation sidebar
- Home / Following timeline tabs
- Post composer and timeline cards
- Post action icons with hover states
- Search, trends, and “Who to follow” panels
- Tailwind CSS utility-based styling
- Material Symbols icons and local profile images

> This is a static frontend mockup. Buttons, posting, search, authentication, and other X features are not connected to a backend.

## Tech Stack

- HTML5
- Tailwind CSS
- Vite
- PostCSS and Autoprefixer
- Google Material Symbols

## Getting Started

### Prerequisites

Install [Node.js](https://nodejs.org/) (version 16 or later recommended).

### Installation

```bash
git clone https://github.com/<your-username>/x-clone.git
cd x-clone
npm install
```

### Run locally

```bash
npm run start
```

Open the local URL shown in the terminal (usually `http://localhost:5173`).

## Project Structure

```text
├── index.html          # Main application markup
├── main.css            # Tailwind CSS entry file
├── tailwind.config.js  # Tailwind configuration
├── postcss.config.js   # PostCSS configuration
├── *.jpg               # Local profile/image assets
└── package.json        # Scripts and dependencies
```

## Customize

- Edit `index.html` to update layout, posts, text, and UI content.
- Add or modify Tailwind utility classes directly in `index.html`.
- Replace the local `.jpg` files with your own image assets if needed.

## Deployment

Create a production build with:

```bash
npx vite build
```

Deploy the generated `dist` folder with a static hosting provider such as Vercel, Netlify, or GitHub Pages.

## Disclaimer

This project is made for learning and portfolio purposes only. X/Twitter names, branding, and related assets belong to their respective owners.
