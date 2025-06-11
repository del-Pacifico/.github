# Del-Pacifico Privacy Policy 🔒

_Last updated: June 10, 2025_

Del-Pacifico (https://github.com/del-Pacifico/) is a GitHub organization **dedicated to building high-quality, privacy-first, and user-centered tools** for developers, researchers, creatives, and the open-source community. Our two flagship projects are:

- 🖼️ **Bulk Image Downloader**  
  Repo: https://github.com/del-Pacifico/bulk-image-downloader  
  *JavaScript Web-based Chromium extension:* Automated bulk image downloads, advanced gallery detection, smart grouping, clipboard hotkeys, and more.

- 🦄 **Unicode to PNG**  
  Repo: https://github.com/del-Pacifico/unicode-to-png  
  *Python script:* Convert any Unicode emoji or symbol into high-resolution PNG files using system fonts—ideal for emoji asset packs and UI prototyping.

---

## 1. What We Collect 📥

### 1.1 Bulk Image Downloader  
- 📋 **Tab metadata** (URL, title, tab ID) via `tabs` permission — used only to detect pages with images or galleries.  
- 🔗 **Image URLs** (`src` attributes of `<img>` or linked-gallery pages) — to download exactly the images you request.  
- ⚙️ **User settings** (download folder choice, simultaneous-download limit, filename prefix/suffix, `galleryMaxImages`, `gallerySimilarityLevel`) stored via `chrome.storage.sync`.  
- 📋 **Clipboard data** on demand (when you press **Ctrl+Alt+P/S**) via `clipboardRead` — sanitized and stored as your filename prefix or suffix. No passive reads.

### 1.2 Unicode to PNG  
- ✏️ **Emoji/codepoint input** you provide to the script.  
- 🚫 **No** browsing data, telemetry, or external metadata is ever collected. All processing happens locally on your machine.

---

## 2. How We Use Your Information ⚙️

### 2.1 Bulk Image Downloader  
- 💾 **Automated saving:** Save images directly to your chosen folder with incremental file naming to prevent overwrites.  
- 🚀 **On-demand script injection:** Inject our scripts/styles only when you click the toolbar icon, press **Ctrl+Alt+I**, or choose a gallery action.  
- 📊 **Progress & badge updates:** Track download progress to update the toolbar badge and (if enabled) close helper or original tabs upon completion.  
- 🗳️ **User feedback loops:** Use your survey votes and settings to shape future betas, roadmap decisions, and documentation.

### 2.2 Unicode to PNG  
- 🖼️ **Local PNG generation:** Convert the codepoint you enter into a PNG using your system fonts—no network calls.  
- 📂 **File output:** Save the generated PNG(s) to your chosen directory with your defined naming pattern.

---

## 3. Data Sharing & Disclosure 🤝  
- 🚫 **No third-party sharing:** We do **not** sell, rent, or share your data.  
- 📵 **No analytics:** We do **not** track your browsing behavior beyond the metadata described.  
- 🖥️ **Local-only processing:** All actions occur client-side in your browser or local environment; we never transmit your data to our servers.

---

## 4. Security & Retention 🛡️  
- 🔐 **Minimal permissions:** We request only the scopes essential for each tool’s functionality.  
- 🧹 **Immediate cleanup:** Injected scripts and styles are removed immediately after use to avoid lingering DOM changes or listeners.  
- ⏳ **Data lifespan:**  
  - Bulk Downloader: tab metadata & image URLs live only in memory during a session; settings persist until you change them; clipboard reads are never stored beyond your sanitized filename.  
  - Unicode to PNG: all data exists only as files you generate and store.

---

## 5. Changes to This Policy 🔄  
We may update this policy to reflect new features or permissions. When we do, we’ll update the “Last updated” date above. Please review periodically.

---

## 6. Contact Us 📬  
Questions, concerns, or feedback?  
- 🐛 Open an issue: https://github.com/del-Pacifico/.github/issues 
- 📧 Email us at: **spalmah@proton.me**

Thank you for choosing Del-Pacifico—where privacy and user empowerment come first! ❤️  
