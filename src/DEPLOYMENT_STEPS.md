# 🚀 STEP-BY-STEP: HOW TO DEPLOY YOUR WEBSITE

Follow these **EXACT STEPS** in order. Don't skip any step!

---

## ✅ **STEP 1: OPEN GITHUB DESKTOP**

1. Open the **GitHub Desktop** application on your computer
2. Make sure you're on the **"aipedia"** repository (top left corner)
3. Make sure you're on the **"main"** branch (top middle)

**Screenshot:** You should see a list of changed files on the left side

---

## ✅ **STEP 2: CHECK THE CHANGED FILES**

In GitHub Desktop, you should see these files in the **"Changes"** tab:

```
✅ Modified:
   📝 utils/supabase/client.tsx

✅ Added (New files):
   📄 .github/workflows/deploy.yml
   📄 public/404.html
   📄 public/.nojekyll
   📄 public/favicon.svg
   📄 GITHUB_PAGES_FIX.md
   📄 DEPLOYMENT_STEPS.md

✅ Deleted:
   🗑️ workflows/deploy.yml (old location - wrong folder)
```

**If you see these files, you're good to go!** ✅

---

## ✅ **STEP 3: WRITE COMMIT MESSAGE**

At the bottom left of GitHub Desktop, you'll see:

**"Summary (required)"** - A text box

Type this EXACT message:
```
Fix GitHub Pages white screen deployment issue
```

**Description (optional)** - You can leave this empty OR type:
```
- Fixed workflow file location (.github/workflows/)
- Added 404.html for SPA routing
- Added .nojekyll for Vite builds
- Fixed Supabase import
- Added favicon
```

---

## ✅ **STEP 4: COMMIT TO MAIN**

1. Click the big blue button at the bottom left that says:
   ```
   Commit to main
   ```

2. **Wait 2 seconds** - The button will change

3. After committing, you'll see the files disappear from the "Changes" tab

**✅ SUCCESS!** Your changes are now saved locally

---

## ✅ **STEP 5: PUSH TO GITHUB**

Now you'll see a new button at the top that says:
```
Push origin
```

**CLICK IT!**

This uploads your changes to GitHub.com

**⏱️ Wait:** This might take 10-30 seconds depending on your internet speed

---

## ✅ **STEP 6: OPEN GITHUB.COM**

1. Open your web browser (Chrome, Firefox, etc.)

2. Go to this URL:
   ```
   https://github.com/rishuchauhan-1/aipedia
   ```

3. You should see your repository

---

## ✅ **STEP 7: CHECK GITHUB ACTIONS**

1. On your GitHub repository page, click the **"Actions"** tab at the top

   **URL:** https://github.com/rishuchauhan-1/aipedia/actions

2. You should see a workflow running with the name:
   ```
   Fix GitHub Pages white screen deployment issue
   ```

3. It will show a **🟡 yellow circle** (running) or **🟢 green checkmark** (done)

**⏱️ WAIT TIME:** 2-4 minutes

---

## ✅ **STEP 8: WAIT FOR GREEN CHECKMARK**

**DO NOT CLOSE THE BROWSER!**

The page will show:

- 🟡 **Yellow circle** = Building... (WAIT!)
- 🟢 **Green checkmark** = Success! (DONE!)
- 🔴 **Red X** = Failed (Tell me if you see this!)

**Refresh the page every 30 seconds** to check the status

---

## ✅ **STEP 9: VISIT YOUR LIVE WEBSITE**

Once you see the **🟢 GREEN CHECKMARK**, your website is LIVE!

**Your website URL:**
```
https://rishuchauhan-1.github.io/aipedia/
```

1. Open a **NEW TAB** in your browser
2. Copy and paste the URL above
3. Press **ENTER**

---

## 🎉 **STEP 10: TEST YOUR WEBSITE**

You should now see:

✅ **AiPedia homepage** with blue/purple gradient
✅ **"Discover the Best AI Tools"** heading
✅ **Category cards** (Text & Writing, Image Generation, etc.)
✅ **Dark mode toggle** in the top right (moon icon)
✅ **Foi chatbot** in the bottom right corner (sparkle icon)
✅ **Navigation menu** (Home, AI Tools, About Us, Contact Us)

---

## 🐛 **IF YOU STILL SEE WHITE SCREEN:**

### Option 1: Hard Refresh
1. Press **Ctrl + Shift + R** (Windows/Linux)
2. Or **Cmd + Shift + R** (Mac)
3. This clears the cache and reloads

