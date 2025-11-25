# Japan Travel Catalogue

A responsive web application for "Activity 6" of Web Developement Course in PUP showcasing iconic Japanese landmarks and cultural sites using Bootstrap 5 and vanilla JavaScript.

## Project Overview

This project is a fragmented part of JAPAN TOURS [ACTIVITY 5] in which it displays a collection of famous Japanese locations through an interactive card-based gallery. Each card features an image, title, and description of a notable landmark or cultural site in Japan.

**Live Demo:** https://james-rivera.github.io/japan-gallery/

**Related Project:** [Japan Tours - Activity 5](https://james-rivera.github.io/tokyo-showcase/)

## Features

- Responsive grid layout that adapts to different screen sizes
- Dynamic content generation using JavaScript arrays
- Bootstrap 5 styling and components
- Mobile-friendly design with breakpoints for various devices
- Fixed-height images with proper aspect ratio handling

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Bootstrap 5.3.3
- Bootstrap Icons

## File Structure

```
Activity 6/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── images/             # Image folder containing landmark photos
│   ├── showa.jpg
│   ├── fuji_train.jpg
│   ├── castle.jpg
│   └── inari_gates.jpg
├── favicon/            # Favicon files
└── README.md           # Project documentation
```

## Installation

1. Clone or download this repository
2. Ensure all image files are placed in the `images` folder
3. Open `index.html` in a web browser

## Usage

The page automatically generates cards for each location defined in the JavaScript arrays. To add more locations:

1. Add the image filename to the `image` array
2. Add the corresponding title to the `title` array
3. Add the description to the `description` array

Make sure all three arrays have the same length to avoid errors.

## Customization

### Styling
Edit `styles.css` to customize:
- Card appearance
- Typography (font family, weight, size)
- Colors and spacing
- Image dimensions

### Content
Modify the arrays in `index.html`:
```javascript
var image = ["image1.jpg", "image2.jpg"];
var title = ["Title 1", "Title 2"];
var description = ["Description 1", "Description 2"];
```

## Browser Compatibility

This project works on all modern browsers that support:
- CSS Grid and Flexbox
- ES6 JavaScript
- Bootstrap 5

## Credits

Developed as part of Web Development coursework.

## License

This project is for educational purposes only.