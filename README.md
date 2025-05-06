# Basic HTML Portfolio Website

This is a simple portfolio website built with HTML, CSS, and JavaScript. It's designed to showcase your projects, skills, and contact information in a clean and responsive layout.

## Features

- Responsive design that works on all devices
- Navigation menu with smooth scrolling
- Hero section with call-to-action buttons
- About section with personal information
- Projects showcase with image gallery
- Skills section with progress bars
- Contact form
- Social media links
- Clean and modern design

## File Structure

```
Basic html/
├── css/
│   └── style.css
├── images/
│   └── README.txt (instructions for adding images)
├── js/
│   └── script.js
├── index.html
└── README.md
```

## How to Use

1. **Open the website**: Simply open the `index.html` file in your web browser to view the website.

2. **Customize the content**:
   - Edit the `index.html` file to update text, links, and structure
   - Modify the `css/style.css` file to change colors, fonts, and layout
   - Update the `js/script.js` file for custom functionality

3. **Add your images**:
   - Add your profile picture as `images/profile.jpg`
   - Add project images as `images/project1.jpg`, `images/project2.jpg`, etc.

## Customization

### Colors

You can change the color scheme by editing the CSS variables at the top of the `style.css` file:

```css
:root {
    --primary-color: #4a6baf;
    --secondary-color: #f8f9fa;
    --accent-color: #ff6b6b;
    --text-color: #333;
    --light-text: #f8f9fa;
    --dark-bg: #2c3e50;
    --light-bg: #ffffff;
    --border-color: #e9ecef;
    --shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}
```

### Personal Information

Update your personal information in the `index.html` file:

1. Change "Your Name" to your actual name
2. Update the tagline under your name
3. Edit the About Me section with your bio
4. Update contact information and social media links

### Projects

For each project you want to showcase:

1. Duplicate the project card HTML structure in the Projects section
2. Update the project title, description, and tags
3. Add a new project image in the images folder
4. Update the image path in the HTML

### Skills

Modify the skills section to reflect your actual skills:

1. Edit the skill names
2. Adjust the skill levels by changing the width percentage in the style attribute

## Contact Form

The contact form is set up for demonstration purposes. To make it functional:

1. You'll need to add server-side code to process the form submission
2. Or connect it to a form submission service like Formspree or Netlify Forms

## Browser Compatibility

This website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

Feel free to use this template for your personal portfolio.

---

Happy coding!