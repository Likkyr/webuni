# Uni402 - Pay-per-Knowledge Platform

![Uni402 Logo](/UNI402_logo.png)

Uni402 is a modern web platform for micro-payments in knowledge sharing, powered by Solana blockchain and x402 protocol. The platform enables creators to monetize educational content and users to access premium knowledge instantly without subscriptions.

## ✨ Features

- **Discover Lessons**: Browse through categorized educational content
- **Instant Access**: Unlock lessons with one-click micro-payments (0.01-0.05 USDC)
- **Create Content**: Publish your own lessons and earn from each unlock
- **Wallet Integration**: Connect Phantom Wallet for seamless transactions
- **No Subscriptions**: Pay only for what you need, when you need it
- **Instant Payments**: Transactions complete in under 10 seconds
- **Content Protection**: Blockchain-verified access records

## 🏗️ Project Structure

```
uni402/
├── index.html              # Homepage with lesson discovery
├── lesson.html            # Individual lesson page
├── create.html           # Lesson creation page
├── style.css            # Main stylesheet
├── script.js            # Core JavaScript functionality
├── UNI402_logo.png      # Platform logo
└── favicon.ico         # Site favicon
```

## 🚀 Quick Start

### Option 1: Local Development
1. Clone or download the project
2. Open `index.html` in your browser
3. Install [Phantom Wallet](https://phantom.app/) extension for full functionality

### Option 2: Live Demo
Open the hosted version at: [https://uni402-demo.netlify.app](https://uni402-demo.netlify.app)

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Grid, Flexbox, CSS Custom Properties
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Inter)
- **Markdown**: marked.js for content rendering
- **Blockchain**: Solana, Phantom Wallet integration
- **Payments**: USDC tokens, x402 protocol

## 🎨 Design Features

### UI/UX
- Modern dark theme with gradient accents
- Fully responsive design (mobile-first approach)
- Smooth animations and hover effects
- Glassmorphism design elements
- Intuitive navigation and user flows

### Components
- Interactive lesson cards with category filters
- Modal payment interface
- Real-time notifications
- Loading states and error handling
- Form validation and feedback

## 📱 Pages Overview

### 1. Homepage (`index.html`)
- Hero section with platform introduction
- Featured lessons grid
- Category filtering system
- Platform statistics
- "How it works" section

### 2. Lesson Page (`lesson.html`)
- Detailed lesson view
- Locked/unlocked content states
- Payment integration
- Related lessons
- Author information

### 3. Create Page (`create.html`)
- Lesson creation form
- Price selection (0.01-0.50 USDC)
- Content type options (text, video, PDF, etc.)
- Category and tag management
- Preview and publishing

## 💡 How It Works

### For Learners
1. **Connect Wallet**: Link your Phantom Wallet
2. **Browse Lessons**: Explore content by category
3. **Unlock Access**: Make a micro-payment (0.01-0.05 USDC)
4. **Learn Instantly**: Access content immediately
5. **Own Forever**: Permanent access to purchased lessons

### For Creators
1. **Connect Wallet**: Link your Phantom Wallet
2. **Create Lesson**: Fill out the lesson creation form
3. **Set Price**: Choose between 0.01-0.50 USDC
4. **Publish**: Make your lesson available worldwide
5. **Earn 95%**: Keep 95% of every sale

## 🔧 Technical Implementation

### Core JavaScript Functions
```javascript
// Wallet Management
initPhantomWallet()    // Connect Phantom Wallet
disconnectWallet()     // Disconnect wallet
checkPhantomSupport() // Check browser compatibility

// Lesson Management
loadLessons()          // Load lesson data
filterLessons()        // Filter by category
loadLesson()          // Load specific lesson
createLesson()        // Create new lesson

// Payment System
processPayment()       // Handle payment flow
checkLessonAccess()   // Verify user access
unlockLesson()        // Grant content access
```

### Mock Data Structure
The platform includes 24 demonstration lessons across 10 categories:
- Web3 & Blockchain (5 lessons)
- Programming (6 lessons)
- Cryptocurrency (3 lessons)
- DeFi (1 lesson)
- NFTs (1 lesson)
- AI & ML (1 lesson)
- Business (1 lesson)
- Design (1 lesson)
- Marketing (2 lessons)
- Personal Development (2 lessons)

### CSS Architecture
- CSS Custom Properties for theming
- Mobile-first responsive design
- Component-based styling
- Animation keyframes
- Utility classes

## 🎯 Key Features in Detail

### 1. Wallet Integration
- Phantom Wallet detection and connection
- Address display and management
- Transaction signing simulation
- Network fee estimation

### 2. Lesson Discovery
- Grid layout with hover effects
- Real-time filtering by category
- Search functionality (coming soon)
- Sorting options (coming soon)

### 3. Payment Flow
- Modal payment interface
- Price confirmation
- Transaction simulation
- Success/failure states
- Access verification

### 4. Content Management
- Markdown support for text content
- Video embedding (YouTube/Vimeo)
- PDF preview and download
- Interactive content support

## 📱 Responsive Design

The platform is fully responsive with breakpoints at:
- **Desktop**: >1024px
- **Tablet**: 768px - 1024px
- **Mobile**: <768px
- **Small Mobile**: <480px

## 🎨 Color Scheme

```css
:root {
    --primary: #8b5cf6;      /* Purple */
    --secondary: #3b82f6;    /* Blue */
    --accent: #10b981;       /* Green */
    --bg-dark: #0f172a;      /* Dark Blue */
    --text-dark: #f9fafb;    /* Light Gray */
}
```

## 🔒 Security Features

- HTML content escaping
- Input validation
- Mock payment simulation (production-ready for real integration)
- Content protection until payment
- Access tracking

## 🚀 Getting Started for Development

### Prerequisites
- Modern web browser
- Code editor (VS Code recommended)
- Basic understanding of HTML/CSS/JavaScript

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/uni402.git
   cd uni402
   ```

2. Install recommended VS Code extensions:
   - Live Server
   - ESLint
   - Prettier

3. Open with Live Server or directly in browser

## 📈 Future Enhancements

### Phase 1 (Coming Soon)
- [ ] Real Solana blockchain integration
- [ ] Actual USDC transactions
- [ ] User authentication system
- [ ] Lesson ratings and reviews

### Phase 2 (Planned)
- [ ] Creator dashboard
- [ ] Analytics and insights
- [ ] Social sharing features
- [ ] Mobile app development

### Phase 3 (Roadmap)
- [ ] Multi-language support
- [ ] Advanced search filters
- [ ] Bundles and discounts
- [ ] Affiliate program

## 🧪 Testing

### Manual Testing Checklist
- [ ] Wallet connection/disconnection
- [ ] Lesson filtering by category
- [ ] Payment flow simulation
- [ ] Content unlocking
- [ ] Form validation
- [ ] Responsive design on all devices
- [ ] Cross-browser compatibility

### Browser Support
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow existing code style
- Add comments for complex logic
- Test changes thoroughly
- Update documentation as needed

## 📄 License

© 2024 Uni402. All rights reserved.

This project is for demonstration purposes. Commercial use requires proper licensing.

## 👥 Team

- **Frontend Development**: Your Name
- **UI/UX Design**: Your Name
- **Blockchain Integration**: Coming Soon
- **Project Management**: Your Name

## 📞 Contact & Support

- **GitHub Issues**: [Report bugs or request features](https://github.com/yourusername/uni402/issues)
- **Email**: support@uni402.com (coming soon)
- **Twitter**: [@Uni402Official](https://twitter.com) (coming soon)
- **Discord**: [Join our community](https://discord.gg) (coming soon)

## 🙏 Acknowledgments

- [Solana Foundation](https://solana.com/) for blockchain infrastructure
- [Phantom Wallet](https://phantom.app/) for wallet integration
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- All our early testers and contributors

---

**Note**: This is a demonstration version using mock data. Full blockchain integration is required for production use. Always test with small amounts first and ensure you understand blockchain transactions before use.

---
Made with ❤️ for the future of decentralized education
