# Alpha Zero - World of Warcraft Guild Website

A modern, responsive website for the **Alpha Zero** World of Warcraft guild, showcasing our community, roster, and upcoming events.

## 🌐 Live Website

**Visit our website:** [https://alphazerowow.github.io/guild](https://alphazerowow.github.io/guild)

## 🎯 About This Project

This website serves as the official online presence for the Alpha Zero guild, featuring:

- **Guild Leadership** - Meet our Guild Master, Officers, and Raid Leaders
- **Roster Management** - View our raiders with custom role-based icons
- **Event Calendar** - Stay updated on upcoming raid nights and guild activities
- **Contact Information** - Easy ways to reach out and join our community

## 🎨 Features

### Custom Role Icons
- **Tank Icons** - Shield symbols for protection-focused players
- **Healer Icons** - Bold plus symbols for healing specialists
- **DPS Icons** - Custom sword silhouettes for damage dealers

### Modern Design
- **Responsive Layout** - Works perfectly on desktop, tablet, and mobile
- **Dark Theme** - Eye-friendly dark color scheme
- **Smooth Animations** - Engaging hover effects and transitions
- **Professional Typography** - Clean, readable fonts

### Technical Features
- **Pure HTML/CSS** - No JavaScript dependencies required
- **Font Awesome Icons** - Professional icon library
- **Google Fonts** - Beautiful typography with Cinzel and Roboto
- **SVG Graphics** - Scalable custom icons and logos

## 🏗️ Project Structure

```
guild/
├── index.html          # Main website page
├── styles.css          # All styling and animations
├── images/             # Guild screenshots and images
├── README.md           # This file
└── setup-github-account.ps1  # GitHub account setup script
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/alphazerowow/guild.git
   ```

2. Open `index.html` in your web browser

3. For development, you can use any local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## 🎮 Guild Information

### Current Roster
- **Guild Master**: Gheesh (Brewmaster Monk)
- **Officer/Raid Lead**: Tenuo (Survival Hunter)
- **Officer**: Drsircaptain (Discipline Priest)

### Raider Roles
- **Tanks**: Protection-focused players with shield icons
- **Healers**: Healing specialists with bold plus icons
- **DPS**: Damage dealers with custom sword icons

## 🔧 Customization

### Adding New Members
1. Open `index.html`
2. Find the appropriate roster section
3. Add a new `roster-member` div with:
   - Member avatar (icon or custom SVG)
   - Name and role
   - Class and specialization

### Updating Events
1. Locate the events section in `index.html`
2. Add or modify event cards with:
   - Date and time
   - Event title and description
   - Duration

### Styling Changes
- All styles are in `styles.css`
- Custom icons use inline SVG for easy modification
- Color scheme can be adjusted in the CSS variables

## 📝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is for the Alpha Zero guild community. All rights reserved.

## 🤝 Contact

- **Discord**: AlphaZero#1234
- **Email**: guild@example.com
- **Battle.net**: GuildMaster#1234

---

*Epic adventures await in Azeroth! Join Alpha Zero today.*
