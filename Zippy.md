# **📘 Zippy App – Full User Guide**

Zippy is a **complete media toolkit** for macOS.  
 It makes everyday media tasks easy — such as converting files, separating video and audio, extracting archives, downloading online content, or stopping hung processes.  
 The interface is simple: just open the app, choose an option, and you’re done.

---

## **🔹 1\. Installation & First Run**

### **Step 1 – Copy the App**

* To install Zippy, simply drag and drop **`Zippy.app` into the `/Applications` folder**.

* Recommended: keep it in `/Applications` so it is properly registered in macOS “Open With” menus.

### **Step 2 – First Launch (Security Prompt)**

* macOS may block new apps the first time they’re opened.

* Fix: In Finder → Right-click on Zippy → **Open**.

* A prompt will appear: *“This app is from an unidentified developer.”*

* Click **Open**.

* From then on, you can launch it by double-clicking normally.

### **Step 3 – Automatic Setup**

On the first run, Zippy automatically:

* Clears macOS security flags (so you don’t repeatedly see “App can’t be opened” errors).

* Registers itself in Finder’s **“Open With” menus**.

* Prepares its internal components so everything is ready to run.

* Refreshes Finder so you see the new options immediately.

---

## **🔹 2\. Ways to Launch the App**

1. **Normal launch** – Double-click Zippy, and the main menu appears.

2. **Drag & Drop** – Drag files or folders onto the Zippy icon → the app opens with those items pre-selected.

3. **From the context menu** – Right-click any file → **Open With → Zippy** → the file opens directly in Zippy.

---

## **🔹 3\. Features in Detail**

### **A) 📽️ Media Converter**

This option provides multiple conversion modes:

* **Convert to MP4** → Fast and widely compatible (TVs, mobiles, browsers).

* **Convert to MOV** → Best for editing workflows (Final Cut Pro, Premiere, DaVinci Resolve, etc.).

* **Convert to MP3** → Extracts just the audio track from a video.

* **Convert to PNG** → Breaks a video into frames and saves them as numbered PNG images.

* **HDR → SDR** → Converts High Dynamic Range videos into standard SDR so they look correct on normal screens.

* **Best Conversion** → Highest quality setting (slower but results are crystal-clear).

**Batch Support:**

* You can drop a single file, multiple files, or entire folders.

* Zippy will automatically scan inside folders and process all files.

* Output files are always saved in the original folder (with a suffix or changed extension).

---

### **B) 🎵 Audio Video Split**

* Select one or multiple files (folders are also allowed).

* Zippy saves the video separately and extracts each audio track into its own file.

* Example: If a video has 3 audio tracks (e.g. English, Hindi, Commentary), you’ll get three separate audio files.

* Video formats are chosen intelligently (MOV, MP4, or MKV).

* Audio tracks are saved with correct extensions automatically (e.g. MP3, M4A, FLAC, WAV).

---

### **C) 📥 Files Download**

You’ll get 4 options:

1. **Video Download** – Save an online video as a local file.

2. **Audio Download** – Save only the audio (useful for music tracks).

3. **Torrent Download** – Download from torrent magnet links or `.torrent` files.

4. **HLS/DASH Grabber** – Convert streaming links (m3u8/DASH) into playable video files.

👉 Zippy will prompt you to enter one or more links. Processed files are automatically saved into your **Downloads folder**.

---

### **D) 🌐 Stream Grabber (Advanced)**

* If you have a streaming link (m3u8, DASH, etc.), this feature saves it as a playable video file.

* Some streams may require you to enter a **Referer URL** and a **Cookie** (if the site requires login).

* Output is always saved as `video.mp4` in the **Downloads folder**.

* Zippy creates a temporary working folder and cleans it up once the task is complete.

---

### **E) 📦 Extract Archives**

* Supports ZIP, RAR, 7Z, ISO, DMG, TAR, GZ, BZ2, XZ, APK, JAR, WAR, RPM, CAB, and many other archive formats.

* If you have multiple archives in one folder, you can extract them all at once.

* Extracted files are automatically created in the same folder as the original archive.

* For ZIP files, Zippy uses macOS’s fast built-in method; for other formats, it uses a universal extractor.

---

### **F) 🛑 Force Quit All**

* If a background task gets stuck (like a conversion or download), this option instantly stops them all.

* You’ll see a notification: *“All processes force-quit.”*

---

## **🔹 4\. Notifications**

* After every task, Zippy shows a macOS notification:

  * Success → *“Done: X files processed”*

  * Error → Filename \+ error message

* This way, you always know the status of background tasks.

---

## **🔹 5\. Troubleshooting**

* **App won’t open** → On the first run, always use **Right-click → Open**.

* **Zippy not showing in “Open With”** → Reopen the app, or manually run the included registration helper script.

* **Download/Stream failing** → Check that the link is valid and accessible. If login is required, provide the correct Referer and Cookie.

* **Conversion failed** → The file may be corrupt or unsupported. Try with another file.

* **Process stuck** → Use the **Force Quit All** option.

---

## **🔹 6\. Best Practices**

* Always keep Zippy in the `/Applications` folder.

* Dragging and dropping folders allows you to process many files at once.

* Check free disk space before large conversions or downloads.

* Only download online content you have the legal rights to.

---

## **✅ Summary**

* **Install** \= Copy to Applications → Right-click Open (first time only).

* **Use** \= Select a feature from the menu, or drag & drop files.

* **Features** \= Convert, Split, Download, Grab Streams, Extract, Force Quit.

* **Output** \= Always saved in an easy-to-find location (original folder or Downloads).

* **Safe** \= Notifications and error handling keep you informed at every step.

