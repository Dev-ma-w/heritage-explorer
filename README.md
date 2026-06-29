# 🏛️ Heritage Explorer

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  
  <h3>Interactive Cultural Heritage Information Platform</h3>
  <p>Explore historical sites, monuments, and cultural landmarks with rich multimedia content and detailed information.</p>
</div>

---

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

---

## 🎯 Overview

**Heritage Explorer** is an interactive web application dedicated to showcasing and preserving cultural heritage information. The platform provides users with detailed information about historical sites, monuments, and landmarks with rich multimedia content, interactive maps, and engaging user experiences.

This project demonstrates frontend expertise with modern web technologies and responsive design principles.

---

## ✨ Features

### 🗺️ Heritage Database
- ✅ Comprehensive collection of historical sites
- ✅ Detailed information about monuments
- ✅ Cultural significance and history
- ✅ Location coordinates and maps integration

### 🖼️ Multimedia Content
- ✅ High-quality images and galleries
- ✅ Video documentation
- ✅ 360° virtual tours
- ✅ Historical photographs and archives

### 🔍 Search & Discovery
- ✅ Advanced search functionality
- ✅ Filter by location, era, and category
- ✅ Tag-based navigation
- ✅ Favorites and bookmarking

### 📱 Responsive Design
- ✅ Mobile-friendly interface
- ✅ Tablet optimization
- ✅ Desktop experience
- ✅ Cross-browser compatibility

### 🗣️ User Engagement
- ✅ User reviews and ratings
- ✅ Comments and discussions
- ✅ Share on social media
- ✅ Download information guides

### 🌍 Interactive Maps
- ✅ Location-based exploration
- ✅ Cluster view for multiple sites
- ✅ Navigation assistance
- ✅ Distance calculations

---

## 🛠️ Technology Stack

| Category | Technology |
|----------|-----------|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **Styling** | CSS3, Bootstrap, Custom CSS |
| **Interactivity** | Vanilla JavaScript, jQuery |
| **Maps** | Google Maps API / Leaflet.js |
| **Storage** | Local Storage / Session Storage |
| **Icons** | FontAwesome, Google Material Icons |
| **Version Control** | Git & GitHub |

---

## 📁 Project Structure

```
heritage-explorer/
├── index.html                    # Main landing page
├── pages/
│   ├── sites.html               # Sites listing page
│   ├── site-detail.html         # Individual site detail
│   ├── search.html              # Search results
│   └── about.html               # About page
├── css/
│   ├── style.css                # Main stylesheet
│   ├── responsive.css           # Responsive design
│   └── animations.css           # CSS animations
├── js/
│   ├── main.js                  # Main JavaScript
│   ├── search.js                # Search functionality
│   ├── maps.js                  # Map integration
│   └── utils.js                 # Utility functions
├── images/
│   ├── sites/                   # Heritage site images
│   ├── icons/                   # UI icons
│   └── bg/                      # Background images
├── data/
│   ├── sites.json               # Heritage sites data
│   └── categories.json          # Categories data
├── assets/
│   ├── fonts/                   # Custom fonts
│   └── videos/                  # Video content
└── README.md                    # This file
```

---

## 🚀 Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- HTTP server (optional, for full functionality)
- Internet connection (for API integrations)

### Step 1: Clone the Repository
```bash
git clone https://github.com/Dev-ma-w/heritage-explorer.git
cd heritage-explorer
```

### Step 2: Set Up Local Server (Optional but Recommended)
Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Using Node.js:
```bash
npx http-server
```

Using PHP:
```bash
php -S localhost:8000
```

### Step 3: Open in Browser
```
http://localhost:8000
# or
file:///path/to/heritage-explorer/index.html
```

---

## 💻 Usage

### Browse Heritage Sites
1. Navigate to the **Sites** page
2. View all available heritage sites
3. Click on any site card to view detailed information

### Search Functionality
1. Use the search bar at the top
2. Search by site name, location, or era
3. Apply filters for refined results
4. Click on results to view details

### Explore on Map
1. Visit the **Map** view
2. Interactive map shows all heritage locations
3. Click on markers to see site information
4. Use zoom and pan controls

### View Details
1. Click on any heritage site
2. View comprehensive information
3. Browse image gallery
4. Read historical context
5. View related sites

### Save Favorites
1. Click the heart icon on any site
2. View all favorites from the sidebar
3. Manage your bookmark list

---

## 🎨 Customization

### Add New Heritage Sites
Edit `data/sites.json`:
```json
{
  "id": 1,
  "name": "Heritage Site Name",
  "location": "City, Country",
  "latitude": 13.3527,
  "longitude": 76.7694,
  "era": "Medieval",
  "category": "Monument",
  "description": "Detailed description...",
  "images": ["url1", "url2"],
  "history": "Historical information...",
  "rating": 4.5,
  "reviews": 120
}
```

### Modify Styles
Edit `css/style.css` to customize:
- Color scheme
- Typography
- Layout spacing
- Component styles

### Update Content
Edit HTML files in `pages/` directory to modify:
- Page structure
- Content sections
- Navigation

---

## 🔌 API Integration

### Google Maps API
Set up your API key in `js/maps.js`:
```javascript
const MAPS_API_KEY = 'your_google_maps_api_key';
```

### Weather API (Optional)
Add weather information for heritage sites:
```javascript
const WEATHER_API_KEY = 'your_weather_api_key';
```

---

## 📸 Screenshots

### Homepage
![Homepage](docs/screenshots/homepage.png)

### Sites Listing
![Sites Listing](docs/screenshots/sites-listing.png)

### Site Detail View
![Site Detail](docs/screenshots/site-detail.png)

### Interactive Map
![Map View](docs/screenshots/map-view.png)

---

## 📱 Responsive Breakpoints

```css
/* Mobile: < 576px */
/* Tablet: 576px - 768px */
/* Medium: 768px - 992px */
/* Desktop: > 992px */
```

---

## ⚡ Performance Optimization

- ✅ Lazy loading for images
- ✅ Minified CSS and JavaScript
- ✅ Image compression
- ✅ Caching strategies
- ✅ Optimized database queries

---

## 🎯 Future Enhancements

- [ ] Backend API with database
- [ ] User authentication and profiles
- [ ] Advanced filtering options
- [ ] Virtual reality tours
- [ ] Multilingual support
- [ ] Mobile app (React Native/Flutter)
- [ ] Audio guides
- [ ] AR heritage site markers
- [ ] Community contributions
- [ ] Offline mode with Service Workers
- [ ] Advanced analytics
- [ ] Admin panel

---

## 🐛 Known Issues

- [ ] Maps may require scrolling on mobile
- [ ] Video loading may be slow on low bandwidth
- [ ] Some features require modern browser support

---

## 📝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the **MIT License**.

---

## 🤝 Support

For support, email [manojdev3003@gmail.com](mailto:manojdev3003@gmail.com) or reach out on [LinkedIn](https://www.linkedin.com/in/dev-manoj-s-176027258/).

---

## 👨‍💻 Author

**Dev Manoj S**
- 🌐 Portfolio: [devmanoj.vercel.app](https://devmanoj.vercel.app)
- 💼 LinkedIn: [@dev-manoj-s-176027258](https://www.linkedin.com/in/dev-manoj-s-176027258/)
- 📧 Email: [manojdev3003@gmail.com](mailto:manojdev3003@gmail.com)
- 🔗 GitHub: [@Dev-ma-w](https://github.com/Dev-ma-w)

---

<div align="center">

**⭐ If you found this helpful, please consider giving it a star!**

Made with ❤️ by Dev Manoj S

</div>
