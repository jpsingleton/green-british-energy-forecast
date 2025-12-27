# Green British Energy Forecast

A lightweight web application that displays GB's green energy forecast, helping users identify the "greener nights" when electricity is sourced from more renewable wind energy.

🌐 **Live Demo**: [https://jpsingleton.github.io/green-british-energy-forecast/](https://jpsingleton.github.io/green-british-energy-forecast/)

## About

**Greener Nights** visualizes GB's green energy forecast over several days, indicating when electricity is likely to come from cleaner, more renewable sources. The application uses a "greenness index" to rate each day as HIGH, MEDIUM, or LOW based on renewable energy availability.

This tool can help you:

- Plan energy-intensive tasks (like running appliances, charging electric vehicles, etc.) during greener periods
- Reduce your carbon footprint by shifting electricity usage to times with higher renewable energy generation
- Stay informed about GB's energy mix trends

## Features

- 📊 **Visual Forecast Display**: Shows multiple days of green energy forecast data
- 🎨 **Color-Coded Ratings**:
  - 🟢 **GREEN (HIGH)**: Best time for energy consumption
  - 🟡 **ORANGE (MEDIUM)**: Moderate renewable energy
  - 🔴 **RED (LOW)**: Lower renewable energy availability
- 🔄 **Live Data**:  Fetches real-time forecast data
- 📱 **Responsive Design**: Works on desktop and mobile devices
- 🎄 **Easter Egg**: Special surprise on Christmas Day!

## How It Works

The application fetches green energy forecast data from a JSON API and displays:

- **Date**: The forecast date
- **Greenness Score**: A numerical score (0-100) indicating renewable energy levels
- **Visual Indicators**:  Symbols showing the intensity of renewable energy
  - `+` for HIGH greenness
  - `•` for MEDIUM greenness
  - `-` for LOW greenness
- **Greener Night Markers**: Arrows (`⇒` and `⇐`) highlight the optimal nights
  - Smaller grey arrows for nights that were previously optimal but now superseded

## Usage

Simply [open](https://jpsingleton.github.io/green-british-energy-forecast/) in your browser. The forecast automatically loads and can be refreshed using the "Refresh" button.

## Data Source

The application fetches forecast data from <https://github.com/jpsingleton/greener-nights-history>:

```txt
https://jpsingleton.github.io/greener-nights-history/greener-nights-history.json
```

This works without needing CORS headers.

## Technology Stack

- **HTML5**:  Structure
- **CSS3**: Styling with a dark theme optimized for readability
- **Vanilla JavaScript**: Async data fetching and DOM manipulation
- **GitHub Pages**: Hosting

---

💚 **Help reduce your carbon footprint, use energy during greener nights.**
