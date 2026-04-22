🌦️ the.weather

A weather app I built that actually feels nice to use. It pulls live data, looks good, and reacts to the weather — if it's raining, you'll know.

---

What it does

- Search any city and get current conditions instantly
- Works with your location too, if you allow it
- Toggle between °C and °F
- Dark and light mode (because not everyone wants to be blinded at night)
- The background and animations change based on what's happening outside — rain falls, snow drifts
- All the data you'd actually want: temp, feels like, humidity, wind, pressure, visibility, cloud cover
- Sunrise/sunset times + a UV index indicator
- 7-day forecast
- Save your frequent cities — they stick around thanks to localStorage
- Smart search suggestions as you type
- Toast notifications and a loading state so nothing feels janky

---

Built with

Just HTML, CSS, and vanilla JavaScript. No frameworks. Weather data from OpenWeatherMap.

---

Getting started

1. Download or clone the repo
2. Grab a free API key from openweathermap.org
3. Drop it in the script where it says `const API_KEY = 'YOUR_API_KEY'`
4. Open `index.html` in your browser — that's it

Everything lives in a single `index.html` file, so there's nothing to install or configure.

---

A few honest notes

The UV index is simulated since the free API tier doesn't include it. AQI isn't in yet either. And like any free API, there are rate limits — shouldn't be an issue for normal use.

---

What's next

Things I want to add when I get to it: real AQI data, an hourly forecast chart, live search suggestions from the API, maybe voice search, and PWA support so it can be installed like a proper app.
