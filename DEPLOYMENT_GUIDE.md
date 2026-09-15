# ICSE AI Tutor - Vercel Deployment Guide
## DPS Megacity Kolkata

---

## **Quick Start (5 minutes)**

### **Step 1: Prepare Your Files**

I've created `icse-tutor.html` - a complete, standalone application. You don't need any other files!

---

### **Step 2: Create a Vercel Account**

1. Go to [vercel.com](https://vercel.com)
2. Click **"Sign Up"**
3. Choose **"Continue with GitHub"** OR **"Continue with Email"**
4. Complete the registration

> Works on both Mac and Windows 11

---

### **Step 3: Deploy on Vercel (2 options)**

#### **Option A: Drag & Drop (Easiest)**

1. Go to [vercel.com/new](https://vercel.com/new)
2. Scroll down to **"Deploy a static project"**
3. Look for **"Or, drag and drop your project folder here"**
4. Drag the `icse-tutor.html` file into the box
5. Vercel will deploy automatically
6. Your app is now **LIVE!** 🎉

#### **Option B: GitHub (Recommended for updates)**

1. **On your computer (Mac or Windows):**
   - Create a folder called `icse-tutor`
   - Put `icse-tutor.html` inside
   - Create a file named `vercel.json` (see below)

2. **Create `vercel.json`** in the same folder:
```json
{
  "buildCommand": "echo 'Deploying static site'",
  "outputDirectory": ".",
  "public": true
}
```

3. **Upload to GitHub:**
   - Create a GitHub account (if you don't have one): [github.com](https://github.com)
   - Create a new repository called `icse-tutor`
   - Upload your files to GitHub

4. **Connect to Vercel:**
   - Go to [vercel.com/new](https://vercel.com/new)
   - Click **"Import Project"**
   - Select your GitHub repository
   - Click **"Deploy"**

5. **Your live URL will look like:**
   ```
   https://icse-tutor.vercel.app
   ```

---

## **Access Your Live Tutor**

### **Share the URL with your son:**
```
https://your-project-name.vercel.app
```

### **On Mac & Windows 11:**
- Open any web browser (Chrome, Safari, Edge, Firefox)
- Paste the URL
- Start learning!

---

## **How It Works**

### **First Time Access:**
1. Click **"Register"** tab
2. Enter:
   - Name (e.g., "Aditya")
   - Email (e.g., aditya@example.com)
   - Password
3. Click **"Create Account"**

### **Next Logins:**
- Use the same email and password
- Progress is saved automatically

---

## **Features**

✅ **8 ICSE Subjects:**
- Mathematics
- Physics
- Chemistry
- Biology
- English
- History
- Civics
- Geography

✅ **Three Modes:**
1. **Learn** - AI-generated explanations
2. **Practice** - Problem solving with feedback
3. **Test** - 5-question quizzes (50 bonus points for all correct)

✅ **Progress Tracking:**
- Points earned
- Correct answers count
- Current streak
- Subjects studied

✅ **Works Offline** (after first load)

---

## **Frequently Asked Questions**

### **Q: Can multiple students use the same app?**
**A:** Yes! Each student creates their own account with their own progress tracking.

### **Q: Is data saved?**
**A:** Yes! Progress is saved locally on each device. When they log in from another device, they create a new account there.

### **Q: Can I see my son's progress?**
**A:** Currently saved locally. I can add a parent dashboard later to track progress across devices.

### **Q: What if he forgets his password?**
**A:** Currently no password reset. He can create a new account with a different email.

### **Q: How much does it cost?**
**A:** **Completely FREE!** Vercel's free tier is perfect for this app.

### **Q: Can I use my own domain?**
**A:** Yes! After deployment, go to Vercel dashboard → Project Settings → Domains → Add custom domain.

---

## **Troubleshooting**

### **Problem: "File not found" error**
**Solution:** Make sure `icse-tutor.html` is in the root folder you're uploading.

### **Problem: Vercel deployment fails**
**Solution:** 
- Try Option A (Drag & Drop) first
- Make sure file size is under 10MB
- Clear browser cache and try again

### **Problem: Answers not checking correctly**
**Solution:** The tutor checks for partial matches. Make sure your answer contains key words from the expected answer.

### **Problem: No questions/problems loading**
**Solution:** 
- Check internet connection
- Make sure you're using a modern browser
- Refresh the page

---

## **Customization (Optional)**

### **Change the app title:**
In `icse-tutor.html`, find this line:
```html
<title>ICSE AI Tutor - DPS Megacity Kolkata</title>
```
Change to whatever you like.

### **Add more topics:**
Find the `subjectTopics` object in the JavaScript section and add more topics to any subject.

### **Adjust points system:**
Search for `appState.totalPoints += 10` to change points values.

---

## **Next Steps**

1. ✅ Deploy the app (5 minutes)
2. 📝 Test with your son (10 minutes)
3. 💬 Give feedback for improvements
4. 🚀 Share with other students/parents

---

## **Support**

If you have issues:
1. Check browser compatibility (use Chrome for best results)
2. Try refreshing the page
3. Clear browser cookies/cache
4. Try a different browser
5. Test on both Mac and Windows devices

---

## **Ready to Deploy?**

1. Go to **[vercel.com/new](https://vercel.com/new)**
2. Drag `icse-tutor.html` into Vercel
3. Wait 30 seconds for deployment
4. Share the live URL with your son!

**Happy learning! 🎓**
