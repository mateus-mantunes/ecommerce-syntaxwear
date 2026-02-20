# SyntaxWear - Shoes & Sneakers Online 👟

![SyntaxWear](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## 📋 Project Overview

**SyntaxWear** is a modern and responsive e-commerce platform specialized in selling shoes and sneakers online. The website offers an elegant shopping experience with diverse categories and contemporary design focused on comfort and style.

### ✨ Key Features

- **Responsive Design**: Fully adapted for mobile devices, tablets, and desktops
- **Mobile Menu**: Intuitive navigation with hamburger menu for smaller devices
- **Hero Section**: Visual highlight section with call-to-action
- **Product Categories**: Casual, Sport, Modern, and Futuristic
- **Product Grid**: Elegant product grid display
- **Newsletter**: Newsletter subscription form
- **Social Media**: Links to Instagram, WhatsApp, TikTok, and Facebook
- **Complete Footer**: Footer navigation with multiple sections

---

## 📁 Folder Structure

```
ecommerce-syntaxwear/
│
├── 📄 index.html                 # Main website file
├── 📄 README.md                  # Project documentation
├── 📁 assets/                    # Resources folder
│   │
│   ├── 📁 css/                   # Organized CSS styles
│   │   ├── reset.css             # Reset default styles
│   │   ├── variables.css         # Color and size variables
│   │   ├── base.css              # Base general styles
│   │   ├── header.css            # Header styles
│   │   ├── hero.css              # Hero section styles
│   │   ├── product-category.css  # Category styles
│   │   ├── product-grid.css      # Product grid styles
│   │   ├── footer.css            # Footer styles
│   │   └── layout.css            # Responsive layout
│   │
│   └── 📁 images/                # Website images
│       ├── 📁 banners/           # Banner images
│       ├── 📁 favicons/          # Browser icons
│       ├── 📁 icons/             # Website icons
│       ├── 📁 logo/              # Site logo
│       └── 📁 products/          # Product images
│
└── 📁 .git/                      # Git repository

```

---

## 🛠️ Technologies Used

- **HTML5**: Semantic and responsive structure
- **CSS3**: Modern styles with Flexbox and Grid
- **CSS Variables**: For easy maintenance of colors and sizes
- **Responsive Design**: Mobile-first approach

---

## 📦 Website Sections

### 1️⃣ **Header**
- SyntaxWear brand logo
- Main navigation menu with categories (Men, Women, Outlet)
- Side menu with links (Our Stores, About)
- User, favorites, and shopping cart icons
- Responsive mobile menu with hamburger icon

### 2️⃣ **Hero Section**
- Featured image with overlay
- Title: "Transform every step into presence"
- Subtitle: "Krypton One"
- Two CTA buttons: "View Models" and "Shop Now"

### 3️⃣ **Categories Section**
Four main product categories:
- **Casual**: Shoes for everyday use
- **Sport**: Shoes for physical activities
- **Modern**: Contemporary styles
- **Futuristic**: Innovative designs

### 4️⃣ **Product Grid**
- Featured card (Krypton One) with gender options
- Responsive grid with images of various models
- Various designs: purple sneaker, featured model, color sneaker, white sneaker, silver sneaker

### 5️⃣ **Footer**
- **Newsletter**: Email subscription form
- **Social Media**: Links to Instagram, WhatsApp, TikTok, and Facebook
- **Navigation**: Structure with 5 columns
  - Men (with subcategories)
  - Women (with subcategories)
  - Outlet
  - Our Stores
  - About
- **Copyright**: Rights reserved message

---

## 🚀 How to Use

### Requirements
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code recommended)
- Local server (Live Server or similar)

### Steps to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/ecommerce-syntaxwear.git
   cd ecommerce-syntaxwear
   ```

2. **Open the HTML file**:
   - Option 1: Open `index.html` directly in your browser
   - Option 2: Use Live Server in VS Code (right-click > Open with Live Server)
   - Option 3: Use a local Python server
     ```bash
     python -m http.server 8000
     # Then access: http://localhost:8000
     ```

3. **Navigate through the site**:
   - Explore the categories
   - Test the mobile menu (responsive)
   - Interact with buttons and links

---

## 🎨 Style Guide

### Main Colors
Colors are defined in `variables.css` and include:
- **Primary**: Colors that reference the tech/futuristic theme
- **Secondary**: Gray tones for neutrality
- **Highlight**: Vibrant colors for CTAs

### Typography
- Base font for body and texts
- Responsive sizes based on viewport

### Reusable Components
- **Buttons**: `btn btn-outline` and `btn btn-filled`
- **Cards**: Different card types for products
- **Links**: Styled with hover effects

---

## 📱 Responsiveness

The site is fully responsive with breakpoints for:
- **Mobile**: up to 768px
- **Tablet**: 768px to 1024px
- **Desktop**: above 1024px

Mobile menu automatically appears on small devices with hamburger icon.

---

## 🔄 Navigation Flow

```
Home (index.html)
├── Hero Section
│   └── Action buttons → View Models / Shop Now
├── Categories
│   ├── Casual
│   ├── Sport
│   ├── Modern
│   └── Futuristic
├── Product Grid
│   └── Featured products
└── Footer
    ├── Newsletter
    ├── Social Media
    ├── Navigation
    └── Copyright
```

---

## 🌐 Meta Tags and SEO

- **Title**: "SyntaxWear - Shoes & Sneakers Online"
- **Description**: "Buy shoes and sneakers online at SyntaxWear. Find the best models for style and comfort. Free shipping throughout Brazil!"
- **Viewport**: Configured for mobile-first
- **Charset**: UTF-8 for Portuguese character support

---

## 📝 Semantic HTML Structure

The project uses semantic HTML5 elements:
- `<header>`: Website header
- `<main>`: Main content
- `<section>`: Content sections
- `<nav>`: Navigation elements with `aria-label`
- `<footer>`: Website footer
- `<form>`: Newsletter form

---

## ✅ Future Features

- [ ] Individual product pages
- [ ] Functional shopping cart
- [ ] Login/registration system
- [ ] Advanced search filters
- [ ] Reviews and comments
- [ ] Payment gateway integration
- [ ] Support chat
- [ ] Admin dashboard
- [ ] Wishlist/favorites

---

## 🤝 How to Contribute

1. **Fork** the project
2. Create a branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

---

## 💡 Development Tips

### Editing Styles
- Global colors are in [assets/css/variables.css](assets/css/variables.css)
- Each section has its own CSS file for better organization
- Use reusable classes to maintain consistency

### Adding New Products
- Add new cards in the `grid-section` of the HTML
- Use the `card` class with additional classes for styling
- Place images in the [assets/images/products/](assets/images/products/) folder

### Testing Responsiveness
- Use browser DevTools (F12)
- Test at different screen sizes
- Check the mobile menu on small screens

---

## 📄 License

This project is under the MIT license. See the LICENSE file for more details.

---

## 👨‍💻 Author

Developed as a study project for the **Dev Quest** course.

---

## 📞 Contact and Support

- 📧 Email: contato@syntaxwear.com
- 🐦 Twitter: [@syntaxwear](https://twitter.com)
- 📸 Instagram: [@syntaxwear](https://instagram.com)
- 💬 WhatsApp: [SyntaxWear](https://wa.me)

---

## 🙏 Acknowledgments

- Inspiration from international sneaker shops
- Dev Quest community
- Everyone who contributes to improving the project

---

**Last update**: February 20, 2026
