# Vineet's Guestbook

A simple, modern, and local-first **Guestbook Website** inspired by Matt Palmer. Built using **HTML + Tailwind CSS + Vanilla JS**, this project lets visitors leave short messages and read past entries.

## ✨ Features

- **Sign the guestbook** with your **Name**, **Emoji (mood)**, and **Message**
- **Local-first storage**: Messages are saved in your browser using `localStorage`
- **Export/Import** entries as JSON backup
- **Dark mode** toggle (saved in localStorage)
- **Pagination**: Automatically paginates after 10 messages
- **Likes & Delete** options for each entry
- **Relative timestamps** (e.g., “2 hours ago”) with timezone support (IST by default)
- **Home button** linking back to [Vineet's main website](https://letcodewithvineet.github.io/vineet-mywebsite/)
- **Admin-only Clear All**: Hidden from public users. Enable by visiting `?admin=1`

## 🚀 Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/<your-username>/vineet-guestbook.git
cd vineet-guestbook
```

### 2. Open in browser

Just open `index.html` in your browser. No build step required.

### 3. Deploy on GitHub Pages

1. Push your repo to GitHub.
2. Go to **Settings → Pages**.
3. Set the branch to `main` and folder to `/ (root)`.
4. Your site will be live at:
   ```
   https://<your-username>.github.io/vineet-guestbook/
   ```

## 🛠 Tech Stack

- **Tailwind CSS** (via CDN)
- **Vanilla JavaScript**
- **HTML5**

## 🔑 Admin Controls

- By default, the **Clear All** button is hidden.
- To enable admin mode, visit the site with:
  ```
  index.html?admin=1
  ```
  This will unlock the button on that browser.

## 📸 Screenshot

![Screenshot](screenshot.png)

## 📄 License

This project is open-source and free to use. Modify and deploy your own version!

---

💡 Built with ❤️ by Vineet
