# Dominika Zagorácz - Portfolio

A magazine-style portfolio website showcasing multilingual storytelling, film production, and translation work.

## Recent Updates (January 27, 2026)

- Added "The Music of Erich Zann" festival achievements with elegant framed design
- Added Ongoing Projects section: "Killing You Softly" and "Full-bodied & Spicy"
- Updated Translator experience date to 2023 with specific publications
- Added Skills sections to Executive Assistant and Credit & Collection Analyst roles
- Updated contact links: LinkedIn, Email (dominika.zagoracz@gmail.com), Visual Diary (Tumblr)
- Enhanced mobile responsiveness
- All images optimized and properly linked

## Features

- **Magazine Layout**: Full-bleed images with editorial design
- **Responsive Design**: Works beautifully on desktop, tablet, and mobile
- **Section Navigation**: Four main sections with numbered headers
- **Elegant Typography**: Mix of Didot/Playfair serif and Helvetica Neue sans-serif
- **Opening Quote**: Gore Vidal's "The unfed mind devours itself"

## Structure

```
Portfolio/
├── index.html          # Main portfolio page
├── README.md           # This file
└── images/            # Image assets (create this folder to organize images)
```

## Customization Guide

### Changing Contact Information

Find the contact section at the bottom of `index.html` and update:

```html
<a href="mailto:your.email@example.com">Email</a>
<a href="#">LinkedIn</a>
<a href="#">Portfolio</a>
```

### Updating Content

All content is in `index.html`. Main sections to edit:

1. **Hero Quote** (line ~394): Change the opening quote
2. **About Section** (line ~410): Update introduction and skills
3. **Film & Writing** (line ~450): Edit creative work experience
4. **Professional Experience** (line ~490): Update job history
5. **Education** (line ~530): Modify academic credentials

### Styling Customization

Colors are defined in the CSS section. Main color variables:

- Background: `#fafafa`, `#ffffff`
- Text: `#2d2d2d`, `#4a4a4a`
- Accent: `#8b7355`, `#d4c5b9`
- Borders: `#e8e3dd`, `#f0ebe7`

### Adding Images

Place your images in a folder and update the `src` attributes in the HTML:

```html
<img src="path/to/your-image.jpg" alt="Description" class="section-image">
```

Current images used:
1. Newspaper reading (About section)
2. Olives & martini glass - 919a1854-3538-4fe6-a944-b0d1c7a83953.jpg (Film & Writing)
3. Elegant dinner setting (Professional Experience)
4. Leather sofa & books (Education)

## Mobile Responsiveness

The portfolio is fully responsive and optimized for:
- **Desktop**: Full magazine layout with side-by-side images
- **Tablet** (968px and below): Stacked layout with adjusted spacing
- **Mobile** (480px and below): Compact, touch-friendly design

Mobile features:
- Touch-friendly spacing and buttons
- Readable font sizes on small screens
- Optimized image heights
- Stacked contact links for easy tapping

## Font Stack

- **Serif**: Didot, Bodoni MT, Playfair Display, Georgia
- **Sans-serif**: Helvetica Neue, Arial

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Mobile browsers

## Tips for Editing

1. **Use a code editor** like VS Code, Sublime Text, or even Notepad++
2. **Preview changes** by opening the HTML file in your browser
3. **Keep backups** before making major changes
4. **Test on mobile** - use browser developer tools to preview responsive design

## Credits

Design inspired by editorial magazines like Vogue, Kinfolk, and The New Yorker.

---

Created with attention to typography, spacing, and visual hierarchy.
