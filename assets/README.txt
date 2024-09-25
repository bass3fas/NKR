# NKR Migration Services - Website Design Documentation

This document contains the design specifications and assets required for building the NKR Migration Services website. The website follows a one-page layout, featuring sections such as the Hero, Photo Gallery, and About sections. Below are the details for typography, color palette, and design elements.

## Fonts
All fonts are from the Google Fonts library and should be included in the HTML header:

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@300;400;500;700;900&display=swap" rel="stylesheet">


| Section          | Text Example                                      | Font        | Weight    | Size | Color    |
|------------------|---------------------------------------------------|-------------|-----------|------|----------|
| NavBar           | Home, Your Trip, Gallery, About, Contacts         | Roboto Slab | Medium    | 30pt | #FFFFFF  |
| NavBar           | Search...                                         | Roboto Slab | Medium    | 30pt | #343C61  |
| NavBar           | NKR MIGRATION                                     | Roboto Slab | Black     | 27pt | #FFFFFF  |
| Hero Section     | Explore the World                                 | Roboto Slab | Light     | 27pt | #FFFFFF  |
| Hero Section     | Book Now                                          | Roboto Slab | Regular   | 27pt | #343C61  |
| Hero Section     | EXPLORE                                           | Roboto Slab | Light     | 98pt | #FFFFFF  |
| Hero Section     | THE WORLD                                         | Roboto Slab | Black     | 98pt | #FFFFFF  |
| Hero Section     | WE PLAN YOUR TRIP THROUGH THE BEST CITIES         | Roboto Slab | Regular   | 41pt | #FFFFFF  |
| Hero Section     | From Dubai to the World – Your Trusted Partner... | Roboto Slab | Regular   | 18pt | #FFFFFF  |
| Photo Section    | YOUR TRIP                                         | Roboto Slab | Black     | 54pt | #343C61  |

*Note: Use `sans-serif` as fallback for all fonts.*

## Colors

| Color Name | Hex Code | Usage                                         |
|------------|----------|-----------------------------------------------|
| White      | #FFFFFF  | Background, Text on Dark Backgrounds, Buttons |
| Blue       | #343C61  | Text, CTA Buttons, Icons                      |
| Pink       | #C05871  | Accent Elements, Highlights                   |


## Sections Overview

1. **NavBar**:
   - Contains navigation links and the NKR MIGRATION logo.
   - Navigation links should scroll smoothly to the corresponding sections on click.
   - The "Search..." input field should include a placeholder.

2. **Hero Section**:
   - Central focus with a compelling background image.
   - Main headline: "EXPLORE THE WORLD"
   - Subheadline: "From Dubai to the World – Your Trusted Partner for Hassle-Free Travel and Migration Solutions"
   - CTA button: "Book Now" should have a hover effect with a slight color change.

3. **Photo Section**:
   - A visual gallery showcasing various destinations and trips.
   - Main heading: "YOUR TRIP"
   - Images should be in a grid format with captions overlaying on hover.

4. **About Section**:
   - A brief introduction to NKR Migration Services, their mission, and values.
   - Include a list of services offered with icons representing each service.

5. **Contact Section**:
   - Contact form with fields for Name, Email, Phone Number, and Message.
   - Include social media links and a Google Maps embed for the office location.


## Exported Assets

| Asset Name                 | Format | Usage                                   |
|----------------------------|--------|-----------------------------------------|
| `background-blue`          | PNG    | Simple color background                 |
| `background-pink`          | PNG    | Diagonally dividing the page into halves|
| `bottom-objects`           | SVG    | White shadow shapes for destinations    |
| `clouds`                   | SVG    | Decorative element for the sky effect   |
| `dotted-lines`             | SVG    | Visual elements for separation or design|
| `dotted-ropes`             | SVG    | Visual elements for separation or design|
| `flying-balloons`          | SVG    | Decorative flying balloons              |
| `hero-line`                | SVG    | Line element for the hero section       |
| `logo`                     | SVG    | Main logo                               |
| `logo-with-text`           | SVG    | Logo with company name                  |
| `objects-over-photo`       | SVG    | White shadow shapes of travel objects   |
| `photo`                    | PNG    | Photo asset                             |
| `photo-empty`              | PNG    | Photo frame without a photo             |
| `photo-with-header`        | PNG    | Photo with frame and "your trip" header |
| `photo-with-header-empty`  | PNG    | Empty photo frame with header           |
| `search-icon`              | SVG    | Search icon for the navigation bar      |


## Developer Notes
- Ensure all SVG assets are optimized using a tool like [SVGOMG](https://jakearchibald.github.io/svgomg/).
- Implement lazy loading for images in the Photo Section to improve page load performance.
- Use CSS Flexbox or Grid for layout to maintain responsiveness across different screen sizes.
- For the Contact Section, implement form validation to enhance user experience.

