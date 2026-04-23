# PlacementPulse
A modern and responsive College Placement Dashboard built using HTML, CSS, and JavaScript. It visualizes student placement data with interactive charts, filters, and analytics to help track placement performance effectively.
Here is the updated `README.md` file with the deployment link included.

```markdown
# College Placement Dashboard

A modern, fully responsive web application for visualizing and managing college placement data. Built with pure HTML, CSS, and JavaScript, featuring real-time charts, filtering capabilities, and a polished dark/light mode interface.

## Live Demo

**[Click here to view the deployed application](https://radiant-kataifi-e62bd7.netlify.app/)**

![Dashboard Preview](https://via.placeholder.com/1200x600/0a0f1c/06d6a0?text=College+Placement+Dashboard)

## Features

### Dashboard Overview
- **Key Metrics Cards**: Total Students, Students Placed, Highest Package, and Average Package with animated counters and trend indicators.

### Data Visualization
- **Bar Chart**: Company-wise placement statistics with toggleable years.
- **Line Chart**: Package trends over the years with toggleable metrics (Highest/Average).
- **Pie Chart**: Department-wise placement distribution with custom legend.

### Advanced Filtering & Search
- **Multi-select Filters**: Filter data by Department, Year, and Company.
- **Instant Search**: Real-time search across student names and companies.
- **Sortable Table**: Click headers to sort data ascending or descending.

### UI/UX Enhancements
- **Dark/Light Mode**: Smooth theme toggle with localStorage persistence.
- **Responsive Sidebar**: Collapsible navigation for both desktop and mobile views.
- **Animated Entrance**: Staggered reveal animations for cards and sections using Intersection Observer.
- **Hover Effects**: Interactive feedback on cards, buttons, and table rows.

## Technologies Used

- **HTML5**: Semantic structure.
- **CSS3**: Custom properties (variables), Flexbox, CSS Grid, and keyframe animations.
- **JavaScript (ES6+)**: DOM manipulation, Array methods, Dynamic rendering.
- **Chart.js**: For rendering responsive charts (Bar, Line, Doughnut).
- **Font Awesome**: Icon library.
- **Google Fonts**: Poppins font family.

## Getting Started

### Prerequisites
You only need a modern web browser to run this application. No server or build tools are required.

### Installation

1. **Download the file**
   Save the `index.html` file to your local machine.

2. **Run the application**
   Double-click the `index.html` file to open it in your default web browser.

Alternatively, you can use a local development server like VS Code's "Live Server" extension for a better development experience.

## Project Structure

Since this is a single-file application, the structure is straightforward:

```
college-placement-dashboard/
│
├── index.html       # Contains HTML, CSS, and JS
└── README.md        # Documentation file
```

## Customization

### Changing the Data
All dummy data is located within the `<script>` tag at the bottom of the HTML file.

**Student Data:**
```javascript
const students = [
    { name: "Arjun Sharma", department: "CSE", company: "Google", package: 48, year: 2024 },
    // Add more students here...
];
```

**Chart Data:**
Update the following objects to change chart values:
- `departmentData` for the Pie Chart.
- `companyData` for the Bar Chart.
- `packageTrends` for the Line Chart.

### Changing Colors
The color scheme uses CSS Custom Properties defined in the `:root` and `[data-theme="light"]` selectors within the `<style>` tag. Modify these variables to match your branding:

```css
:root {
    --bg-primary: #0a0f1c;
    --accent: #06d6a0;
    /* ... other variables */
}
```

## Browser Support

- Google Chrome (Recommended)
- Mozilla Firefox
- Microsoft Edge
- Safari

## Performance

- **CSS Animations**: Hardware-accelerated for smooth transitions.
- **Efficient Rendering**: Tables use pagination to handle large datasets efficiently.
- **Reduced Motion**: Respects `prefers-reduced-motion` user preference for accessibility.

## License

This project is open-source and available under the MIT License.

---

Created with care for a modern web experience.
```
