# High Lands - Cannabis Farming Simulation Game

![High Lands](assets/gg.png)

The ultimate cannabis farming simulation game built on Solana blockchain. Grow, harvest, and earn rewards in this innovative Web3 gaming experience.

## 🚀 Features

- **Real-time farming simulation** - Plant, grow, and harvest cannabis
- **NFT integration** - Collect unique seeds and farming equipment
- **Solana blockchain** - Fast, secure transactions
- **Multiplayer gameplay** - Compete with other farmers
- **Token rewards** - Earn $HIGH tokens for your efforts

## 🛠️ Tech Stack

- **Backend**: PHP 7.4+ (opcional)
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Blockchain**: Solana
- **Styling**: Custom CSS with responsive design
- **APIs**: CoinGecko for real-time SOL price

## 🔧 Requirements

- **PHP 7.4+** (optional - site works as static HTML)
- **Web Server** (Apache, Nginx, or Vercel/Netlify)

## 📦 Deployment

### Vercel (Recommended)

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect the `vercel.json` configuration
3. Deploy with security headers and optimizations enabled

### Netlify

1. Connect your repository to Netlify
2. Netlify will use the `_headers` file for security headers
3. Deploy with automatic optimizations

### Manual Deployment

#### Option 1: PHP Server
```bash
php -S localhost:8000
```

#### Option 2: Apache/Nginx
1. Upload all files to your web server
2. Ensure HTTPS is enabled
3. Configure your server to use the provided `.htaccess` file (Apache)

#### Option 3: Static HTML
- Use `index.html` for static hosting (included in repository)
- Or rename `index.php` to `index.html` for static hosting
- All functionality remains the same

## 🔒 Security Features

- Content Security Policy (CSP)
- XSS Protection
- Frame Options (DENY)
- Strict Transport Security (HSTS)
- Referrer Policy
- Permissions Policy

## 📱 Responsive Design

Fully responsive across all devices:
- Desktop (1200px+)
- Tablets (900px - 1199px)
- Mobile (600px - 899px)
- Small mobile (400px - 599px)

## 🚀 Getting Started

### Local Development

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/highlands-game.git
cd highlands-game

# Install dependencies (if any)
npm install

# Start development server
npm run dev
```

### Uploading to GitHub

1. **Create a new repository on GitHub:**
   - Go to [github.com](https://github.com) and sign in
   - Click the "+" icon → "New repository"
   - Name it `highlands-game` or your preferred name
   - Don't initialize with README (we already have one)
   - Click "Create repository"

2. **Connect your local repository:**
   ```bash
   # Add the remote origin (replace YOUR_USERNAME with your GitHub username)
   git remote add origin https://github.com/YOUR_USERNAME/highlands-game.git

   # Push to GitHub
   git push -u origin main
   ```

3. **Deploy with Vercel (Recommended):**
   - Go to [vercel.com](https://vercel.com)
   - Connect your GitHub account
   - Import the repository
   - Deploy automatically

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

© High Lands. All rights reserved by UNICORN LABS 2025.

## 📞 Contact

- Website: [playhighlands.net](https://playhighlands.net)
- Documentation: [docs.playhighlands.net](https://docs.playhighlands.net)
- Twitter: [@highlands.fun](https://x.com/highlands.fun)

---

Built with ❤️ by UNICORN LABS
