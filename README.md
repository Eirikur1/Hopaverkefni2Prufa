# Venuu - Event Discovery Platform

A simple and clean website for discovering amazing events happening across Iceland. Built with vanilla HTML, CSS, and JavaScript.

## What is Venuu?

Venuu is a local event discovery platform that helps people find and connect through Iceland's vibrant cultural events. Whether you're looking for concerts, festivals, workshops, or community gatherings, Venuu makes it easy to discover what's happening around you.

## Features

- **Event Discovery**: Browse through a curated collection of events across Iceland
- **Smart Search**: Find events by name, location, or category
- **Filter Options**: Sort events by date, location, or category
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Clean Interface**: Simple and intuitive design that focuses on the events

## Pages

- **Home** (`index.html`) - Main landing page with featured events
- **Events** (`events.html`) - Complete event listing with search and filters
- **Login** (`login.html`) - User authentication page

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/Eirikur1/Hopaverkefni2Prufa.git
   cd Hopaverkefni2Prufa
   ```

2. **Open in your browser**

   - Simply open `index.html` in your web browser
   - No build process or dependencies required!

3. **Start exploring**
   - Browse events on the home page
   - Use the search bar to find specific events
   - Click on events to see more details

## Project Structure

```
├── index.html          # Home page
├── events.html         # Events listing page
├── login.html          # Login page
├── api-data.json       # Event data
├── Fonts/              # Custom fonts (Inter, RubikMonoOne)
├── Images/             # Event images and graphics
├── icons/              # SVG icons
└── Video/              # Lottie animations
```

## Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling with custom properties and flexbox/grid
- **JavaScript** - Interactive functionality and event handling
- **Tailwind CSS** - Utility-first CSS framework
- **Lottie** - Lightweight animations
- **Font Awesome** - Icon library

## Design Philosophy

This project focuses on simplicity and usability:

- **Clean Design**: Minimal, distraction-free interface
- **Mobile-First**: Responsive design that works on all devices
- **Fast Loading**: Optimized images and lightweight code
- **Accessible**: Proper semantic HTML and ARIA labels
- **User-Friendly**: Intuitive navigation and clear information hierarchy

## Customization

### Adding New Events

Edit `api-data.json` to add or modify events. Each event should include:

- `name`: Event title
- `date`: Event date
- `location`: Event venue
- `category`: Event type
- `description`: Event details
- `image`: Path to event image

### Styling Changes

- Main styles are in the `<style>` sections of each HTML file
- Colors and fonts can be customized in the CSS variables
- Mobile responsive breakpoints are set at 1024px, 768px, and 480px

### Fonts

The project uses custom fonts:

- **Inter**: Main body text and UI elements
- **RubikMonoOne**: Headings and titles

Font files are located in the `Fonts/` directory.

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

This is a student project, but suggestions and improvements are welcome! Feel free to:

- Report bugs or issues
- Suggest new features
- Improve the documentation
- Optimize performance

## License

This project is created for educational purposes. Please respect the rights of any third-party assets used.

## Contact

For questions about this project, you can reach out through the GitHub repository.

---
