# Smart Bin System

## Overview
The **Smart Bin System** is a web-based application that helps users locate nearby bins and check their fill levels. The system uses **Google Maps API** for location tracking and displays bin status dynamically.

## Features
- **Google Maps Integration:** Displays user location and nearby bins.
- **Bin Status Visualization:** Shows bin fill percentage dynamically.
- **Geolocation Support:** Locates user and centers the map accordingly.
- **Interactive UI:** Click to view bin details, double-click to open status page.

## Project Structure
```
/project-root
  ├── /css           # For stylesheets (if needed)
  ├── /js            # For scripts (if needed)
  ├── /assets        # For images/icons (if needed)
  ├── bin.html       # Main Map Interface
  ├── binstatus.html # Bin Status Page
  ├── README.md      # Project Documentation
```

## Setup Instructions
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/smart-bin-system.git
   cd smart-bin-system
   ```
2. **Replace Google Maps API Key:**
   - Open `bin.html`
   - Replace the placeholder in:
     ```html
     <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAPS_API_KEY"></script>
     ```
3. **Run the Project:**
   - Open `bin.html` in a browser.
   - Ensure **geolocation permissions** are enabled.

## Technologies Used
- **HTML, CSS, JavaScript**
- **Google Maps API**
- **AngularJS & Ionic Framework (for binstatus.html)**

## Future Enhancements
- Fetch **real bin locations** from a database instead of random placements.
- Improve UI/UX with **better styling and animations**.
- Implement **user authentication** for reporting full bins.

## Contributing
Feel free to fork and submit pull requests!

