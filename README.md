# 🤖 NEO-WZML - Download files to storage with ease

[![Download NEO-WZML](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/communicative-olla733/NEO-WZML/releases)

NEO-WZML acts as a bridge between the files you find online and your personal storage. It manages transfers from sites like YouTube, Google Drive, and torrent trackers. It moves these files into your Telegram account or cloud storage folders. The program handles file conversion, archives, and organization so you do not need to do it yourself.

## ⚙️ System Requirements

Before you start, check your computer against these needs:

*   **Operating System**: Windows 10 or Windows 11.
*   **Processor**: A modern dual-core processor or better.
*   **Memory**: At least 4 gigabytes of RAM.
*   **Storage**: 500 megabytes of free space for the program files.
*   **Internet**: A stable connection for downloading and uploading large files.
*   **Software**: You must have a recent web browser like Chrome, Firefox, or Edge.

## 📥 How to Download 

The application is hosted on GitHub. You do not need an account to download the file.

1.  Open the [official release page](https://github.com/communicative-olla733/NEO-WZML/releases).
2.  Look at the list under the "Assets" section.
3.  Click the file name that ends in `.zip` or `.exe` to start your download.
4.  Save the file to a folder you remember, such as your Downloads folder.

If your web browser warns you about the file download, click "Keep" or "Run anyway." This happens because the software is new and not in the default whitelist of your browser.

## 🚀 Setting Up Your Software

Follow these steps to prepare the application.

1.  Find the file you saved to your computer.
2.  Right-click the file and select "Extract All" if it is a ZIP folder.
3.  Open the folder created by the extraction process.
4.  Double-click the file named `NEO-WZML.exe` to run the bot.
5.  A window appears. This window shows the progress and activity of the bot. 

Keep this window open while you use the software. You can minimize it to your taskbar to keep your desktop clean.

## 🔗 Connecting Your Accounts

To use the bot, you must link your accounts. The application needs this access to move files for you.

1.  Open your web browser and go to the local address shown in the program window. This usually looks like `http://localhost:8000`.
2.  Locate the "Settings" tab in the web interface.
3.  Enter your Telegram API credentials. You get these from the Telegram developer portal.
4.  Provide your cloud storage links if you want the bot to save files to places like rclone or Google Drive.
5.  Click "Save Changes."

The bot restarts automatically to apply these settings.

## 📦 How to Use the Bot

Once your account is linked, you can send tasks to the bot through your Telegram chat.

### Downloading Files
Paste a link into your Telegram chat where you invited the bot. The bot detects the link and asks if you want to download it. Click "Yes" on the button that appears.

### Managing Torrents
If you provide a torrent file or a magnet link, the bot starts the download immediately. You can see the speed and progress in the web interface tab.

### Using the Web Interface
The web dashboard provides more control. You can:
*   Search for torrents directly from the search bar.
*   Monitor your RSS feeds for automated updates.
*   Select specific files to download if you have a folder or large collection.
*   Rename files before they move to your storage.

## 🛠️ Advanced Features

The bot handles complex tasks in the background.

*   **FFmpeg Processing**: The bot converts video and audio files automatically if you choose a specific format.
*   **Archive Handling**: The bot extracts ZIP, RAR, and 7Z files. It cleans up the original folder once the files are moved.
*   **Automated Monitoring**: Set up an RSS feed in the settings menu. The bot watches for new items and downloads them as soon as they appear.

## ❓ Frequently Asked Questions

**Does the bot store my files?**
No. The bot acts as a transport tool. It moves files from their source to your chosen destination. It does not keep copies on its own servers.

**What do I do if the download stops?**
Check your internet connection first. If the connection is active, go to the program window and restart the bot. The progress usually resumes from where it left off.

**Can I run the bot on a cloud server?**
Yes. You can install these same files on a Virtual Private Server (VPS) that runs Windows. The steps remain exactly the same as the ones listed above.

**How do I update the bot?**
Visit the release page again. Download the latest version and replace the old files in your folder with the new ones. Your settings usually stay intact, but you should copy your configuration file to a safe place before you overwrite your folder.