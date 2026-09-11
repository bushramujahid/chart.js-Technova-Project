# TechNova Performance Dashboard

A responsive dashboard built with HTML, CSS, JavaScript, and [Chart.js](https://www.chartjs.org/). It presents sample business performance data for TechNova across six months.

## Features

- Line chart comparing revenue, expenses, and profit
- Bar chart showing monthly revenue
- Pie chart showing June profit distribution
- Responsive layout for desktop and mobile screens
- Chart.js loaded from the jsDelivr CDN

## Getting Started

No build tools or package installation are required.

1. Clone or download this project.
2. Open `index.html` in a modern web browser.
3. Make sure the browser has an internet connection so Chart.js can load from the CDN.

For a local development server, run any static file server from the project directory. For example, with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This project has been deployed live on [Netlify](https://bushraproject.netlify.app/).

## Project Structure

```text
project on chart.js/
├── index.html   # Dashboard markup, styles, and chart configuration
├── favicon.ico  # Browser icon
└── README.md    # Project documentation
```

## Customizing the Data

The chart data is defined near the bottom of `index.html` in the `months`, `revenue`, `expenses`, and `profit` arrays. Update those arrays to change the six-month performance figures. The pie chart values are defined separately in its dataset as `[40, 35, 25]`.

## Technologies

- HTML5
- CSS3
- JavaScript
- Chart.js 4.x via CDN
