# Netflix Clone (React + Vite + Tailwind CSS)

A full-featured Netflix Clone UI built with React, Vite, Tailwind CSS, React Router v6, and TMDB API integration.

## Features
- **Netflix Style Login**: Background image backdrop, red Netflix theme, email sign-in storing user state in `localStorage`.
- **Navbar**: Sticky top navigation, transitions from transparent to solid dark blur on scroll, user profile popover menu.
- **Hero Banner**: Featured dynamic movie hero section with play trailer, my list toggle, gradient overlays.
- **Horizontal Movie Rows**: Smooth scrollable rows for 8+ movie genres with hover scaling effect.
- **YouTube Trailer Modal**: Clicking any movie poster launches a cinematic modal with YouTube trailer player and metadata.
- **My List Storage**: Interactive add/remove titles to personal watchlists, saved directly in `localStorage`.
- **TMDB API & Mock Data**: Supports custom `VITE_TMDB_API_KEY` from `.env`, with automatic offline mock fallback.

## Quick Start

1. Install dependencies:
   ```bash
   npm install
   ```

2. (Optional) Set TMDB API Key:
   Create `.env` file:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key_here
   ```

3. Run development server:
   ```bash
   npm run dev
   ```
   Open `http://localhost:5173` in your browser.
