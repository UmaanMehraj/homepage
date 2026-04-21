# Personal Portfolio Homepage

A modern, responsive personal portfolio website showcasing projects and skills with a sleek, contemporary design.

## Features

- **Profile Section** - Eye-catching header with profile picture and social media links (GitHub, Twitter, LinkedIn)
- **Project Showcase** - Display of completed projects with previews, descriptions, and links
- **Responsive Design** - Modern CSS styling with diagonal/skewed visual elements
- **Icon Integration** - DevIcons for technology stack visualization
- **Clean Layout** - Organized sections for about, projects, and contact information

## Project Structure

```
homepage/
├── index.html          # Main HTML structure
├── styles.css          # Custom styling and layout
├── README.md           # Project documentation
└── assests/
    ├── img/            # Project preview images and profile picture
    └── icons/          # Custom SVG icons (e.g., open-in-new)
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/UmaanMehraj/homepage.git
   cd homepage
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server (optional):
     ```bash
     python -m http.server 8000
     # or
     npx http-server
     ```

3. **View at** - `http://localhost:8000` (if using server)

## Customization

### Update Profile Information
Edit the "About Me" section in `index.html`:
- Replace profile picture (`assests/img/pfp.jpg`)
- Update about text and social media links
- Add your GitHub, Twitter, and LinkedIn URLs

### Add/Modify Projects
Add new project cards in the projects section with:
- Project preview image
- Project title
- GitHub repository link
- Live demo link (if available)
- Project description

### Styling
Customize the look in `styles.css`:
- Change color scheme (currently cyan/teal: `#0891b2`)
- Adjust fonts and spacing
- Modify the diagonal skew effect

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and animations
- **DevIcons** - Technology icons via CDN

## Links

- [Live Demo](https://umaanmehraj.github.io/homepage)


This project was made during _The Odin Project_
