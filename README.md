# Shubham Baxi - Personal Website

The personal portfolio of Shubham Baxi, an aspiring engineer exploring robotics, computer vision, reinforcement learning, and useful automation.

The site is a lightweight static website built with HTML and CSS. It introduces the author, highlights selected GitHub projects, and links visitors to GitHub and YouTube.

## Features

- Responsive layout for desktop and mobile screens
- About, selected work, and contact sections
- Project cards linked to the original GitHub repositories
- Custom `SB.` browser-tab favicon
- Google Fonts using Space Grotesk and DM Mono
- No JavaScript or build step required

## Featured Projects

- [`line-follower-robot`](https://github.com/shubhambaxi1-code/line-follower-robot) - An Arduino robot that follows a black track using IR sensors and bang-bang control.
- [`YOLO-for-human-following-robot`](https://github.com/shubhambaxi1-code/YOLO-for-human-following-robot) - A YOLOv8 application for detecting people and producing position-based guidance.
- [`mountain-car-gymnasium`](https://github.com/shubhambaxi1-code/mountain-car-gymnasium) - A tabular Q-learning experiment using Gymnasium's MountainCar environment.
- [`amazon-price-tracker`](https://github.com/shubhambaxi1-code/amazon-price-tracker) - A scheduled price monitor that records changes and sends email notifications.

## Run Locally

Because this is a static site, it can be opened directly:

1. Clone or download the repository.
2. Open `index.html` in a browser.

For a local development server, run one of these commands from the project directory:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Project Files

| File | Purpose |
| --- | --- |
| `index.html` | Page content, navigation, project cards, and links |
| `style.css` | Layout, colors, typography, responsive behavior, and states |
| `favicon.svg` | Custom browser-tab icon |
| `old.txt` | Earlier page draft kept for reference |

## Customization

Update the text and links in `index.html`. Adjust the visual system in `style.css`, including the colors in the `:root` variables. Replace `favicon.svg` if you want to use a different tab icon.