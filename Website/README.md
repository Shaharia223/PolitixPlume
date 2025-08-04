# PolitixPlume - Political Science Platform

A comprehensive frontend platform for political science articles, analysis, and academic discourse focused on Bangladesh and international politics.

## Features

- **Multi-section Articles**: Bangladesh Politics, Books Review, Political Science Academia, International Politics
- **Responsive Design**: Modern, mobile-friendly interface
- **Static Content**: Fast-loading HTML/CSS/JS website
- **Article Submission Form**: Public submission system for contributors
- **Professional Layout**: Clean, academic-focused design

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with responsive design
- **Icons**: Font Awesome
- **Hosting**: Static file hosting (GitHub Pages, Netlify, Vercel, etc.)

## Project Structure

```
Website/
├── home.html                 # Main homepage
├── about.html               # About page
├── bangladesh-politics.html # Bangladesh politics section
├── books-review.html        # Books review section
├── political-science-academia.html # Academic section
├── international-politics.html # International politics section
├── styles.css              # Main stylesheet
├── Submission/            # Article submission pages
│   ├── Submission.html
│   └── submissionguideline.html
└── CV/                   # Portfolio/CV pages
```

## Quick Start

### Option 1: Direct File Opening
Simply open any HTML file in your browser:
```bash
# Navigate to the Website folder
cd Website

# Open the homepage
# Double-click home.html or drag it to your browser
```

### Option 2: Local Server (Recommended)
For better development experience, use a local server:

**Using Python:**
```bash
cd Website
python -m http.server 8000
# Then visit: http://localhost:8000/home.html
```

**Using Node.js:**
```bash
cd Website
npx serve .
# Then visit: http://localhost:3000/home.html
```

**Using Live Server (VS Code Extension):**
1. Install "Live Server" extension in VS Code
2. Right-click on any HTML file
3. Select "Open with Live Server"

## Usage

### For Visitors
1. Browse articles by section
2. Read political analysis and academic content
3. Submit articles through the submission form
4. Contact the team through the About page

### For Content Updates
Since this is a static website, content updates require:
1. Editing the HTML files directly
2. Replacing placeholder images with actual content
3. Updating article text and metadata

## Customization

### Adding New Articles
1. Open the appropriate section HTML file
2. Copy an existing article card structure
3. Update the content, images, and metadata
4. Save the file

### Styling Changes
- Main styles are in `styles.css`
- Section-specific styles can be added inline or in separate CSS files
- Uses CSS Grid and Flexbox for responsive layouts

### Adding New Sections
1. Create a new HTML file for the section
2. Copy the structure from existing section pages
3. Update navigation in all HTML files
4. Add your content

## Deployment

### Static Hosting Options
This website can be deployed to any static hosting service:

- **GitHub Pages**: Free hosting for public repositories
- **Netlify**: Drag and drop deployment
- **Vercel**: Fast deployment with Git integration
- **Firebase Hosting**: Google's hosting solution
- **AWS S3 + CloudFront**: Scalable hosting
- **Traditional Web Hosting**: Any web hosting service

### Deployment Steps
1. Upload all files to your hosting service
2. Ensure all file paths are correct
3. Test all links and functionality
4. Update any absolute URLs if needed

## Content Management

### Current Content Structure
- **Bangladesh Politics**: 3 sample articles
- **Books Review**: 3 sample articles
- **Political Science Academia**: 3 sample articles
- **International Politics**: 3 sample articles

### Article Submission
The submission form is currently set up to use Google Apps Script for processing. You can:
1. Keep the current Google Apps Script setup
2. Replace with a different form processing service
3. Implement a custom backend later

## Development

### Recommended Tools
- **Code Editor**: VS Code, Sublime Text, or Atom
- **Browser DevTools**: For testing and debugging
- **Image Editor**: For optimizing images
- **Git**: For version control

### Best Practices
1. Optimize images for web (compress, use appropriate formats)
2. Test on multiple browsers and devices
3. Ensure all links work correctly
4. Validate HTML and CSS
5. Test responsive design on different screen sizes

## Future Enhancements

This static website can be enhanced with:
- **Backend Integration**: Add a CMS or database
- **Search Functionality**: Implement client-side search
- **Comments System**: Add social features
- **Newsletter**: Email subscription system
- **Analytics**: Track visitor behavior
- **SEO Optimization**: Improve search engine visibility

## Contact

- **Email**: politixplume@gmail.com
- **Phone**: +880 1521739684
- **Location**: Dhaka, Bangladesh

## Support

For support and questions:
- Check the About page for contact information
- Review the submission guidelines
- Contact the development team

---

**PolitixPlume** - Fostering informed political discourse since 2025 