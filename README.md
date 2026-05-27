# 🕰️ Time-Vault: Premium Timex Watches E-Commerce Website

A fully responsive, elegant, and modern e-commerce landing page showcasing Timex watch collections. **Time-Vault** features a dark and light theme, seamless interactive sliders, smooth scroll navigation, and a luxury-themed aesthetic tailored to captivate users.

---

## 📱 Preview Image

![Time-Vault Mockup] <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4aefb20b-2257-4aba-8c2d-d7e8f7c992a6" />

---

## 🚀 Key Features

- **🌓 Dynamic Theme Toggle**: Seamless transition between dark and light themes, with user preference saved automatically in `localStorage`.
- **📱 Fully Responsive Design**: Built from the ground up to support all screen types, from large-screen desktop displays to tablets and mobile devices.
- **✨ Micro-Animations & Hover Effects**: Luxury hover effects on cards, navigation elements, buttons, and social links that make the UI feel alive and responsive.
- **🎠 Swiper Integration**: Manual Card Sliding effect.
  - **Testimonial Slider**: Auto-looping slider for corporate reviews with custom navigation arrows.
  - **New Arrivals Carousel**: Breakpoint-optimized carousel that displays a responsive number of products based on viewport width (1 to 4 items).
- **⚓ Interactive Smooth Navigation**:
  - Custom scroll-active highlighting that updates the navigation bar link as the user scrolls.
  - Scroll-triggered sticky header with blur and drop shadow effects.
- **🔝 Scroll-to-Top Action**: A convenient back-to-top shortcut button that appears dynamically after scrolling past a threshold.
- **🛍️ Professional E-Commerce Sections**:
  - **Hero Landing**: Showcasing a premium flagship watch with details and direct shopping CTAs.
  - **Featured Grid**: Focuses on sale items with dynamic shop hover buttons.
  - **Brand Story**: Highlights Timex's history in a structured layout.
  - **Product Showcase**: Detailed grid containing various product segments (Classic, Automatic, Weekender, etc.) with preview buttons.
  - **Newsletter Subscription**: Stylized form for promotions and updates.

---

## 🛠️ Technology Stack

| Technology / Library | Version / Source | Purpose |
| :--- | :--- | :--- |
| **HTML5** | Semantic Standard | Document structure and SEO accessibility |
| **Vanilla CSS3** | Custom Variables | Theming, layout (Flexbox/Grid), transitions, and style tokens |
| **JavaScript** | ES6+ Standard | DOM manipulation, swipers, themes, and scroll effects |
| **Swiper JS** | 8.x (Local bundle) | Responsive slider and carousel animations |
| **Boxicons** | 2.1.4 (CDN) | Modern, clean vector icons for navigation, features, and UI controls |
| **Google Fonts** | Roboto (400, 500, 700) | Premium, clean typography for optimal readability |

---

## 📂 Project Directory Structure

```text
Watches-Website-Timex-FW/
│
├── Images/                         # Asset Directory (Watch Images, Logos, and Mockup)
│   ├── Fav.svg                     # Website Favicon
│   ├── Home-watch.png              # Flagship watch image (Hero section)
│   ├── Featured-1.png to 3.png     # Featured collection products
│   ├── Product-1.png to 6.png      # Product section images
│   ├── New-1.png to 4.png          # New Arrivals carousel images
│   ├── Story-watch.jpeg            # Historical story brand image
│   ├── Men-with-watch.jpeg         # Testimonial sidebar decorative photo
│   ├── Testimonails-pfp.png        # Testimonial avatar
│   └── website_preview.png         # Multi-device layout preview (Desktop/Tablet/Mobile)
│
├── index.html                      # Core HTML Document (Structured with SEO tags)
├── styles.css                      # Master stylesheet containing styles, themes, & variables
├── main.js                         # Custom JavaScript logic for theme toggling, menu, & scroll
├── swiper-bundle.min.css           # Local stylesheet for Swiper carousel slider
└── swiper-bundle.min.js            # Local JavaScript library for Swiper carousel slider
```

---

## 🔧 Getting Started

### 📋 Prerequisites
To view and run this project, all you need is a modern web browser (e.g., Chrome, Edge, Safari, Firefox) and a code editor (like VS Code).

### 🚀 Running the Project
1. **Clone or Download the Repository**:
   ```bash
   git clone https://github.com/Amit-Patra-04/Watches-Website-Timex-FW.git
   ```
2. **Navigate into the Project Folder**:
   ```bash
   cd Watches-Website-Timex-FW
   ```
3. **Open the Website**:
   - Double-click the `index.html` file to open it in your default browser.
   - *Alternatively (Recommended)*: Use a local development server like **Live Server** in VS Code to run it at a local IP address (e.g., `http://127.0.0.1:5500/index.html`) to support all features seamlessly.

---

## 🎨 Theme & Typography Customization

The project uses modular CSS custom properties (variables) defined at the `:root` level, making color theme customization incredibly easy. 

To change the primary gold/accent colors or theme colors, modify the variables inside the `styles.css` file:

```css
:root {
    /* Primary Accent Color (Gold/Orange-Yellow) */
    --first-color: hsl(31, 100%, 70%);
    
    /* Layout Backgrounds */
    --body-color: hsl(0, 0%, 99%);
    --container-color: #fff;
    
    /* Typography Font Family */
    --body-font: 'Roboto', sans-serif;
}

/* Dark Mode Overrides */
body.dark-theme {
    --first-color: hsl(31, 76%, 74%);
    --body-color: hsl(0, 0%, 12%);
    --container-color: hsl(0, 0%, 16%);
}
```

---

## 📱 Responsive Breakpoints

The stylesheet employs CSS Media Queries to adapt the grid layouts and font sizes across four viewport tiers:
- **Mobile Devices (up to 767px)**: Collapsible sidebar menu navigation, single-column main content, and smaller headings.
- **Medium Screens / Tablets (from 576px / 768px)**: Flexed story layout, dual-column product cards, and 2-to-3 item carousels.
- **Desktop Screens (968px and up)**: Full horizontal header navigation, fixed position scroll elements, three-column grids, and larger luxury font sizes.
- **Large Desktops (1024px and up)**: Set container constraints at `1024px` width to maintain layout symmetry.

---

## ✒️ Credits

- **Libraries**:
  - [Swiper JS](https://swiperjs.com/) for sliders.
  - [Boxicons](https://boxicons.com/) for iconography.
- **Design Inspiration**: Modern premium minimalistic watches e-commerce layouts.
