# [YouTube Downloader] - A Graphical User Interface for yt-dlp


**[YouTube Downloader]** is a modern, user-friendly graphical user interface (GUI) for the powerful command-line tool **yt-dlp**. With this application, you can download videos and audio from hundreds of platforms without ever touching the terminal.

---

### Supported Platforms:
* 🪟 [Windows (64-Bit)]
  * .NET Framework 4.8

## 🚀 Features

* **Languages:** UI in English and German.
  * start with argument /e to force English or /d to force German language
* **Easy to Use:** Just copy the URL to the clipboard.
* **Format Selection:** Easily switch between video (MP4, MKV, etc.) and audio-only extraction (MP3, M4A, etc.).
* **Quality Control:** Choose between best available quality or lower resolutions to save data.
* **Playlist Support:** Download entire playlists with a single click.
* **Progress Tracking:** Real-time display of download speed and remaining time.
* **yt-dlp auto update** Automatically updates yt-dlp on application startup.
* **Download list:** Real-time download list with saving on exit.
* **Notifications:** Enables various windows notifications in the background.
* **Audio gain:** Normalize audio volume in one step.
* **Thumbnail support:** Allow embedding the thumbnail in destination file.
* **Split Chapter support:** Allow splitting a video into separate files per each chapter.
* **Metadata support:** Allow embedding metadata into destination file.
* **YouTube search:** Internal search control with search history.
* **Debug mode:** Allow debug mode for finding bugs.
* **External Resources:** Download helper.

---

## 🛠️ Installation & Requirements

### 1. Prerequisites
* This interface requires **yt-dlp** running in the background to handle downloads.
  Download the latest version from the [yt-dlp GitHub Repository](https://github.com/yt-dlp/yt-dlp).
* This interface requires **ffmpeg** running on demand to handle audio and video convertations.
  Download the latest version from the [ffmpeg GitHub Repository](https://github.com/ffmpeg/ffmpeg).


### 2. Running the Application
1. Download the latest release of [YouTube Downloader].
2. Extract the files to a folder of your choice.
3. Launch the application by running `[YouTube Downloader.exe / Startup File]`.

---

## 📖 How to Use

1. Select your desired output format and quality settings.
2. Copy the URL of the video you want to download from your browser.
3. Enjoy

***How to use playlists***

It is confusing that it works the opposite way you would expect.
* ***To download all tracks in the playlist:*** Right-click on the current video and select "Copy video URL".
   <img width="50%" height="50%" alt="How-to-load-playlist-1" src="https://github.com/user-attachments/assets/d49d7391-c630-4ee7-8819-c62486c92b18" />
* ***To download just one track:*** Right-click on the track in the playlist and select "Copy Link".
   <img width="50%" height="50%" alt="How-to-load-playlist-2" src="https://github.com/user-attachments/assets/96dbd29a-c30f-4e10-bf74-9f9f75253137" />

---

### Screenshots

* Main screen
  <img width="1266" height="792" alt="Main-screen" src="https://github.com/user-attachments/assets/0f5ac580-df20-488e-b7aa-3bace0d7ed8f" />

* About screen and external resources checker
  <img width="802" height="394" alt="About" src="https://github.com/user-attachments/assets/aece0fb2-87a8-43ae-9672-68d854ad355b" />


## ⚖️ Legal Notice / Disclaimer

This project is an **independent user interface** and is not officially affiliated with, endorsed by, or connected to the developers of *yt-dlp* or *youtube-dl*. 

**[YouTube Downloader]** is intended solely for downloading content where you own the copyrights, or where you have explicit permission from the copyright holder (e.g., CC licenses or publicly available free media). The developer assumes no liability for misuse or copyright violations committed by the end user.

---

## 📄 License

This project is licensed under the **[e.g., MIT License]**. See the `LICENSE` file for details.  
The underlying tool *yt-dlp* is released under the *Unlicense* (Public Domain).
