# Personal Portfolio Website

A modern, responsive personal portfolio website showcasing skills, projects, resume, and contact information for a fresh graduate.

## Features

- **Responsive Design**: Fully responsive across all devices
- **Smooth Scrolling**: Smooth navigation between sections
- **Sticky Navigation**: Fixed navbar with scroll effect
- **Animated Sections**: Fade-in animations on scroll
- **Mobile Menu**: Hamburger menu for mobile devices
- **Multiple Sections**:
  - Hero section with call-to-action
  - About section with profile photo and stats
  - Skills section with categorized abilities
  - Projects showcase with live demo links
  - Resume with education, internships, and certifications
  - Contact form with social links

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript
- Intersection Observer API

## File Structure

```
portfolio/
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
├── script.js       # Interactive functionality
└── README.md       # Documentation
```

## Sections Overview

### 1. Home/Hero
- Eye-catching introduction
- Professional title
- Call-to-action buttons

### 2. About
- Profile photo
- Personal introduction
- Achievement statistics (Projects, Certifications, Internships)

### 3. Skills
- Frontend technologies
- Backend technologies
- Database knowledge
- Development tools

### 4. Projects
- Project showcase with images
- Technology tags
- Live demo and GitHub links

### 5. Resume
- Education details
- Internship experience
- Certifications (4 major certifications)
- Download resume button

### 6. Contact
- Contact information (Email, Phone, Location)
- Social media links
- Contact form

## How to Use

1. Open `index.html` in your web browser
2. Navigate using the top menu or scroll through sections
3. Click on navigation links for smooth scrolling
4. On mobile, use the hamburger menu

## Customization

### Personal Information

Edit `index.html` to update:

```html
<!-- Name and Title -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Your Title</p>

<!-- Contact Details -->
<p>your.email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>Your Location</p>
```

### Profile Photo

Replace the image URL in the About section:

```html
<img src="your-photo.jpg" alt="Profile Photo">
```

### Skills

Update the skills in each category in `index.html`:

```html
<ul>
    <li>Your Skill 1</li>
    <li>Your Skill 2</li>
</ul>
```

### Projects

Add or modify projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="project-image.jpg" alt="Project">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Description</p>
        <div class="project-tags">
            <span>Tech1</span>
            <span>Tech2</span>
        </div>
    </div>
</div>
```

### Colors

Change the color scheme in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --dark-bg: #0f172a;
    --light-bg: #f8fafc;
}
```

### Resume/Certifications

Update education, internships, and certifications in the Resume section of `index.html`.

## Responsive Breakpoints

- Desktop: 1024px and above
- Tablet: 769px - 1023px
- Mobile: Below 768px
- Small Mobile: Below 480px

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

- Optimize images before uploading
- Use WebP format for better compression
- Minify CSS and JavaScript for production
- Consider lazy loading for images

## Deployment

You can deploy this portfolio on:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply upload all files to your hosting service.

## License

Free to use for personal projects. Customize as needed!
