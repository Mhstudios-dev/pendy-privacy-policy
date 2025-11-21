# GitHub Pages Setup for Privacy Policy

This guide will help you host your privacy policy on GitHub Pages while keeping your app code private.

## Why GitHub Pages?

- ✅ **Free hosting**
- ✅ **Easy to update**
- ✅ **Professional URL**
- ✅ **Separate from your app code** (keeps your code private)
- ✅ **Google Play accepts it**

---

## Step-by-Step Setup

### 1. Create a GitHub Account (if you don't have one)
- Go to https://github.com
- Sign up with your email: **pendytimerapp@gmail.com**
- Verify your email

### 2. Create a NEW Repository (Just for Privacy Policy)
**Important**: This will be a SEPARATE repository from your app code!

1. Click the **"+"** icon in top right → **"New repository"**
2. Fill in:
   - **Repository name**: `pendy-privacy-policy` (or any name you like)
   - **Description**: "Privacy Policy for Pendy Timer App"
   - **Public** ✅ (Privacy policies must be public, but your app code stays private)
   - ✅ Check "Add a README file"
3. Click **"Create repository"**

### 3. Add Your Privacy Policy

1. In your new repository, click **"Add file"** → **"Create new file"**
2. Name the file: `index.md`
3. Copy the entire content from `PRIVACY_POLICY.md` and paste it
4. Scroll down and click **"Commit new file"**

### 4. Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### 5. Get Your Privacy Policy URL

After a few minutes, GitHub will show you the URL:
```
https://YOUR-USERNAME.github.io/pendy-privacy-policy/
```

**Example**: If your GitHub username is `mhstudios`, the URL would be:
```
https://mhstudios.github.io/pendy-privacy-policy/
```

This is the URL you'll use in Google Play Console!

---

## Your App Code Stays Private

**Important**: Your main app code repository can remain **completely private**. Only this privacy policy repository needs to be public (because privacy policies must be publicly accessible).

### To Keep Your App Code Private:

1. Create a SEPARATE repository for your app code
2. Name it something like: `PendulumTimer-Private`
3. Set it to **Private** when creating
4. Upload your app code there
5. Only you can see it!

---

## Updating Your Privacy Policy

Whenever you need to update the privacy policy:

1. Go to your `pendy-privacy-policy` repository
2. Click on `index.md`
3. Click the **pencil icon** (Edit)
4. Make your changes
5. Click **"Commit changes"**
6. Changes go live in 1-2 minutes!

---

## Alternative: Simple HTML Version

If you prefer a cleaner look, you can create `index.html` instead:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pendy - Privacy Policy</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        h1 { color: #2c3e50; }
        h2 { color: #34495e; margin-top: 30px; }
        .contact { background: #f8f9fa; padding: 15px; border-radius: 5px; }
    </style>
</head>
<body>
    <!-- Paste your privacy policy content here -->
</body>
</html>
```

---

## For Google Play Console

When filling out your app listing:

1. Go to **"Store presence"** → **"Privacy policy"**
2. Enter your GitHub Pages URL:
   ```
   https://YOUR-USERNAME.github.io/pendy-privacy-policy/
   ```
3. Save!

Google will verify that the URL is accessible and contains a privacy policy.

---

## Summary

✅ **Privacy Policy**: Public on GitHub Pages
✅ **App Code**: Private repository (separate)
✅ **URL**: `https://YOUR-USERNAME.github.io/pendy-privacy-policy/`
✅ **Cost**: $0 (completely free)
✅ **Updates**: Edit anytime, live in minutes

---

## Need Help?

If you run into any issues:
1. Make sure the repository is **Public**
2. Make sure GitHub Pages is **enabled** in Settings
3. Wait 2-3 minutes after enabling Pages
4. Check that `index.md` exists in the repository
5. Try accessing the URL in an incognito/private browser window

Your privacy policy will be live and ready for Google Play! 🚀
