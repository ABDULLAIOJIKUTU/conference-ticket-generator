# Conference Ticket Generator

A dynamic web application that generates personalized conference tickets with custom user information and downloadable output.

## 🎫 Overview

This project allows users to create professional-looking conference tickets by entering their details. The generated tickets can be previewed in real-time and downloaded for use at events.

## ✨ Features

- **Real-time Preview**: See your ticket update as you type
- **Custom Information**: Add name, email, GitHub username, and more
- **Avatar Integration**: Automatically fetch GitHub avatars or upload custom images
- **Download Capability**: Save tickets as images (PNG/JPG) or PDF
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **QR Code Integration**: Generate unique QR codes for ticket validation
- **Multiple Themes**: Choose from different ticket designs
- **Form Validation**: Ensures all required fields are filled correctly

## 🚀 Demo

[View Live Demo](#) *(Add your live demo link here)*

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling and animations
- **JavaScript (Vanilla)**: Dynamic ticket generation and interactions
- **Canvas API / HTML2Canvas**: For ticket rendering and download
- **QR Code Library**: For generating unique ticket codes (optional)

## 📁 Project Structure

```
conference-ticket-generator/
│
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Main styles
│   └── ticket.css         # Ticket-specific styles
├── js/
│   ├── main.js            # Main application logic
│   ├── ticket-generator.js # Ticket generation functionality
│   └── download.js        # Download functionality
├── assets/
│   ├── images/            # Logos, backgrounds, icons
│   └── fonts/             # Custom fonts (if any)
├── templates/             # Ticket templates
└── README.md
```

## 💻 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML, CSS, and JavaScript
- (Optional) Local server for testing (Live Server, Python SimpleHTTPServer)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/conference-ticket-generator.git
   ```

2. Navigate to the project directory
   ```bash
   cd conference-ticket-generator
   ```

3. Open `index.html` in your browser
   ```bash
   # Using Live Server (VS Code extension)
   # Or simply open the file
   open index.html
   ```

### Usage

1. **Enter Your Details**
   - Fill in your name, email, and other required information
   - (Optional) Enter your GitHub username to auto-fetch your avatar
   - Or upload a custom profile picture

2. **Customize Your Ticket**
   - Select a ticket theme/design
   - Preview changes in real-time

3. **Download Your Ticket**
   - Click the "Download Ticket" button
   - Choose your preferred format (PNG, JPG, or PDF)
   - Save and use your ticket!

## 🎨 Customization

### Adding New Ticket Templates

Create a new template in the `templates` folder and add it to the selection:

```javascript
const templates = {
  default: {
    background: '#gradient',
    accentColor: '#your-color',
    font: 'Your-Font'
  },
  // Add your new template
  premium: {
    background: '#gradient',
    accentColor: '#your-color',
    font: 'Your-Font'
  }
};
```

### Modifying Ticket Design

Edit `css/ticket.css` to customize the ticket appearance:

```css
.ticket-container {
  /* Your custom styles */
}
```

### Changing Conference Details

Update conference information in `main.js`:

```javascript
const conferenceInfo = {
  name: "Your Conference Name",
  date: "January 1, 2025",
  location: "City, Country",
  logo: "path/to/logo.png"
};
```

## 📋 Features Breakdown

### Form Validation
- Email format validation
- Required field checks
- GitHub username format validation
- File size limits for image uploads

### Ticket Generation
- Dynamic content rendering
- Real-time preview updates
- Unique ticket ID generation
- QR code for ticket verification

### Download Options
- PNG format (high resolution)
- JPG format (compressed)
- PDF format (printable)

## 🔧 Configuration

### API Keys (if applicable)

If using external APIs for QR codes or image processing, add your keys:

```javascript
// In js/config.js
const CONFIG = {
  QR_API_KEY: 'your-api-key',
  GITHUB_TOKEN: 'your-github-token' // Optional
};
```

## 🌐 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Internet Explorer (limited support)

## 📱 Responsive Design

- **Desktop**: Full-featured experience with side-by-side form and preview
- **Tablet**: Stacked layout with optimized spacing
- **Mobile**: Touch-friendly interface with simplified controls

## 🐛 Known Issues

- Large image uploads may take time to process
- PDF generation might have slight quality differences across browsers
- GitHub API has rate limits for unauthenticated requests

## 🚀 Future Enhancements

- [ ] Multiple ticket types (VIP, Regular, Student)
- [ ] Batch ticket generation
- [ ] Email integration to send tickets directly
- [ ] Admin panel for event organizers
- [ ] Social media sharing capabilities
- [ ] Print optimization
- [ ] Dark mode support

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**ojikutu abdullai**

- GitHub: [@yourusername](https://github.com/ABDULLAIOJIKUTU)
- LinkedIn: [Your Profile](https://linkedin.com/in/abdullai-ojikutu)


## 🙏 Acknowledgments

- Inspired by modern event ticketing systems
- Icons from [Font Awesome / Heroicons / etc.]
- Fonts from [Google Fonts]
- QR Code library by [mention if used]

## 📸 Screenshots

### Ticket Form
![Form View](./screenshots/form.png)

### Generated Ticket
![Ticket Preview](./screenshots/ticket.png)

### Mobile View
![Mobile](./screenshots/mobile.png)

---

⭐ Star this repo if you found it helpful!

**Made with ❤️ for conference attendees everywhere**
