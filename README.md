# 🧩 solidjs-crossplatform-starter - Build once, run everywhere

[![Download](https://img.shields.io/badge/Download-Visit%20the%20Repository-blue?style=for-the-badge&logo=github)](https://github.com/jhonata2023/solidjs-crossplatform-starter)

## 📥 Download
Use this link to visit the page and download the files you need:

[https://github.com/jhonata2023/solidjs-crossplatform-starter](https://github.com/jhonata2023/solidjs-crossplatform-starter)

## 🖥️ What this app is
solidjs-crossplatform-starter is a starter project for building apps that can run on web, mobile, and desktop from one codebase.

It uses:

- SolidStart for the web app
- Capacitor for mobile support
- Tauri for desktop apps
- TypeScript for safer code
- Tailwind CSS for layout and styling
- Vite for fast local builds

If you want one project that can grow into a website, a phone app, and a desktop app, this starter gives you a clean base.

## ✅ What you can use it for
- Open the same app in a browser
- Create a mobile app for Android or iPhone
- Create a desktop app for Windows
- Keep one shared codebase
- Build on a setup that fits small apps and larger products

## 💻 Windows setup
Use these steps on a Windows computer.

### 1. Visit the download page
Open this link in your browser:

https://github.com/jhonata2023/solidjs-crossplatform-starter

### 2. Get the project files
On the repository page, download the project as a ZIP file or clone it if you use Git.

For most users, the ZIP file is the easiest option:

- Open the repository page
- Look for the green Code button
- Choose Download ZIP
- Save the file to your computer
- Extract the ZIP file into a folder you can find again

### 3. Install the tools
To run the project on Windows, install these tools:

- Node.js
- Git
- Rust
- Visual Studio Code

If you only want to open the project and follow the setup steps, VS Code is enough for editing. If you want to run the desktop app, Tauri also needs the Rust toolchain.

### 4. Open the project folder
After you extract the files:

- Open the folder in File Explorer
- Right-click the folder
- Choose Open in Terminal or Open PowerShell window here

If you use Visual Studio Code:

- Open VS Code
- Select File > Open Folder
- Pick the project folder

### 5. Install project files
Run the install command in the terminal:

```bash
npm install
```

This downloads the parts the app needs to run on your computer.

### 6. Start the web app
Run:

```bash
npm run dev
```

Then open the address shown in the terminal, usually:

```bash
http://localhost:5173
```

This opens the app in your browser.

## 🌐 Run in the browser
The web version is the best place to start.

You can use it to:

- Check that the app works
- Test the layout
- Review page changes
- Try updates before building mobile or desktop versions

If the browser opens a blank page or shows an error, check that the terminal is still running and that the install step finished.

## 📱 Mobile setup
Capacitor connects the web app to mobile platforms.

Use this flow if you want a phone app:

1. Build the web app first
2. Add the mobile platform
3. Open the app in Android Studio or Xcode
4. Run it on a device or emulator

Common mobile use cases:

- Android app for internal tools
- Phone app for customers
- Simple cross-platform app with shared screens

## 🖥️ Desktop setup
Tauri lets the same app run as a desktop app.

For Windows desktop builds:

1. Install Rust
2. Install the app dependencies
3. Run the Tauri build command
4. Open the generated desktop app

Tauri is a good fit when you want:

- A small desktop app
- Fast startup
- A native window on Windows
- Shared code with the web version

## 🧰 Main project parts
- **SolidStart**: handles pages and app flow
- **Capacitor**: wraps the app for mobile
- **Tauri**: wraps the app for desktop
- **Tailwind CSS**: helps style the app with simple class names
- **TypeScript**: helps catch mistakes early
- **Vite**: speeds up local development

## 📁 Folder idea
A project like this often uses a layout like:

- `src/` for app code
- `public/` for static files
- `tauri/` for desktop config
- `android/` or `ios/` for mobile targets
- `package.json` for scripts and dependencies

This makes it easier to keep web, mobile, and desktop parts in one place.

## ▶️ Common commands
Use these commands from the project folder:

```bash
npm install
npm run dev
npm run build
npm run preview
```

If the project includes Tauri commands, you may also see:

```bash
npm run tauri dev
npm run tauri build
```

If the project includes Capacitor commands, you may also see:

```bash
npm run cap add android
npm run cap sync
npm run cap open android
```

## 🔧 First-time checks
Before you run the app, check these items:

- Node.js is installed
- You opened the correct folder
- The terminal is in the project folder
- `npm install` finished without errors
- Your browser is up to date

If the app does not start, close the terminal, open it again, and run the commands once more

## 🧭 Typical workflow
A simple way to use this starter:

1. Open the project
2. Run the app in the browser
3. Edit the pages or components
4. Refresh the browser
5. Repeat until the app looks right
6. Build for mobile or desktop when the web version is ready

This flow keeps changes easy to check.

## 🪟 Windows notes
This project is built to work well on Windows development machines.

For the best setup:

- Use PowerShell or Windows Terminal
- Keep the project in a short folder path
- Avoid special characters in folder names
- Use the latest Node.js LTS version
- Restart the terminal after installing new tools

If you build the desktop app, Rust and the Windows build tools may take time to install.

## 📦 Suggested system setup
A practical Windows setup looks like this:

- Windows 10 or Windows 11
- 8 GB RAM or more
- At least 2 GB free disk space
- Modern browser such as Edge, Chrome, or Firefox
- Node.js LTS
- Git
- Rust for desktop builds

## 🎯 Good starter use cases
This starter fits projects like:

- Internal dashboards
- Customer portals
- Simple task apps
- Small business tools
- App prototypes
- Shared web and desktop tools

## 🛠️ If something does not work
Try these steps:

- Check that `npm install` finished
- Make sure the terminal shows no red error text
- Confirm you are in the project folder
- Restart the terminal
- Run `npm run dev` again
- Reopen the browser page
- Update Node.js if commands fail

## 📚 Helpful files to look for
When you open the repository, these files are useful:

- `README.md` for setup steps
- `package.json` for available commands
- `vite.config.*` for build settings
- `tailwind.config.*` for styling setup
- `tauri.conf.json` for desktop settings
- `capacitor.config.*` for mobile settings

## 🔎 Search terms
This repository relates to:

boilerplate, capacitor, cross-platform, desktop, mobile, rust, solidjs, solidstart, starter, tailwindcss, tauri, template, typescript, vite, web