### Option 2: Clear Browser Cache
1. Press **Ctrl + Shift + Delete** (Windows/Linux)
2. Or **Cmd + Shift + Delete** (Mac)
3. Select "Cached images and files"
4. Click "Clear data"
5. Refresh the page

### Option 3: Try Private/Incognito Mode
1. Press **Ctrl + Shift + N** (Chrome)
2. Or **Ctrl + Shift + P** (Firefox)
3. Go to: https://rishuchauhan-1.github.io/aipedia/

### Option 4: Check Browser Console
1. Press **F12** on your keyboard
2. Click the **"Console"** tab
3. Take a screenshot of any **RED errors**
4. Send me the screenshot

---

## 📸 **WHAT SHOULD YOU SEE?**

Your homepage should look like this:

```
┌─────────────────────────────────────────────┐
│  🏠 AiPedia    AI Tools  About Us  Contact  │
│                              🌙 👤          │
├─────────────────────────────────────────────┤
│                                             │
│     Discover the Best AI Tools              │
│     Your Complete AI Tools Directory        │
│                                             │
│     [Explore AI Tools]  [Learn More]        │
│                                             │
├─────────────────────────────────────────────┤
│  Browse by Category                         │
│                                             │
│  [📝 Text & Writing]  [🎨 Image]           │
│  [🎬 Video]           [🎵 Audio]           │
│  [💻 Code]            [🔍 Search]          │
│                                             │
└─────────────────────────────────────────────┘
                                    ✨ Foi Bot
```

---

## 🎯 **QUICK CHECKLIST**

Use this to make sure you did everything:

- [ ] Opened GitHub Desktop
- [ ] Saw changed files listed
- [ ] Typed commit message
- [ ] Clicked "Commit to main"
- [ ] Clicked "Push origin"
- [ ] Opened GitHub.com/actions page
- [ ] Waited for green checkmark ✅
- [ ] Visited https://rishuchauhan-1.github.io/aipedia/
- [ ] Saw AiPedia website (not white screen!)

---

## 💡 **TROUBLESHOOTING**

### Problem: GitHub Desktop says "No changes"
**Solution:** The files are already committed. Skip to STEP 5 (Push origin)

### Problem: "Push origin" button is grayed out
**Solution:** Everything is already pushed. Skip to STEP 7 (Check Actions)

### Problem: GitHub Actions shows red X ❌
**Solution:** 
1. Click on the failed workflow
2. Click on "build" job
3. Take a screenshot of the error
4. Send it to me

### Problem: Website shows 404 error
**Solution:** Wait 5 more minutes. GitHub Pages takes time to activate.

### Problem: Website still shows white screen after 10 minutes
**Solution:**
1. Press F12 (open developer tools)
2. Click "Console" tab
3. Screenshot any errors
4. Send to me

---

## 📞 **NEED HELP?**

If you're stuck at ANY step, tell me:

1. **Which step number** you're on (1-10)
2. **What you see** on your screen
3. **What happens** when you try to do the step
4. Take a **screenshot** if possible

I'll help you fix it immediately!

---

## 🎉 **CONGRATULATIONS!**

Once you complete all 10 steps, your **AiPedia** website will be:

✅ **Live on the internet**
✅ **Accessible to anyone** worldwide
✅ **Fully functional** with all features
✅ **Mobile responsive**
✅ **Fast and optimized**

**Your website URL:**
```
https://rishuchauhan-1.github.io/aipedia/
```

**Share this URL** with friends, professors, or on social media!

---

## 👥 **CREDITS**

**AiPedia** - Your Complete AI Tools Directory

**Created by:**
- Ritesh Thakur (ritesh_2503mc03@iitp.ac.in)
- Rishu Kumar (rishu_2503ct03@iitp.ac.in)

**Tech Stack:**
- React + TypeScript + Vite
- Tailwind CSS 4.0
- Supabase Authentication
- GitHub Pages Hosting
- 500+ AI Tools Database
- Foi Chatbot (Gemini-powered)

---

## ⏰ **TOTAL TIME NEEDED**

- Steps 1-5: **2 minutes** (your actions)
- Steps 6-7: **3-4 minutes** (GitHub builds the site)
- Steps 8-10: **1 minute** (testing)

**TOTAL: About 6-7 minutes** from start to finish

---

## 🚀 **START NOW!**

Go back to **STEP 1** and follow each step carefully.

**You got this!** 💪

Your website will be live in less than 10 minutes!
