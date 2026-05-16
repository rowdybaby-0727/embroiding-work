# 🧵 Prasanna Embroidery – Professional GitHub README

````markdown
<div align="center">

# 🧵 Prasanna Embroidery Website
### *Custom Embroidery Designs Crafted with Creativity & Elegance*

<p align="center">
  A modern embroidery showcase and ordering website with WhatsApp integration for seamless customer communication.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Responsive-Website-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" />
</p>

<p align="center">
  🔗 <a href="https://rowdybaby-0727.github.io/embroiding-work/">Live Demo</a> |
  📂 <a href="https://github.com/rowdybaby-0727/embroiding-work">GitHub Repository</a>
</p>

</div>

---

# 📚 Table of Contents

- [🎯 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [🏗️ System Architecture](#️-system-architecture)
- [🛠️ Technology Stack](#️-technology-stack)
- [📂 Project Structure](#-project-structure)
- [🚀 Quick Start](#-quick-start)
- [📖 Usage Guide](#-usage-guide)
- [📱 WhatsApp Integration](#-whatsapp-integration)
- [📊 Performance & Optimization](#-performance--optimization)
- [🖼️ Results & UI Preview](#️-results--ui-preview)
- [🔧 Configuration Examples](#-configuration-examples)
- [🧪 Troubleshooting](#-troubleshooting)
- [🛣️ Future Enhancements](#️-future-enhancements)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)
- [🙏 Acknowledgments](#-acknowledgments)

---

# 🎯 Overview

## 📌 Problem Statement
Small embroidery businesses often rely on social media messages or manual communication for customer orders. This process can become difficult to manage, especially when handling multiple custom requests.

## 💡 Solution
**Prasanna Embroidery Website** provides a lightweight and responsive web platform where customers can:

- View embroidery designs
- Explore custom services
- Submit order details
- Instantly connect through WhatsApp

The project is designed to help embroidery businesses establish an online presence with minimal complexity and maximum usability.

---

# 🖼️ Live Project Screenshots

## 🎨 Gallery Showcase

<div align="center">
<img src="gallery.png" alt="Embroidery Gallery Showcase" width="1000"/>
</div>

---

# ✨ Key Features

## 🖼️ Embroidery Gallery
- Showcase custom embroidery samples
- Responsive image layout
- Easy-to-update design collection

## 📲 WhatsApp Order Integration
- Customers can place orders directly through WhatsApp
- Automatic message formatting
- Instant communication workflow

## 📱 Responsive Design
- Mobile-friendly UI
- Optimized layout for tablets and desktops
- Smooth navigation experience

## 🎨 Clean User Interface
- Minimalistic and elegant design
- Easy-to-use sections
- Fast-loading static website

## 📞 Contact & Business Information
- Dedicated contact section
- WhatsApp quick access button
- Easy customer interaction

---

# 🏗️ System Architecture

<div align="center">
<img src="architecture diagram.png" alt="Embroidery Website Architecture Diagram" width="900"/>
</div>

## 🔄 Workflow

```text
User Visits Website
        ↓
Views Embroidery Designs
        ↓
Fills Order Form
        ↓
JavaScript Generates WhatsApp Message
        ↓
Redirect to WhatsApp API
        ↓
Business Receives Customer Order
````

---

# 🛠️ Technology Stack

| Category      | Technology   | Purpose                                |
| ------------- | ------------ | -------------------------------------- |
| Frontend      | HTML5        | Website structure                      |
| Styling       | CSS3         | UI styling and responsiveness          |
| Scripting     | JavaScript   | Form handling and WhatsApp integration |
| Hosting       | GitHub Pages | Free website deployment                |
| Communication | WhatsApp API | Customer order messaging               |

---

# 📂 Project Structure

```bash
embroiding-work/
│
├── index.html                 # Main webpage
├── style.css                  # Website styling
├── images/                    # Embroidery design images
│   ├── design1.jpg
│   ├── design2.jpg
│   └── design3.jpg
│
├── docs/
│   ├── images/
│   │   ├── architecture-diagram.png
│   │   ├── ui-preview.png
│   │   └── workflow-diagram.png
│   │
│   └── README-assets/
│
└── README.md
```

---

# 🚀 Quick Start

## 📋 Prerequisites

Before running the project, ensure you have:

* A modern web browser
* Git installed
* Internet connection for WhatsApp integration

---

## 💻 Installation Method 1 – Clone Repository

```bash
# Clone the repository
git clone https://github.com/rowdybaby-0727/embroiding-work.git

# Navigate to project folder
cd embroiding-work
```

---

## 🌐 Run Locally

### Option 1 – Open Directly

```bash
# Open index.html in browser
start index.html
```

### Option 2 – VS Code Live Server

```bash
# Install Live Server Extension
# Right click index.html
# Click 'Open with Live Server'
```

---

# 📖 Usage Guide

## 🏠 Step 1 – Open Website

Launch the website locally or visit the live deployment.

🔗 Live Demo:

```text
https://rowdybaby-0727.github.io/embroiding-work/
```

---

## 🖼️ Step 2 – Explore Designs

Users can browse embroidery samples displayed in the gallery section.

---

## 📝 Step 3 – Fill Order Form

Example form details:

```text
Name: Priya
Design Type: Custom Blouse Embroidery
Details: Floral hand embroidery with golden thread
```

---

## 📲 Step 4 – Send Order via WhatsApp

The website automatically formats and redirects the order request to WhatsApp.

### JavaScript Integration Example

```javascript
function sendToWhatsApp() {
    let name = document.getElementById("name").value;
    let type = document.getElementById("type").value;
    let details = document.getElementById("details").value;

    let message = `Hi, I am ${name}%0ADesign Type: ${type}%0ADetails: ${details}`;

    let url = "https://wa.me/919042394553?text=" + message;

    window.open(url, "_blank");
}
```

---

# 📱 WhatsApp Integration

## 🔗 WhatsApp API Format

```text
https://wa.me/<phone_number>?text=<message>
```

## ✅ Advantages

* Faster customer communication
* No backend required
* Mobile-friendly ordering system
* Easy customer support handling

---

# 📊 Performance & Optimization

| Metric                 | Status |
| ---------------------- | ------ |
| Mobile Responsive      | ✅      |
| Lightweight Design     | ✅      |
| Fast Loading           | ✅      |
| SEO Friendly Structure | ✅      |
| Beginner Friendly      | ✅      |

## ⚡ Optimization Techniques

* Minimal JavaScript usage
* Lightweight CSS styling
* Static website deployment
* Optimized navigation structure

---

# 🖼️ Results & UI Preview

## 🏠 Homepage Preview

<div align="center">
<img src="homepage.png" alt="Embroidery Website Homepage Preview" width="900"/>
</div>

---

## 📲 Mobile Responsive View

<div align="center">
<img src="mobile responsive.png" alt="Mobile Responsive Embroidery Website Preview" width="900"/>
</div>

---

# 🔧 Configuration Examples

## 📞 Update WhatsApp Number

Replace the existing number inside `index.html`:

```javascript
let url = "https://wa.me/919042394553?text=" + message;
```

### Example

```javascript
let url = "https://wa.me/911234567890?text=" + message;
```

---

## 🖼️ Add New Gallery Images

Place new images inside:

```text
images/
```

Then update:

```html
<img src="images/new-design.jpg" alt="New Design">
```

---

# 🧪 Troubleshooting

<details>
<summary>❌ WhatsApp button not working</summary>

### Solution

* Ensure internet connection is active
* Verify WhatsApp number format
* Confirm browser popup permissions

</details>

<details>
<summary>❌ Images not loading</summary>

### Solution

* Verify image paths
* Ensure images exist inside `images/` folder
* Check file extensions (.jpg, .png)

</details>

<details>
<summary>❌ CSS not applying</summary>

### Solution

* Verify `style.css` path
* Clear browser cache
* Ensure stylesheet link exists in `<head>`

</details>

---

# 🛣️ Future Enhancements

## 🚀 Short-Term Goals

* Add more embroidery categories
* Improve UI animations
* Add testimonial section
* Add service pricing cards

## 🌟 Long-Term Goals

* Customer login system
* Online payment integration
* Admin dashboard
* AI-generated embroidery previews
* Order tracking system
* Multi-language support

---

# 🤝 Contributing

Contributions are welcome!

## 📌 Steps to Contribute

```bash
# Fork the repository
# Create a feature branch
git checkout -b feature-name

# Commit your changes
git commit -m "Added new feature"

# Push to GitHub
git push origin feature-name
```

Then create a Pull Request 🚀

---

# 📄 License

This project is licensed under the MIT License.

```text
MIT License © 2026 Prasanna Embroidery
```

---

# 📬 Contact

## 👩‍💻 Developer Information

* GitHub: [https://github.com/rowdybaby-0727](https://github.com/rowdybaby-0727)
* Website: [https://rowdybaby-0727.github.io/embroiding-work/](https://rowdybaby-0727.github.io/embroiding-work/)
* WhatsApp: +91 9042394553

---

# 🙏 Acknowledgments

Special thanks to:

* GitHub Pages for free hosting
* WhatsApp API for communication integration
* Open-source web development community

---

# ⭐ Support the Project

If you found this project useful:

* ⭐ Star the repository
* 🍴 Fork the project
* 🛠️ Contribute improvements
* 📢 Share with others

<div align="center">

## 💖 Thank You for Visiting!

</div>
```
