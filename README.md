# Style Mobile - E-commerce Website

A professional e-commerce website for Style Mobile, a mobile accessories store in Maharagama, Sri Lanka.

## 📋 Project Overview

This is a complete e-commerce solution featuring:
- **Customer Frontend**: Home page, product shop, shopping cart, and checkout
- **Admin Dashboard**: Product management, order tracking, and store settings
- **Payment Integration**: Support for Koko, Bank Transfer, and Card payments
- **Social Media Integration**: WhatsApp, Facebook, and TikTok links
- **Responsive Design**: Mobile-first design optimized for all devices

## 📁 File Structure

### HTML Files (Standalone)
- **index.html** - Home page with featured products and hero section
- **shop.html** - Product listing with filtering and sorting
- **cart.html** - Shopping cart with checkout process
- **admin.html** - Admin dashboard for managing products and orders

### React/TypeScript Files (Full-Stack)
- **client/src/pages/** - React page components
  - Home.tsx - Home page component
  - Shop.tsx - Shop page component
  - Cart.tsx - Cart page component
  - AdminDashboard.tsx - Admin dashboard component
- **client/src/App.tsx** - Main app with routing
- **client/src/index.css** - Global styles with brand colors

### Design Assets
- **ideas.md** - Design philosophy and style guide
- **Logo** - Style Mobile brand logo (stored in webdev-static-assets)

## 🎨 Design Philosophy

**Modern Tech-Forward Minimalism** with:
- Clean white backgrounds with vibrant orange (#FF6B35) and cyan (#0099FF) accents
- Plus Jakarta Sans + Inter typography pairing
- Smooth animations and hover effects
- Mobile-first responsive design
- Accessibility-focused UI

## 🚀 Quick Start

### Option 1: Using HTML Files (Simple Deployment)
1. Copy all `.html` files to your web server
2. Ensure images load from CDN URLs
3. Open `index.html` in a browser
4. No build process required!

### Option 2: Using React/TypeScript (Full-Stack)
```bash
cd style-mobile-ecommerce
pnpm install
pnpm dev
```

## 📱 Pages & Features

### Customer Pages

#### Home (index.html)
- Hero section with call-to-action
- Featured products showcase
- Key features highlight
- Payment methods display
- Contact information with social links
- Footer with navigation

#### Shop (shop.html)
- Product grid with filtering
- Category sidebar
- Sorting options
- Product cards with ratings
- Add to cart functionality

#### Cart (cart.html)
- Shopping cart items display
- Order summary with pricing breakdown
- Checkout modal with shipping form
- Payment method selection
- Support for Koko, Bank Transfer, and Card payments

### Admin Pages

#### Admin Dashboard (admin.html)
- Dashboard with key statistics
- Recent orders table
- Product management
- Order tracking
- Store settings
- Payment configuration

## 💳 Payment Methods

### 1. Koko Payment
- Fast mobile payment gateway
- Secure transaction processing
- Instant confirmation

### 2. Bank Transfer
- Direct bank transfer option
- Manual confirmation via WhatsApp
- Reliable and secure

### 3. Card Payment
- Visa and Mastercard support
- Secure payment processing
- Immediate confirmation

## 📞 Contact Information

- **Address**: 8 Piliyandala - Maharagama Rd, Maharagama 10280, Sri Lanka
- **Phone**: 077 550 6050
- **WhatsApp**: https://wa.me/94775506050
- **Facebook**: https://web.facebook.com/stylemobilelk
- **TikTok**: https://www.tiktok.com/@stylemobilelk

## 🛠️ Customization

### Updating Products
Edit the product data in the respective HTML files or use the admin dashboard to add/edit products.

### Changing Colors
Update the color values in the CSS:
- Primary Orange: `#FF6B35`
- Secondary Cyan: `#0099FF`
- Background: `#FFFFFF`
- Text: `#1A1A1A`

### Adding New Pages
Create new `.html` files following the existing template structure or add new React components in `client/src/pages/`.

## 📊 Admin Features

- **Dashboard**: View key metrics and recent orders
- **Products**: Add, edit, delete products with categories
- **Orders**: Track order status and manage shipments
- **Settings**: Configure store details and payment methods

## 🔒 Security Notes

- Store sensitive payment information securely
- Use HTTPS for all transactions
- Implement proper authentication for admin panel
- Validate all user inputs on the server side
- Keep payment gateway API keys secure

## 📈 Performance

- Optimized images using CDN
- Minimal CSS and JavaScript
- Fast page load times
- Mobile-optimized design
- Responsive grid layouts

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

All rights reserved © 2026 Style Mobile

## 🤝 Support

For technical support or inquiries:
- WhatsApp: 077 550 6050
- Facebook: https://web.facebook.com/stylemobilelk
- Email: Contact via social media

---

**Version**: 1.0.0  
**Last Updated**: May 12, 2026  
**Built with**: HTML5, CSS3, JavaScript, React, TypeScript, Tailwind CSS
