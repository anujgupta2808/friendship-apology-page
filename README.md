# I'm Really Sorry 💙

An interactive apology webpage with animated elements and a playful "No" button that moves away when hovered.

## Features

- 🎨 Animated gradient background
- 💙 Floating hearts animation
- 🎯 Interactive "No" button that moves horizontally
- 📱 Fully responsive design
- 💬 WhatsApp integration
- ✨ Smooth animations and transitions

## Setup

1. Open `dindexel.html` in your browser
2. Update the WhatsApp number in the script section:
   ```javascript
   window.whatsappUrl = "https://wa.me/YOURNUMBER?text=Hey%20👋%20I%20forgive%20you!%20Let's%20talk%20💙";
   ```
   Replace `YOURNUMBER` with your actual WhatsApp number (country code without +)

## How It Works

- **Yes Button**: Clicking shows a success popup and redirects to WhatsApp
- **No Button**: Moves horizontally when hovered, making it hard to click
- The "No" button text changes after multiple attempts to encourage clicking "Yes"

## Customization

Edit the message in the `.message-card` section to personalize your apology.

## Technologies

- HTML5
- CSS3 (Animations & Gradients)
- Vanilla JavaScript
