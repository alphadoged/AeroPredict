# AeroPredict - Weather & AI Companion Dashboard

A premium, SaaS-grade Weather & AI Companion Dashboard built with **React**, **Vite**, and **Chart.js**. It features instant city/country search, live browser GPS geolocation, custom humanized weather indices (temperature trends, storm warnings, and outdoor activity scores), dynamic charts, and an interactive dark/light Zinc design.

---

## Key Features

1. **City & Country Autocomplete Search**: Instantly query and autocomplete locations worldwide using the free, keyless **Open-Meteo Geocoding API**.
2. **Live GPS Geolocation**: Fetch real-time weather metrics matching your browser's physical coordinates instantly.
3. **AI Companion & Prediction Engine**:
   - **Temperature Trends**: Projects temperature shifts over the 7-day forecast to show warming/cooling rates in friendly terms (e.g., dress lighter vs. grab a jacket).
   - **Storm Warnings & Probability**: Evaluates upcoming barometric pressure drop velocities and humidity bounds to alert you to storm fronts in plain language.
   - **Outdoor Activity Comfort**: Computes daily activity ratings (0-100%) and generates custom recommendations (e.g., "Perfect day for outdoors!").
   - **Travel & Transit Advisories**: Warns you if high winds, heavy rain, or storms are likely to cause flight or road delays.
   - **Home Energy Demand**: Projects how hard your heating or cooling system will need to work based on comfort deviation levels.
4. **Interactive Data Charts**: Dynamic multi-axis charts visualizing 7-day temperature spreads, hourly rain probability, and activity curves.
5. **Aesthetic Transitions & Dark Mode**: Smooth "UI redirection" transitions with a full dark/light glassmorphic Zinc system.
6. **Automatic API Sandbox Fallback**: Detects internet dropouts or API blocks and automatically offers a mock data simulator so you can explore the dashboard features even when offline.

---

## Getting Ready to Push to GitHub

Since Git may not be added to your current shell PATH inside the editor, you should run the following commands in your **local system terminal (PowerShell, Command Prompt, or Git Bash)** or use **VS Code's Source Control panel** to push this project.

### Step 1: Initialize Git & Stage Files
Navigate to the project directory in your terminal and run:
```bash
# Initialize a local Git repository
git init

# Stage all files (this uses the configured .gitignore to skip node_modules/logs)
git add .

# Create the initial commit
git commit -m "feat: humanize weather metrics & prepare repo for GitHub"
```

### Step 2: Create a GitHub Repository
1. Go to your GitHub account and click **New Repository**.
2. Name it (e.g., `weather-predictive-dashboard`).
3. Leave it **Public** or **Private**, and **DO NOT** check any checkboxes for adding a README, .gitignore, or license (since we already have them).
4. Click **Create repository**.

### Step 3: Link & Push to GitHub
Copy the commands displayed on GitHub under "or push an existing repository from the command line" and run them in your local terminal:
```bash
# Rename the default branch to main
git branch -M main

# Link your local repository to GitHub (replace with your actual URL)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push your code to GitHub
git push -u origin main
```

---

## Installation & Local Development Setup

If you want to run the project locally on another machine:

### Step 1: Install Node.js & npm
1. Download the official **Node.js LTS Installer**:
   - Visit: [https://nodejs.org/](https://nodejs.org/)
2. Run the installer and follow the standard installation wizard (make sure Node is added to your PATH).
3. Verify the installation is correct:
   ```bash
   node -v
   ```

### Step 2: Install Project Dependencies
In your terminal, navigate to the project folder and run:
```bash
npm install
```

### Step 3: Run the Development Server
Launch the local dev environment:
```bash
npm run dev
```
By default, this will compile the files and host your local dashboard at:
👉 **[http://localhost:3000](http://localhost:3000)**

---

## Commands Reference

* **`npm run dev`**: Starts the Vite local dev server with hot-module replacement (HMR).
* **`npm run build`**: Compiles and bundles production-optimized static assets in the `/dist` directory.
* **`npm run preview`**: Runs a local static preview server of the production build folder.

