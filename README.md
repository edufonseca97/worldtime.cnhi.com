# CNHi - World Time & Calendar

A comprehensive world timezone and calendar application for tracking local times across multiple global locations, combined with agricultural seasonal activities by region.

## Overview

This application provides real-time timezone tracking for multiple global locations, including:
- **St Marys (Sydney)** - Australia/Sydney (GMT+10)
- **Pune** - Asia/Kolkata (GMT+5:30)
- **Plock** - Europe/Warsaw
- **Zedelgem** - Europe/Brussels (GMT+2)
- **Basildon** - Europe/London
- **Curitiba** - America/Sao_Paulo (GMT-3)
- **New Holland, PA** - America/New_York (GMT-4 EDT)
- **Oak Brook, IL** - America/Chicago (GMT-5 CDT)
- **Goodfield, IL** - America/Chicago
- **Sioux Falls, SD** - America/Chicago
- **Fargo, ND** - America/Chicago

## Features

✅ **Real-Time Timezone Display**
- Live clock updates every second
- 24-hour or AM/PM format toggle
- Date display with timezone abbreviations
- Country flags for visual identification

✅ **Calendar View**
- Full month grids with ISO week numbers
- Highlights current date with enhanced visual emphasis (shadow effect)
- Highlights entire current week with subtle background
- Bold week number for current week
- Day-of-year counter (e.g., "Day 129 of 365") shown only for current year
- Intelligent leap year detection (365/366 days)
- Weekend highlighting
- Multi-year navigation with years generated relative to the current year

✅ **Agricultural Seasons & Activities**
- Quarterly breakdown by region (NAFTA, EMEA, LATAM, APAC)
- Growing, harvest, and planting activities
- Region-specific seasonal information
- Comprehensive legend with acronym definitions

✅ **Best Meeting Times Calculator**
- Automatically calculates optimal meeting windows
- Assumes work hours 9am-5pm local time
- Shows top 3 best times in UTC
- Intelligently hides when no overlap exists

✅ **Theme Support**
- Dark mode / Light mode toggle
- Persistent preferences using localStorage
- Accessible color contrasts

✅ **Responsive Design**
- Works on desktop, tablet, and mobile
- Clean, modern UI with CSS Grid layout
- No external dependencies; single-file implementation

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid layout, media queries
- **JavaScript (ES6+)** - Vanilla JS, no frameworks
- **SVG** - Inline flag graphics

## Usage

1. Open `index.html` in a modern web browser
2. Use the Dark Mode toggle to switch themes
3. Switch between 24h and AM/PM time formats
4. Select different years to view calendars
5. Scroll down to see agricultural seasons and meeting time suggestions

## Files

- `index.html` - Complete single-file application (HTML + CSS + JavaScript)
- `README.md` - Documentation (this file)
- `_config.yml` - GitHub Pages configuration

## Developer

**Eduardo Kosinski**

Developed for CNHi Global Tracking and Agricultural Planning

## License

All rights reserved © 2026
