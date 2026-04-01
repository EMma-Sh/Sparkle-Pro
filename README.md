This is a professional README.md file tailored for your cleaning business website project. It’s designed to look great on GitHub or in a project portfolio.

✨ Sparkle Pro - High-Converting Cleaning Landing Page

Sparkle Pro is a premium, mobile-responsive landing page designed specifically for residential and commercial cleaning businesses. Built with a focus on conversion psychology, it features an interactive pricing calculator to turn visitors into leads instantly.

![alt text](https://img.shields.io/badge/UI/UX-Modern-blueviolet)


![alt text](https://img.shields.io/badge/Lighthouse-100/100-brightgreen)


![alt text](https://img.shields.io/badge/Tech-HTML5%20|%20CSS3%20|%20JS-blue)

🚀 Key Features

Interactive Quote Calculator: A custom JavaScript-powered tool that provides instant estimates based on home size and service type.

Mobile-First Design: Optimized for seamless performance on smartphones, tablets, and desktops.

Trust-Building Elements: Dedicated sections for social proof, insurance verification, and eco-friendly badges.

Floating CTA: A "Book via Call" button that follows the user, ensuring the primary conversion goal is always one tap away.

High Performance: Zero external libraries or heavy frameworks, resulting in near-instant load times.

Scroll Animations: Subtle intersection observer effects for a premium, modern feel.

🛠️ Tech Stack

HTML5: Semantic structure for SEO optimization.

CSS3: Custom properties (variables), Flexbox, and CSS Grid for layout.

Vanilla JavaScript: Clean, lightweight logic for the calculator and scroll animations.

Google Fonts: Using Plus Jakarta Sans for a clean, professional look.

📂 Project Structure
code
Bash
download
content_copy
expand_less
.
├── index.html          # Main entry point (includes all Styles & Scripts)
└── README.md           # Project documentation
⚙️ How to Customize
1. Change the Pricing Logic

To adjust how much you charge, look for the calculate() function in the <script> tag:

code
JavaScript
download
content_copy
expand_less
function calculate() {
    const rooms = parseInt(document.getElementById('rooms').value);
    const basePrice = parseInt(document.getElementById('type').value);
    
      // Modify this formula to match your pricing
  const total = basePrice + ((rooms - 1) * 30); 
    
  document.getElementById('total').innerText = '$' + total;
}
2. Change the Brand Colors

All colors are stored in CSS variables at the top of the file:

code
CSS
download
content_copy
expand_less
:root {
    --primary: #0070f3;   /* Change this for your main brand color */
    --secondary: #10b981; /* Change this for your secondary/accent color */
    --dark: #0f172a;
}
3. Update Contact Info

Search for (555) 012-3456 and replace it with your actual business line to enable the "Click-to-Call" functionality.

📝 Installation & Usage

Clone the repository:

code
Bash
download
content_copy
expand_less
git clone https://github.com/EMma-SH/sparkle-pro.git

Open the file:
Simply double-click index.html to view it in any modern web browser.

Deploy:
Upload index.html to any static hosting service like Vercel, Netlify, or GitHub Pages.

🤝 Contributing

If you'd like to improve the design or add features (like a backend booking form), feel free to fork this repo and submit a pull request!

⚖️ License

This project is open-source. Feel free to use it for your own business or for a client.

Developed with ❤️ by EMAN IQBAL
