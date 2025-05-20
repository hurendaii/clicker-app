# Clicker App 

A simple clicker web application built using HTML, CSS, and JavaScript.

## Features

- Minimal design
- Live click counter
- Responsive layout
- Styled with custom CSS

## 🌐 Deploying on Azure (Free Tier)

You can deploy this app to **Azure Blob Storage** using the free tier:

### 1. Create a Storage Account

1. Go to [Azure Portal](https://portal.azure.com)
2. Click **Create a resource > Storage Account**
3. Fill in:
   - **Resource group**: Create or choose one
   - **Storage account name**: Unique name like `clickerstaticweb`
   - **Region**: Closest to you
   - **Performance**: Standard
   - **Redundancy**: Locally Redundant (LRS)
4. Click **Review + Create > Create**

### 2. Enable Static Website Hosting

1. Go to the **Storage Account**
2. Click **"Static website"** under **Data management**
3. Enable it:
   - **Index document name**: `index.html`
   - Leave **Error document** blank or as `404.html` (optional)
4. Click **Save**

You’ll now see a **primary endpoint URL** — this will be your website URL.

### 3. Upload Your Files

1. In the Storage Account, go to **Containers > $web**
2. Click **Upload**
3. Upload:
   - `index.html`
   - `style.css`
4. Set **Blob type** to `Block blob`, leave everything else default
5. Click **Upload**

### 4. Test Your App

Open the **primary endpoint URL** (looks like `https://yourstoragename.z13.web.core.windows.net`) in a browser — your app should be live!

## 🧾 License

MIT

---
