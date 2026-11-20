# Travel Explorer ✈

A responsive travel discovery and trip-planning demo made with **HTML5, CSS3 and Vanilla JavaScript**.

## Features

- Responsive cinematic hero, mobile navigation and dark/light themes
- Search destinations by name/country, filter by category and budget, sort by price or rating
- 12 sample destinations, 8 travel categories, 4 sample packages
- Destination details modal and persistent favorites
- Interactive trip planner with date validation, group budget calculation and sample itineraries
- Locally saved trips, clickable gallery with keyboard controls, sample testimonials and demo newsletter
- Accessibility considerations and reduced-motion support

## Run

Open `index.html` in a browser, or use **VS Code → Live Server → Open with Live Server**. Internet access is needed for remote Unsplash images and Google Fonts; system font fallbacks are provided.

## Deploy to GitHub Pages

1. Create a GitHub repository and upload the contents of this folder to the repository root.
2. Open repository **Settings → Pages**.
3. Select **Deploy from a branch**, `main`, and `/ (root)`; save.
4. Open the published URL after deployment completes.

## Project structure

- `index.html` — markup and accessible controls
- `css/style.css` — components, layout and theme
- `css/responsive.css` — breakpoints
- `css/animations.css` — motion effects
- `js/data.js` — sample destination/package data
- `js/destinations.js` — filtering, favorites, modals
- `js/trip-planner.js` — itinerary and local trip persistence
- `js/script.js` — navigation, gallery, theme and initialization

## Demo disclaimer

All prices, ratings, packages and testimonials are **fictional or illustrative**. No actual bookings or newsletter subscriptions occur. Trip budgets are user-entered estimates. Remote Unsplash photos are for demo display; review image licenses and hosting requirements before commercial use. The demo contact email is not a real support address.

## Testing notes

JavaScript syntax and project asset paths were validated. Browser-based interaction and visual testing could not be completed in the available environment because Chromium blocked local navigation. The included layout preview is a schematic, not an actual browser screenshot.


## New: Travel dashboard and tourist attractions
- Dashboard at `#dashboard` shows live totals for destinations, saved favorites, saved trips, and combined user-entered trip budgets.
- Tourist attractions at `#attractions` include eight curated landmarks with location information, photo previews and Google Maps search links.
- Attraction photos are loaded from Unsplash when online; a local fallback illustration is displayed if unavailable. Some images are representative destination photos, not verified photographs of the specific landmark.
- Layout patterns are informed by familiar tourism discovery sites, but this is an original student demo, not affiliated with any travel company.
- No bookings or payments are processed. All costs and ratings are illustrative.
