# 🚀 RATANAK TOOLS / Khmer SMM

> Modern Web Tools Platform - Next.js 15 + React 19 + TypeScript

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15.3.3-black?logo=next.js">
  <img src="https://img.shields.io/badge/React-19.1.0-blue?logo=react">
  <img src="https://img.shields.io/badge/TypeScript-5.8.3-blue?logo=typescript">
  <img src="https://img.shields.io/badge/Tailwind-4.1.7-cyan?logo=tailwindcss">
  <img src="https://img.shields.io/badge/Node.js-20.x-green?logo=node.js">
  <img src="https://img.shields.io/badge/License-MIT-red">
</p>

---

# 🌐 Live Demo

* 🌍 **Website:** https://ratanak-tools.vercel.app (deploy your own)
* 📢 **Telegram:** https://t.me/nhnak
* 👨‍💻 **Developer:** NH-NAK

---

# ✨ Features

* ⚡ **Next.js 15** - Latest App Router with Server Components
* 🎨 **Tailwind CSS 4** - Modern styling with animations
* 🔐 **2FA Generator** - OTP code generator from secret key
* � **QR Code Generator** - Create QR codes for text, URL, WiFi, Phone
* � **TikTok Downloader** - Download TikTok videos (API powered)
* 🌍 **IP Checker** - Check your IP address and location
* 📦 **Software Download** - Download popular development tools
* � **Rate Limiting** - API protection system
* � **Admin Panel** - Dashboard for management

---

# 📸 Screenshots

<p align="center">
  <img src="preview-home.png" width="800">
</p>
<p align="center">
  <img src="preview-software.png" width="800">
</p>

---

# 🎯 Available Tools

| Tool | Description | Status |
|------|-------------|--------|
| 🔐 2FA Generator | Generate OTP codes | ✅ Active |
| 📱 QR Code | Create various QR codes | ✅ Active |
| 🎬 TikTok Downloader | Download TikTok videos | ✅ Active |
| 🌍 IP Checker | Check IP & location | ✅ Active |
| 📦 Software Center | Download dev tools | ✅ Active |
| 👤 Rate Limit Test | API testing | ✅ Active |
| 🔒 Fake Data | Generate test data | 🚧 Coming Soon |

---

# 📂 Project Structure

```bash
khmer-smm/
│
├── src/
│   ├── app/              # Next.js App Router
│   │   ├── 2fa/          # 2FA Generator tool
│   │   ├── qr-code/      # QR Code generator
│   │   ├── tiktok/       # TikTok downloader
│   │   ├── check-ip/     # IP checker
│   │   ├── software/     # Software download
│   │   ├── rate-limit/   # Rate limit test
│   │   ├── fake-data/    # Fake data generator
│   │   ├── admin/        # Admin panel
│   │   └── api/          # API routes
│   ├── components/       # React components
│   └── lib/              # Utilities & helpers
│
├── api/                  # Python Flask API
│   ├── app.py           # Main API (TikTok/YouTube)
│   ├── deploy.py        # Deploy version
│   └── requirements.txt  # Python deps
│
├── public/              # Static assets
├── render.yaml          # Render deployment config
├── netlify.toml         # Netlify config
└── package.json         # Node.js dependencies
```

---

# ⚡ Quick Start

```bash
# Clone repository
git clone https://github.com/USERNAME/khmer-smm.git

# Navigate to project
cd khmer-smm

# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

# 🛠️ Installation

## Prerequisites

- Node.js 20.x or higher
- npm or yarn

## Step 1: Clone & Install

```bash
git clone https://github.com/USERNAME/khmer-smm.git
cd khmer-smm
npm install
```

## Step 2: Environment Variables (Optional)

Create `.env.local` file:

```env
# Optional: Database connection
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

## Step 3: Run Project

```bash
# Development
npm run dev

# Production build
npm run build
npm start
```

---

# 🔧 API Configuration

The project includes a Python Flask API for video downloading:

## Deploy API to Render

1. Push code to GitHub
2. Connect repository to [Render](https://render.com)
3. Use `render.yaml` blueprint
4. API will be available at `https://your-api.onrender.com`

## API Endpoints

```
GET /          - Health check
GET /info?url= - Get video info
GET /download?url= - Download video
GET /captions?url= - Download captions
```

---

# 🧠 Technologies Used

### Frontend
- **Next.js 15.3.3** - React Framework
- **React 19.1.0** - UI Library
- **TypeScript 5.8.3** - Type safety
- **Tailwind CSS 4.1.7** - Styling
- **Lucide React** - Icons
- **Zod** - Schema validation

### Backend
- **Next.js API Routes** - Serverless functions
- **Python Flask** - Video download API
- **yt-dlp** - Video extraction
- **MongoDB + Mongoose** - Database (optional)

### Tools
- **QRCode** - QR code generation
- **BcryptJS** - Password hashing
- **JWT** - Authentication tokens

---

# 📦 Build & Deploy

## Build for Production

```bash
npm run build
```

## Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## Deploy to Netlify

```bash
# Install Netlify CLI
npm i -g netlify-cli

# Deploy
netlify deploy --prod
```

---

# 📊 Project Status

| Feature | Status |
|---------|--------|
| Homepage | ✅ Complete |
| 2FA Tool | ✅ Complete |
| QR Code | ✅ Complete |
| TikTok Downloader | ✅ Working |
| IP Checker | ✅ Complete |
| Software Center | ✅ Complete |
| Admin Panel | ✅ Basic |
| Rate Limiting | ✅ Complete |
| Fake Data | 🚧 Coming Soon |

---

# 🛡️ Security Features

* 🔐 JWT Authentication
* 🛡️ Rate Limiting (API protection)
* � IP-based restrictions
* 📊 Request monitoring
* 🚫 Anti-spam protection

---

# 📈 Roadmap

* [ ] YouTube Downloader (Full HD)
* [ ] Facebook Video Downloader
* [ ] Instagram Downloader
* [ ] Password Generator
* [ ] URL Shortener
* [ ] File Converter
* [ ] AI Chat Integration
* [ ] User Accounts System
* [ ] Cloud Storage
* [ ] Mobile App (React Native)

---

# 🌐 Community

<p align="center">
  <a href="https://t.me/nhnak">
    <img src="https://img.shields.io/badge/Join-Telegram-229ED9?style=for-the-badge&logo=telegram">
  </a>
</p>

---

# 💻 Developer

## 👨‍💻 NH-NAK (RATANAK)

Full Stack Developer | Next.js & React Specialist | API Developer

---

# ⭐ Support Project

If you like this project:

* ⭐ Star this repository
* 🔁 Share with friends
* 📢 Join Telegram community
* 🐛 Report issues

---

# 📜 License

MIT License © 2024 NH-NAK / RATANAK

---

<p align="center">
  Made with ❤️ by NH-NAK | Powered by Next.js & React
</p>
