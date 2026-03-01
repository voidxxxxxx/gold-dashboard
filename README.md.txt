# 🏆 Live Gold Price Dashboard

A beautiful, real-time precious metals tracking dashboard for Qatar (QAR) and Nepal (NPR) markets.

![Dashboard Preview](https://your-screenshot-url.png)

## ✨ Features

- **Real-time Updates**: Auto-refreshes every 60 seconds
- **Dual Currency**: Toggle between Qatari Riyal (QR) and Nepali Rupee (रू)
- **4 Metals**: Gold, Silver, Platinum, Palladium
- **Price Conversions**: Ounce, Gram, and Kilogram
- **Live Charts**: 24-hour trend and comparison visualizations
- **Mobile Responsive**: Works perfectly on all devices
- **Free API Integration**: Supports GoldAPI.io and FreeGoldPrice.org

## 🚀 Quick Start

### Option 1: Use Simulated Data (Immediate)
1. Fork this repository
2. Go to Settings → Pages → Select "Main" branch
3. Your site will be live at `https://yourusername.github.io/repo-name`
4. Dashboard works immediately with realistic simulated prices

### Option 2: Real-Time Data (Recommended)
1. Get a free API key from [GoldAPI.io](https://www.goldapi.io/) (100 requests/month)
2. Open your live site
3. Click "Add free API key" in the yellow banner
4. Paste your key and click Save
5. Enjoy real-time price updates!

## 🔧 API Setup Details

### GoldAPI.io (Easiest)
- **Free Tier**: 100 requests/month
- **Sign up**: https://www.goldapi.io/
- **Pros**: Reliable, fast, no credit card required

### FreeGoldPrice.org
- **Free Tier**: Available with registration
- **Sign up**: https://freegoldprice.org/
- **Pros**: Supports multiple metals in one call

## 📊 Exchange Rates

Current fixed rates (update in `js/dashboard.js` if needed):
- 1 USD = 3.64 QAR
- 1 USD = 134.50 NPR
- 1 QAR = 36.95 NPR

## 🛠️ Customization

### Change Update Frequency
Edit in `js/dashboard.js`:
```javascript
const CONFIG = {
    updateInterval: 60000, // Change this (milliseconds)
    // ...
};