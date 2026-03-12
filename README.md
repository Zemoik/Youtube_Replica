# 📺 YouTube Replica

A pixel-accurate clone of the YouTube homepage built with pure HTML and CSS —
replicating the header, sidebar navigation, search bar, notification badge,
and a fully responsive video grid displaying 12 real video cards.

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=flat&logo=google&logoColor=white)

## Features
- Full three-section header: YouTube logo + hamburger menu, search bar with voice search, upload/notifications/profile icons
- Notification badge showing unread count
- Fixed sidebar with SVG icons for Home, Explore, Subscriptions, Originals, YouTube Music, and Library
- Video grid displaying 12 cards with thumbnails, video duration overlay, channel profile pictures, titles, view counts, and upload dates
- Pure CSS tooltips on hover for all header icon buttons
- Google Fonts Roboto to match YouTube's exact typography
- No JavaScript, no frameworks — layout built entirely with CSS Flexbox and Grid

## Preview

<img width="1919" height="956" alt="Screenshot 2026-03-11 at 10 28 22 PM" src="https://github.com/user-attachments/assets/7d4a1916-546e-4838-9d36-b202faf18289" />


## Tech Stack
| Layer | Technology |
|-------|------------|
| Structure | HTML5 |
| Styling | CSS3 (Flexbox, Grid) |
| Typography | Google Fonts Roboto |
| Icons | Custom SVGs |
| Images | JPEG / WebP |

## Setup
```bash
git clone https://github.com/Zemoik/Youtube-Replica.git
cd Youtube-Replica
open index.html
```
No dependencies, no build step, no internet connection required after clone.

## Project Structure
```
Youtube-Replica/
├── index.html        # Full page markup — header, sidebar, video grid
├── styles.css        # All layout and styling (Flexbox + Grid)
├── icons/            # SVG icons for header and sidebar
│   ├── youtube-logo.svg
│   ├── hamburger-menu.svg
│   ├── search.svg
│   ├── notifications.svg
│   └── ...
├── profiles/         # Channel profile pictures (channel-1 to channel-12)
├── thumbnails/       # Video thumbnails (thumbnail-1 to thumbnail-12, .webp)
└── README.md
```

## What I Learned
- Structuring complex page layouts using CSS Flexbox and Grid together
- Building a sticky fixed header and sidebar with proper z-index layering
- Implementing pure CSS tooltips triggered on hover without JavaScript
- Working with SVG icons and controlling their size and alignment in CSS
- Using consistent class naming for scalable styling
- Replicating a real-world production UI from scratch by inspecting layout patterns

## Author
**Dev Patel** — [LinkedIn](https://www.linkedin.com/in/dev--patel--/) · [GitHub](https://github.com/Zemoik)
