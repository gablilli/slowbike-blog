# 🔗 Wix Blog Dashboard Redirect

This repository contains a simple `index.html` page that performs an **automatic redirect** to the Wix blog dashboard.

## ⚙️ How It Works

- ⏩ Redirect via `<meta http-equiv="refresh">`
- 🌀 JavaScript redirect fallback
- 🔗 Visible link in case JavaScript is disabled
- 🎨 Minimal design with loading spinner and message

## 🌍 Target URL

The page redirects to:
https://manage.wix.com/dashboard/d70d3799-d80f-4f6e-b00f-535e4063ce57/blog/overview
> ⚠️ This is the **Wix admin dashboard**. A valid Wix account login is required to access it.

## 🚀 Usage

1. Clone this repo:
   ```
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2.	Edit index.html if you want to change the destination URL (look for both the <meta http-equiv="refresh"> and the window.location.replace(...) line).
3.	Deploy using GitHub Pages or any static hosting service.
4.	Open your custom domain or GitHub Pages link → you’ll be automatically redirected to the Wix dashboard.

## 📝 Notes
•	This project is only a redirect helper.

•	The Wix dashboard cannot be hosted directly on your domain due to security restrictions.

•	Perfect if you want a neat shortcut like blogadmin.yourdomain.com pointing to your Wix dashboard.