⚡ Rashboard
​A blazing-fast, 100% local Infrastructure & Environment Command Center.
​Rashboard is a Progressive Web App (PWA) designed to solve the chaos of managing multiple developer environments. Instead of digging through endless dashboards to find your .env variables or server statuses, Rashboard lets you upload your .env files and instantly visualizes your entire stack in a sleek, native-feeling interface.
​✨ Key Features
​🔒 100% Local & Secure: No backend required. Your sensitive API keys and database URIs never leave your device. Everything is encrypted and stored locally in your browser.
​📂 Smart .env Parsing: Drag and drop your .env files. Rashboard automatically strips comments, categorizes variables (Database, Auth, Frontend, etc.), and builds your dashboard.
​🌐 Intelligent Service Detection: Rashboard scans your variables and automatically generates deep-links to your provider consoles (Supabase, Vercel, Render, Clerk, Stripe, Neon, etc.).
​🐙 GitHub & Pages Integration: Enter your repository name, and Rashboard automatically generates quick links to your source code and deployed GitHub Pages.
​📡 Live Health Pinging: Real-time server status indicators. Rashboard periodically pings your live URLs to let you know if your instances are ONLINE, STANDBY, or WAKING UP.
​📱 Native PWA Experience: Installable on Android, iOS, and Desktop. Features a custom splash screen, adaptive Bottom Dock navigation, and flawless mobile scaling.
​🌗 Adaptive OLED UI: A Vercel-inspired glassmorphism interface that perfectly synchronizes with your device's system-level Light or Dark mode.
​💾 Vault Backup System: Export your entire dashboard configuration as a secure JSON payload and restore it on any device.
​🛠️ Installation & Setup
​Rashboard requires zero build steps or package managers. It runs purely on standard web technologies.
​Prerequisites
​Make sure you have these files in the same directory:
​index.html (The main application)
​manifest.json (PWA configuration)
​sw.js (Service Worker for offline caching)
​1000121828.png (Your custom App Logo)
​Running Locally (Desktop)
​You can run this using any basic local server.
If you have Python installed, open your terminal in the project folder and run:
