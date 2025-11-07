# 🧱 Hide Google AI Overview (uBlock Origin Filter)

🧹 A simple uBlock Origin filter that hides Google’s new **AI Overview** box from search results — keeping your search results clean and distraction-free.

---

## 🚀 Features

- Hides the **AI Overview / AI Summary** section that appears above normal Google Search results.  
- Works across languages and regions.  
- Lightweight — only a few CSS-style filters.  
- No scripts, no performance impact.

---

## 🧩 Requirements

You’ll need **uBlock Origin** installed in your browser.

### 🦊 **Firefox**
👉 [Install uBlock Origin on Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)

### 🧭 **Chrome / Chromium (Lite version)**
👉 [Install uBlock Origin Lite on Chrome](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh)
(uBlock Origin Lite because uBlock Origin stopped their support for Chrome after Chrome 139 update)

Compatible with Chrome, Edge, Brave, Vivaldi, and Opera.
---

## ⚙️ Installation

🛡️ **uBlock Origin:**
1. Open the **uBlock Origin dashboard**  
   - Click the uBlock icon → ⚙️ → **Dashboard**

2. Go to the **“My filters”** tab.

3. Open this repository’s [**GoogleAiOverviewHide.scss**](./GoogleAiOverviewHide.scss) file and copy its contents.

4. Paste the copied filters into the **My filters** text area.

5. Click **Apply changes**.

6. Refresh any Google search results page — the AI Overview box should now be hidden ✅

🛡️ **uBlock Origin Lite:**
1. Open the **uBlock Origin Lite dashboard**  
   - Click the uBlock icon → ⚙️ → **Dashboard**

2. Go to the **"Personalized Filters"** tab.

3. Open this repository’s [**GoogleAiOverviewHide.scss**](./GoogleAiOverviewHide.scss) file and copy its contents.

4. Paste the copied filters into the **Import/Export** text area.

5. Click **Import and Attach**.

6. Refresh any Google search results page — the AI Overview box should now be hidden ✅

---

## 🧠 How It Works

This filter uses **CSS selectors** (supported by uBlock Origin’s element hiding syntax) to remove the HTML elements Google uses to display the **AI Overview** summary at the top of search results.  
It doesn’t interfere with network requests or block normal results — it simply hides that specific box.

---

## ⚠️ Notes

- Google frequently changes internal class names (like `.GcKpu`, `.hdzaWe`, etc.).  
- If the filter stops working, open your browser’s DevTools (**Inspect Element**) and update the selectors in `GoogleAiOverviewHide.scss`.  
- This filter hides only the **AI Overview** — it does **not** remove or hide the “AI mode” tab/button.

---

## 📜 License

[MIT License](LICENSE)

## 👤 Author

xolossus

Designed for a seamless quality viewing experience.
