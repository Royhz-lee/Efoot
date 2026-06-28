# 🎮 Munene Esports Arena

> **Africa's Premier eFootball Tournament Platform**

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Platform](https://img.shields.io/badge/Platform-Responsive-orange.svg)]()

---

## 📋 Project Overview

Munene Esports Arena is a modern, professional eFootball tournament platform where players can register, deposit funds, join leagues and tournaments, compete for real prize money, and withdraw winnings. The platform is built with a dark esports theme featuring blue and gold accents, creating an immersive competitive gaming experience.

**[Live Demo](#)** | **[Documentation](#documentation)** | **[Issues](#reporting-bugs)** | **[Contributing](#contributing)**

---

## ✨ Key Features

### 🏆 Tournament Management
- **Dynamic Tournament System**: Browse and register for multiple tournaments
- **Tournament Stages**: Registration → Group Stage → Knockout Rounds → Finals
- **Real-time Prizes**: Live prize pool tracking and participant count
- **Tournament Categories**: Elite, Rookie, Weekend Warriors, and more
- **Countdown Timers**: Integration-ready for live tournament countdowns

### 💰 Wallet & Payments
- **Multi-Payment Support**:
  - M-Pesa (Paybill: 247247, Account: 0708636339)
  - Pesapal
  - IntaSend
- **Instant Deposits**: Real-time fund addition to player wallets
- **Secure Withdrawals**: Multiple withdrawal options with verification
- **Transaction History**: Complete audit trail of all financial activities
- **Balance Management**: Real-time wallet balance updates

### 🏅 League System
- **5-Tier League Structure**:
  - Bronze League (Entry: 500 KES)
  - Silver League (Entry: 2,000 KES)
  - Gold League (Entry: 5,000 KES)
  - Platinum League (Entry: 10,000 KES)
  - Champions League (Entry: 20,000 KES)
- **Monthly Competitions**: Rank-based prize distribution
- **Dynamic Rankings**: Real-time player positioning

### 👥 Player Profiles & KYC
- **KYC Verification System**:
  - National ID/Passport upload
  - Selfie verification
  - Phone verification
  - Email confirmation
- **Player Dashboards**: Personalized gaming space with:
  - Wallet management
  - Match history
  - League standings
  - Performance analytics
  - Upcoming matches

### 🏆 Leaderboard & Rankings
- **Global Leaderboard**: Top 10 players showcase
- **Dynamic Rankings**: Real-time point calculations
- **League-based Filtering**: View rankings by tier
- **Achievement Tracking**: Win counts and points accumulation

### 📊 Admin Dashboard (Ready for Backend Integration)
- **User Management**: View and manage player accounts
- **Financial Dashboard**: Track deposits, withdrawals, revenues
- **Tournament Administration**: Create, edit, and monitor tournaments
- **KYC Verification Queue**: Approve/reject player verifications
- **Analytics & Reports**: Revenue tracking and player statistics

### 🎯 Responsive Design
- **Mobile-First Approach**: Fully responsive from 320px to 4K
- **Touch-Optimized**: Perfect for mobile and tablet users
- **Dark Theme**: Easy on the eyes with high contrast ratios
- **Fast Loading**: Optimized for performance

---

## 🛠 Technical Stack

### Frontend
- **HTML5**: Semantic markup with proper structure
- **CSS3**: Modern styling with:
  - CSS Variables for theming
  - Flexbox & Grid layouts
  - Smooth animations & transitions
  - Media queries for responsiveness
  - Backdrop filters & gradients
- **JavaScript (Vanilla)**: 
  - No dependencies required
  - SPA (Single Page Application) navigation
  - Local storage for user sessions
  - Event handling & DOM manipulation
  - Sample data management

### Design & Icons
- **Font Awesome 6.4**: 1800+ icons for rich UI
- **Custom Color Palette**:
  - Primary Dark: `#0a0e27`
  - Card Dark: `#1a1f3a`
  - Gold Accent: `#ffd700`
  - Electric Blue: `#00d4ff`
  - Modern gradients and shadow effects

### Compatibility
- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

---

## 🚀 Quick Start

### Installation

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/munene-esports-arena.git
cd munene-esports-arena
```

2. **Open in Browser**
```bash
# Method 1: Direct file open
open index.html

# Method 2: Using Python's built-in server
python -m http.server 8000

# Method 3: Using Node.js http-server
npm install -g http-server
http-server

# Method 4: Using Live Server (VSCode Extension)
# Install 'Live Server' extension and click 'Open with Live Server'
```

3. **Access the Platform**
```
http://localhost:8000
```

### No Setup Required!
- ✅ Single HTML file - just open in any browser
- ✅ No build process needed
- ✅ No npm packages required (frontend only)
- ✅ No server dependencies
- ✅ Works offline (with sample data)

---

## 📖 Usage Guide

### For Players

#### 1. **Register Account**
- Click "Register" button
- Fill in profile information
- Create secure password
- Verify email address

#### 2. **Complete KYC**
- Upload National ID or Passport
- Submit selfie photo
- Verify phone number
- Await approval (instant for demo)

#### 3. **Deposit Funds**
- Go to Wallet → Deposit Funds
- Select amount and payment method
- M-Pesa: Use Paybill 247247, Account 0708636339
- Complete payment
- Funds appear instantly

#### 4. **Join Tournaments**
- Browse available tournaments
- Review entry fee and prize pool
- Click "Register Now"
- Match will appear in Dashboard

#### 5. **Track Performance**
- View Dashboard for stats
- Check Leaderboard rankings
- Monitor wallet balance
- View match history

#### 6. **Withdraw Winnings**
- Go to Wallet → Withdraw Funds
- Enter amount and method
- Confirm withdrawal
- Receive within 1-3 business days

### For Administrators

#### Access Admin Dashboard (Demo)
- Navigate to `/admin` section
- View user management
- Monitor financial activities
- Approve KYC verifications
- Generate reports

---

## 📁 Project Structure

```
munene-esports-arena/
├── index.html                 # Main application file (single-page)
├── README.md                  # This file
├── LICENSE                    # MIT License
├── .gitignore                # Git ignore rules
├
├── docs/                      # Documentation (optional)
│   ├── CONTRIBUTING.md
│   ├── DEPLOYMENT.md
│   └── API.md                 # For backend integration
│
└── assets/                    # Static files (optional)
    ├── images/
    ├── fonts/
    └── logos/
```

---

## 🎨 Customization Guide

### Theme Colors
Edit the CSS variables in the `<style>` section:

```css
:root {
    --primary-dark: #0a0e27;      /* Main background */
    --secondary-dark: #0f1419;    /* Secondary background */
    --card-dark: #1a1f3a;         /* Card backgrounds */
    --accent-gold: #ffd700;       /* Primary accent */
    --accent-blue: #00d4ff;       /* Secondary accent */
    --accent-electric: #0099ff;   /* Highlight accent */
    --text-primary: #ffffff;      /* Main text */
    --text-secondary: #a0a0a0;    /* Secondary text */
    --success: #00ff88;           /* Success state */
    --danger: #ff4444;            /* Error state */
    --warning: #ffaa00;           /* Warning state */
}
```

### Logo & Branding
Update in the header section:
```html
<div class="logo">
    <i class="fas fa-gamepad"></i>
    Munene Arena  <!-- Change text here -->
</div>
```

### Payment Information
Update M-Pesa details in the wallet section:
```javascript
const methods = {
    'M-Pesa': '<strong>M-Pesa Details:</strong><br>Business Name: Your Name<br>Paybill: 247247<br>Account Number: YOUR_ACCOUNT'
}
```

### Tournament Data
Modify the tournaments array in the JavaScript:
```javascript
app.tournaments = [
    {
        id: 1,
        name: 'Your Tournament',
        entry: 5000,
        prize: 500000,
        participants: 128,
        slots: 12,
        stage: 'Registration',
        startDate: 'July 15, 2024'
    }
]
```

### Company Information
Update footer details:
```javascript
// In footer section
<li><a href="mailto:YOUR_EMAIL">YOUR_EMAIL</a></li>
<li><a href="tel:YOUR_PHONE">YOUR_PHONE</a></li>
```

---

## 🔧 Backend Integration (Next Steps)

This is a frontend-only application. To make it fully functional, you'll need to integrate with a backend server. Here's the recommended setup:

### Recommended Backend Stack

#### **Option 1: Python + Flask/FastAPI**
```bash
pip install flask flask-cors python-dotenv
pip install psycopg2 sqlalchemy
```

**Basic structure:**
```python
from flask import Flask, request, jsonify
from flask_cors import CORS

app = Flask(__name__)
CORS(app)

@app.route('/api/auth/register', methods=['POST'])
def register():
    data = request.json
    # Validate and store user
    return jsonify({'success': True})

@app.route('/api/wallet/deposit', methods=['POST'])
def deposit():
    # Handle payment integration
    return jsonify({'transaction_id': 'TXN123'})
```

#### **Option 2: Node.js + Express**
```bash
npm install express cors dotenv
npm install pg knex  # For database
npm install stripe # For payments
```

#### **Option 3: Python + Django**
```bash
pip install django djangorestframework django-cors-headers
```

### Database Schema (Example)
```sql
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    username VARCHAR(255) UNIQUE,
    email VARCHAR(255) UNIQUE,
    phone VARCHAR(20),
    password_hash VARCHAR(255),
    kyc_status VARCHAR(50),
    created_at TIMESTAMP,
    updated_at TIMESTAMP
);

CREATE TABLE wallets (
    id SERIAL PRIMARY KEY,
    user_id INT REFERENCES users(id),
    balance DECIMAL(10, 2),
    currency VARCHAR(3)
);

CREATE TABLE transactions (
    id SERIAL PRIMARY KEY,
    user_id INT REFERENCES users(id),
    type VARCHAR(50),
    amount DECIMAL(10, 2),
    status VARCHAR(50),
    created_at TIMESTAMP
);

CREATE TABLE tournaments (
    id SERIAL PRIMARY KEY,
    name VARCHAR(255),
    entry_fee DECIMAL(10, 2),
    prize_pool DECIMAL(10, 2),
    stage VARCHAR(50),
    start_date TIMESTAMP
);
```

### API Endpoints (To Implement)

```
Authentication:
POST   /api/auth/register        - User registration
POST   /api/auth/login           - User login
POST   /api/auth/logout          - User logout
GET    /api/auth/verify          - Verify token

Users:
GET    /api/users/{id}           - Get user profile
PUT    /api/users/{id}           - Update profile
POST   /api/users/{id}/kyc       - Submit KYC documents

Wallets:
GET    /api/wallet/balance       - Get wallet balance
POST   /api/wallet/deposit       - Initiate deposit
POST   /api/wallet/withdraw      - Initiate withdrawal
GET    /api/wallet/transactions  - Get transaction history

Tournaments:
GET    /api/tournaments          - List all tournaments
GET    /api/tournaments/{id}     - Get tournament details
POST   /api/tournaments/{id}/register - Register for tournament

Leagues:
GET    /api/leagues              - List all leagues
GET    /api/leagues/{id}         - Get league details
GET    /api/leaderboard          - Get global leaderboard

Payments:
POST   /api/payments/mpesa       - M-Pesa payment
POST   /api/payments/pesapal     - Pesapal payment
POST   /api/payments/callback    - Payment callback
```

### Payment Gateway Integration

#### **M-Pesa Integration (Daraja API)**
```python
import requests

def initiate_mpesa_payment(amount, phone, account_ref):
    api_url = "https://sandbox.safaricom.co.ke/mpesa/stkpush/v1/processrequest"
    
    payload = {
        "BusinessShortCode": 247247,
        "Password": generate_password(),
        "Timestamp": get_timestamp(),
        "TransactionType": "CustomerPayBillOnline",
        "Amount": amount,
        "PartyA": phone,
        "PartyB": 247247,
        "PhoneNumber": phone,
        "CallBackURL": "https://yourdomain.com/api/payments/mpesa/callback",
        "AccountReference": account_ref,
        "TransactionDesc": "Tournament Entry"
    }
    
    response = requests.post(api_url, json=payload)
    return response.json()
```

#### **Pesapal Integration**
```python
def initiate_pesapal_payment(amount, email, order_id):
    api_url = "https://api.pesapal.com/api/urlbuilder"
    
    payload = {
        "pesapal_request_ip": get_client_ip(),
        "pesapal_merchant_reference": order_id,
        "pesapal_transaction_type": "PAYMENT",
        "pesapal_amount": amount,
        "pesapal_description": "Munene Tournament Entry",
        "pesapal_type": 'MERCHANT',
        "pesapal_currency": 'KES',
        "pesapal_callback_url": "https://yourdomain.com/api/payments/pesapal/callback"
    }
    
    # Sign request and call API
    return call_pesapal_api(payload)
```

---

## 🔐 Security Considerations

### Frontend Security
- ✅ Input validation on all forms
- ✅ HTTPS enforcement (required in production)
- ✅ XSS prevention via proper escaping
- ✅ CSRF tokens (implement with backend)
- ✅ Rate limiting (implement with backend)

### Backend Security (When Implementing)
- ✅ Never store sensitive data in localStorage
- ✅ Use secure session management
- ✅ Implement JWT or session tokens
- ✅ Encrypt sensitive data
- ✅ Use HTTPS only
- ✅ Implement CORS properly
- ✅ Validate all inputs server-side
- ✅ Use parameterized queries to prevent SQL injection
- ✅ Implement rate limiting

### KYC & Compliance
- ✅ Age verification (18+ requirement)
- ✅ Document verification
- ✅ Phone and email verification
- ✅ Compliance with local regulations

---

## 📱 Browser Support

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome  | ✅ Full | Latest 2 versions |
| Firefox | ✅ Full | Latest 2 versions |
| Safari  | ✅ Full | iOS 12+ |
| Edge    | ✅ Full | Latest 2 versions |
| IE 11   | ❌ No  | Not supported |

---

## ⚡ Performance Optimization

### Current Optimizations
- ✅ Single HTML file (no multiple requests)
- ✅ Inline CSS & JavaScript (no external file requests)
- ✅ Minimal Font Awesome usage (CDN)
- ✅ CSS Variables for easy theming
- ✅ Optimized animations (GPU accelerated)
- ✅ Efficient JavaScript (no framework overhead)

### Further Optimization (Production)
- Split CSS & JS into separate files
- Minify and gzip compression
- Implement service workers for offline support
- Use WebP images with JPEG fallback
- Implement lazy loading for images
- Cache static assets
- Use CDN for Font Awesome

---

## 🐛 Reporting Bugs

Found a bug? Please report it by:

1. **Check existing issues** - Avoid duplicates
2. **Create a new issue** with:
   - Clear title
   - Detailed description
   - Steps to reproduce
   - Expected vs actual behavior
   - Browser/OS information
   - Screenshots (if applicable)

**Issue Template:**
```markdown
## Bug Report

### Description
[Clear description of the bug]

### Steps to Reproduce
1. [Step 1]
2. [Step 2]
3. [Step 3]

### Expected Behavior
[What should happen]

### Actual Behavior
[What actually happens]

### Environment
- Browser: [Chrome/Firefox/Safari]
- OS: [Windows/Mac/Linux]
- Version: [Version number]
```

---

## 💡 Feature Requests

Have a great idea? Submit a feature request:

1. Check if feature already exists
2. Create an issue with label `enhancement`
3. Describe the feature clearly
4. Explain the use case and benefits

---

## 🤝 Contributing

Contributions are welcome! Here's how to contribute:

### 1. Fork the Repository
```bash
# Click the "Fork" button on GitHub
```

### 2. Clone Your Fork
```bash
git clone https://github.com/yourusername/munene-esports-arena.git
cd munene-esports-arena
```

### 3. Create a Feature Branch
```bash
git checkout -b feature/amazing-feature
```

### 4. Make Your Changes
- Follow the existing code style
- Keep changes focused and atomic
- Add comments for complex logic

### 5. Commit Your Changes
```bash
git commit -m "Add amazing feature: description"
```

### 6. Push to Your Fork
```bash
git push origin feature/amazing-feature
```

### 7. Open a Pull Request
- Provide clear title and description
- Reference any related issues
- Include screenshots for UI changes

### Code Style Guidelines

#### HTML
- Use semantic HTML5 elements
- Proper indentation (2 spaces)
- Clear class naming (BEM optional but recommended)

#### CSS
- Use CSS Variables
- Follow the existing color scheme
- Keep selectors simple and efficient
- Comment complex styles

#### JavaScript
- Use const/let (avoid var)
- Write descriptive function names
- Add comments for complex logic
- Follow the existing naming conventions

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

---

## 👥 Authors & Contributors

### Original Creator
- **Your Name** - [GitHub](https://github.com/yourusername)

### Contributors
- [View contributors on GitHub](https://github.com/yourusername/munene-esports-arena/graphs/contributors)

---

## 📞 Contact & Support

- **Email**: support@munenearena.com
- **Phone**: +254 708 636 339
- **Website**: [www.munenearena.com](#)
- **Twitter**: [@munenearena](#)
- **Instagram**: [@munenearena](#)

### Support Channels
- 📧 Email Support: 24/7
- 💬 Live Chat: In-app (when backend is integrated)
- 🎮 Discord Community: [Join our server](#)

---

## 🎯 Roadmap

### Phase 1: MVP (Current)
- ✅ User registration & login
- ✅ Tournament browsing
- ✅ League system
- ✅ Leaderboard
- ✅ Wallet UI
- ✅ KYC verification flow
- ✅ Responsive design

### Phase 2: Backend Integration (Upcoming)
- 🔄 Payment gateway integration
- 🔄 Real database implementation
- 🔄 Admin dashboard functionality
- 🔄 Email notifications
- 🔄 SMS verification

### Phase 3: Advanced Features (Future)
- 📋 Live match streaming
- 📋 In-game chat
- 📋 Teams & partnerships
- 📋 Sponsorship dashboard
- 📋 Mobile app (React Native)
- 📋 API for third-party integration

### Phase 4: Expansion (Long-term)
- 📋 Multiple games support
- 📋 Regional tournaments
- 📋 International tournaments
- 📋 Franchise system
- 📋 Content creator tools

---

## 📚 Additional Resources

- [HTML5 Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3 Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [Font Awesome Icons](https://fontawesome.com)
- [M-Pesa Daraja API](https://developer.safaricom.co.ke)
- [Pesapal Documentation](https://pesapal.com)

---

## ❓ FAQ

**Q: Can I use this for production?**
A: The frontend is production-ready. You'll need to implement a backend for full functionality.

**Q: Is this fully functional?**
A: The frontend is fully functional. Backend integration is required for real payments and data persistence.

**Q: Can I customize the colors?**
A: Yes! All colors are in CSS variables. Easy to change.

**Q: How many users can it handle?**
A: Frontend only - depends on your backend implementation.

**Q: Is there a mobile app?**
A: Not yet, but planned for Phase 3.

**Q: How do I add more tournaments?**
A: Edit the `app.tournaments` array in JavaScript.

**Q: Can I integrate my own payment gateway?**
A: Yes! Implement the payment integration in your backend.

---

## 🎓 Learning Resources

### Getting Started with Web Development
1. [MDN Web Docs](https://developer.mozilla.org)
2. [FreeCodeCamp](https://freecodecamp.org)
3. [CSS Tricks](https://css-tricks.com)

### Backend Development (Choose One)
- **Python**: [Django](https://www.djangoproject.com/) or [Flask](https://flask.palletsprojects.com/)
- **Node.js**: [Express](https://expressjs.com/)
- **PHP**: [Laravel](https://laravel.com/)
- **Java**: [Spring Boot](https://spring.io/projects/spring-boot)

### Database
- [PostgreSQL](https://www.postgresql.org/) - Recommended
- [MySQL](https://www.mysql.com/)
- [MongoDB](https://www.mongodb.com/)

---

## 🏆 Project Stats

- **Lines of Code**: ~3,500+
- **CSS Classes**: 150+
- **JavaScript Functions**: 30+
- **Pages/Sections**: 15+
- **Responsive Breakpoints**: 5
- **Icon Count**: 100+

---

## 📝 Changelog

### Version 1.0 (Current)
- ✨ Initial release
- ✨ Complete frontend implementation
- ✨ Responsive design
- ✨ All core features
- ✨ Documentation

---

## ⭐ Show Your Support

If you find this project helpful, please:
- ⭐ Star the repository
- 🔀 Fork for your own use
- 📢 Share with others
- 💬 Provide feedback

---

## 🙏 Acknowledgments

- **Font Awesome** - Beautiful icon library
- **The Open Source Community** - Inspiration and tools
- **African Gaming Community** - Target audience and inspiration

---

## 📜 Legal

- [Terms of Service](docs/TERMS.md)
- [Privacy Policy](docs/PRIVACY.md)
- [Responsible Gaming Policy](docs/RESPONSIBLE.md)

---

**Made with ❤️ for African Gamers**

Last Updated: January 2024 | Version: 1.0.0

---

*For questions or support, please open an issue on GitHub or contact support@munenearena.com*
