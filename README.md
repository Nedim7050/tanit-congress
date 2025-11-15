# TANIT 2K25 - AIESEC Carthage Congress Website

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/Nedim7050/tanit-congress?style=social)](https://github.com/Nedim7050/tanit-congress)
[![GitHub forks](https://img.shields.io/github/forks/Nedim7050/tanit-congress?style=social)](https://github.com/Nedim7050/tanit-congress)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)

**An official website for TANIT 2K25, an international congress hosted by AIESEC Carthage**

[Live Demo](#) • [Documentation](#) • [Report Bug](https://github.com/Nedim7050/tanit-congress/issues) • [Request Feature](https://github.com/Nedim7050/tanit-congress/issues)

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-key-features)
- [Screenshots](#-screenshots)
- [Technologies](#-technologies-used)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Usage](#-usage)
- [Performance](#-performance)
- [Browser Support](#-browser-support)
- [Contributing](#-contributing)
- [Author](#-author)
- [Contact](#-contact)
- [License](#-license)

---

## ✨ Overview

**TANIT 2K25** is a transformative international congress designed to empower delegates through connection, growth, and impactful learning. This interactive website serves as the primary digital hub for event information, registration, and engagement.

### 🎯 Project Purpose

- **Event Information Hub**: Comprehensive information about TANIT 2K25 congress
- **Registration Platform**: Streamlined registration process for Tunisian and International delegates
- **Committee Showcase**: Dynamic display of congress committee members
- **Activity Discovery**: Interactive showcase of main congress activities
- **Testimonials**: Insights and feedback from previous TANIT editions

---

## 🎯 Key Features

### 🚀 Core Functionality
- ✈️ **Interactive Hero Section** - Animated airplane flight simulation with sinusoidal trajectory
- 📝 **Multi-language Registration** - Separate optimized forms for Tunisian (200 DT) and International (120 €) delegates
- 👥 **Committee Showcase** - Dynamic team member display with smooth GSAP animations
- 🎨 **Activity Gallery** - Visual showcase of main congress activities
  - Become a Trainer certification program
  - Football Tournament
  - Networking sessions
  - Workshops & Interactive sessions

### 🎨 Design & User Experience
- 📱 **Fully Responsive Design** - Optimized for mobile, tablet, and desktop devices
- ⚡ **Modern UI/UX** - Clean, professional interface with smooth animations
- 🎬 **Scroll Animations** - AOS (Animate On Scroll) library integration
- 🎭 **Dynamic Interactions** - Hover effects, card animations, and interactive elements
- 🌈 **Custom Styling** - Branded color scheme matching TANIT 2K25 identity

### 🛠️ Technical Features
- ⚡ **Performance Optimized** - Lazy loading images, optimized assets
- 🔄 **Dynamic Content** - JavaScript-powered interactive components
- 📊 **Form Validation** - Client-side validation for registration forms
- 🎯 **SEO Friendly** - Semantic HTML structure and meta tags

---

## 📸 Screenshots

> _Screenshots section - Add your project screenshots here_

### Homepage
![Homepage](https://via.placeholder.com/800x400?text=TANIT+2K25+Homepage)

### Registration Forms
![Registration](https://via.placeholder.com/800x400?text=Registration+Forms)

### Committee Showcase
![Committee](https://via.placeholder.com/800x400?text=Committee+Showcase)

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with animations and responsive design
- **JavaScript (ES6+)** - Interactive functionality and dynamic content
- **Bootstrap 5** - Responsive framework and grid system
- **GSAP 3.12** - Advanced animations library
- **AOS (Animate On Scroll)** - Scroll-triggered animations

### Services & Tools
- **Cloudinary** - Image hosting and optimization
- **Vimeo API** - Video embedding and playback
- **Font Awesome** - Icon library
- **Google Fonts** - Typography (Montserrat, Dancing Script, Poppins)

### Development Tools
- **Gulp** - Task runner and build system
- **Pug** - Template engine (source files)
- **SCSS/Sass** - CSS preprocessor (source files)
- **Git** - Version control

---

## 🚀 Installation

### Prerequisites

Ensure you have the following installed:
- **Node.js** (v14.0.0 or higher) - [Download](https://nodejs.org/)
- **npm** (v6.0.0 or higher) or **yarn** package manager
- **Git** - [Download](https://git-scm.com/)

### Step-by-Step Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nedim7050/tanit-congress.git
   cd tanit-congress
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Development workflow (Optional)**
   
   For using the Gulp-based build system:
   ```bash
   gulp
   ```

4. **View the website**
   
   You can either:
   - Open the `public/index.html` file directly in your browser, or
   - Use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (npx)
     npx serve public
     
     # Using PHP
     php -S localhost:8000 -t public
     ```

5. **Access the website**
   
   Navigate to `http://localhost:8000` in your browser

---

## 📁 Project Structure

```
tanit-congress/
│
├── public/                          # Production-ready files
│   ├── assets/
│   │   ├── css/                    # Compiled CSS files
│   │   │   ├── theme.css
│   │   │   └── theme-rtl.css
│   │   ├── img/                    # Images and icons
│   │   │   ├── plane-emoji.png    # Animated plane image
│   │   │   ├── favicons/
│   │   │   └── ...
│   │   └── js/                     # JavaScript files
│   │       └── theme.js
│   ├── vendors/                    # Third-party libraries
│   ├── index.html                  # Main homepage
│   ├── registration-tunisian.html  # Registration form (Tunisian)
│   ├── registration-international.html # Registration form (International)
│   ├── registration.html           # Generic registration
│   ├── boardingpass.html           # Boarding pass generator
│   └── 404.html                    # Error page
│
├── src/                            # Source files
│   ├── pug/                        # Pug templates
│   │   ├── mixins/
│   │   └── ...
│   └── scss/                       # SCSS stylesheets
│       ├── theme.scss
│       └── ...
│
├── gulpfile.js                     # Gulp configuration
├── package.json                    # Project dependencies
└── README.md                       # This file
```

---

## 💻 Usage

### Basic Usage

1. Navigate to the homepage (`public/index.html`)
2. Browse through sections:
   - **About** - Watch the introduction video
   - **Activities** - Discover main congress activities
   - **Registration** - Choose your registration type
   - **Committee** - Meet the team
   - **Testimonials** - Read participant feedback

### Registration Process

#### For Tunisian Delegates:
1. Click "Registration for Tunisians" button
2. Fill out the registration form
3. Total fee: **200 DT** (3 days, 2 nights)

#### For International Delegates:
1. Click "Registration for Internationals" button
2. Fill out the registration form
3. Total fee: **120 €** (3 days, 2 nights)

### Customization

To customize the website:

1. **Colors**: Modify CSS variables in `public/assets/css/theme.css`
2. **Content**: Edit HTML files in the `public/` directory
3. **Images**: Replace images in `public/assets/img/`
4. **Animations**: Adjust animation parameters in JavaScript sections

---

## ⚡ Performance

- **Optimized Images**: All images are optimized and hosted on Cloudinary
- **Lazy Loading**: Images use lazy loading for faster initial page load
- **Minified Assets**: CSS and JavaScript are minified for production
- **CDN Resources**: External libraries loaded from CDN for caching

---

## 🌐 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | Latest |
| Firefox | Latest |
| Safari | Latest |
| Edge | Latest |
| Opera | Latest |
| iOS Safari | Latest |
| Chrome Mobile | Latest |

---

## 📝 Event Details

| Property | Value |
|----------|-------|
| **Event Name** | TANIT 2K25 |
| **Host** | AIESEC Carthage |
| **Venue** | African Queen Hotel Hammamet |
| **Date** | August 29-31, 2025 |
| **Duration** | 3 days (2 nights) |
| **Tunisian Fee** | 200 DT |
| **International Fee** | 120 € |

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines

- Follow the existing code style
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation as needed

---

## 👤 Author

<div align="center">

### **Nedim Mejri**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nedim7050)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nedim-mejri)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nedim.mejri@example.com)

</div>

**About the Author:**

- 💻 **Full-Stack Web Developer** specializing in frontend development
- 🎯 **Congress Committee Member** - DXP (Digital Experience Portfolio) at TANIT 2K25
- 🌟 **AIESEC Carthage** - Active member and contributor
- 🚀 Passionate about creating engaging user experiences and modern web applications

**Skills & Expertise:**
- HTML5, CSS3, JavaScript (ES6+)
- Bootstrap, Responsive Design
- GSAP Animations, AOS
- Git & Version Control
- Web Performance Optimization

---

## 📞 Contact

For inquiries, collaborations, or questions about this project:

<div align="center">

**Nedim Mejri**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Nedim7050)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nedim.mejri@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nedim-mejri)

**Email**: nedim.mejri@example.com *(Replace with your actual email)*  
**GitHub**: [@Nedim7050](https://github.com/Nedim7050)

---

### Event Contact & Links

**TANIT 2K25 Official Channels:**
- 📷 **Instagram**: [@ittt_tanit](https://www.instagram.com/ittt_tanit)
- 📘 **Facebook Group**: [TANIT 2K25](https://www.facebook.com/groups/1031234249068230)
- ✉️ **General Inquiries**: ineshamdoun25@gmail.com

</div>

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Nedim Mejri

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- **ThemeWagon** - Original Jadoo theme inspiration
- **AIESEC Carthage** - For the opportunity and support
- **TANIT 2K25 Congress Committee** - All team members for their contributions
- **Previous TANIT Participants** - For valuable testimonials and feedback
- **Open Source Community** - For amazing tools and libraries

---

<div align="center">

### ⭐ Star this repository if you find it helpful!

**Made with ❤️ by [Nedim Mejri](https://github.com/Nedim7050) for TANIT 2K25**

[⬆ Back to Top](#tanit-2k25---aiesec-carthage-congress-website)

</div>
