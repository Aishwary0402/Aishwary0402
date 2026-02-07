# 🚀 GitHub Profile Setup Instructions

## Overview
This package contains all files needed to create a professional GitHub profile similar to the reference (UHM1912). The profile includes:
- Animated typing headers
- Wave animations
- Skill badges
- GitHub statistics
- Contribution snake animation
- Project showcases

---

## 📁 Files Included

1. **README.md** - Main profile README with your information
2. **.github/workflows/snake.yml** - GitHub Actions workflow for snake animation
3. **SETUP_GUIDE.md** - This file

---

## 🔧 Setup Steps

### Step 1: Create a Special Repository

1. Go to GitHub: https://github.com/new
2. Create a repository with the **EXACT** same name as your username: `Aishwary0402`
3. Make it **Public**
4. Check "Add a README file" (you'll replace this)
5. Click "Create repository"

### Step 2: Upload Files

**Option A: Via GitHub Web Interface**
1. Go to your new repository: https://github.com/Aishwary0402/Aishwary0402
2. Click "Add file" → "Upload files"
3. Upload the `README.md` file
4. Commit the changes

**Option B: Via Git Command Line**
```bash
# Clone your new repository
git clone https://github.com/Aishwary0402/Aishwary0402.git
cd Aishwary0402

# Copy the README.md file to the repository
cp /path/to/downloaded/README.md .

# Create the workflow directory and file
mkdir -p .github/workflows
cp /path/to/downloaded/.github/workflows/snake.yml .github/workflows/

# Commit and push
git add .
git commit -m "✨ Initial profile setup with animations"
git push origin main
```

### Step 3: Enable GitHub Actions

1. Go to your repository settings
2. Click "Actions" in the left sidebar
3. Under "Actions permissions", select "Allow all actions and reusable workflows"
4. Click "Save"

### Step 4: Run the Snake Animation

1. Go to the "Actions" tab in your repository
2. Click on "Generate Snake" workflow
3. Click "Run workflow" → "Run workflow"
4. Wait for it to complete (creates the snake animation)

**Note**: The snake animation will auto-update every 12 hours once set up.

---

## 🎨 Customization Guide

### Update Your LinkedIn Link
In README.md, find and replace:
```markdown
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aishwary-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aishwary-singh-rathour)
```
Replace `aishwary-singh-rathour` with your actual LinkedIn username.

### Update Project Links
Each project has a placeholder link `https://github.com/Aishwary0402`. Replace these with:
- Actual repository URLs once you create project repos
- Or remove projects you haven't built yet

### Add Profile Picture
Consider adding a professional banner image:
1. Create a banner (recommended size: 1200x300px)
2. Upload to your repository
3. Add at the top of README.md:
```markdown
![Banner](./banner.png)
```

### Customize Colors
You can change the color schemes in the URLs:
- Wave animations: `color=0:18C8F9,100:1E88E5` (blue gradient)
- GitHub stats theme: `theme=tokyonight` (other options: radical, merko, gruvbox, etc.)

---

## 🔍 Verification

After setup, check:
1. ✅ Your profile shows at: https://github.com/Aishwary0402
2. ✅ README displays correctly with animations
3. ✅ Snake animation appears (may take first run)
4. ✅ All badges and stats show properly

---

## 🐛 Troubleshooting

### Snake Animation Not Showing
- Wait 5-10 minutes after first workflow run
- Check Actions tab for any errors
- Make sure the workflow has permissions (Settings → Actions → General)

### Stats Not Loading
- GitHub stats API can be slow
- Try refreshing after a few minutes
- Check if your username is correct in the URLs

### Broken Links
- Update all `Aishwary0402` references if your username differs
- Replace project links with actual repositories

---

## 📝 Optional Enhancements

### Add More Sections
You can add:
- Blog posts (using dev.to integration)
- Recent activity
- Spotify currently playing
- WakaTime stats (coding time tracker)

### Create Project Banners
For each project, create a cover image:
1. Use Canva or Figma (1200x630px)
2. Upload to project repository
3. Add to Featured Projects section

### Add Visitor Counter
The profile already includes a visitor counter at the bottom. It will automatically track views.

---

## 🌟 Pro Tips

1. **Keep It Updated**: Update projects and skills regularly
2. **Pin Repositories**: Pin your best 6 repositories on your profile
3. **Write Good READMEs**: Each project should have a detailed README
4. **Use Topics**: Add relevant topics to your repositories for discoverability
5. **Maintain Streak**: Commit regularly to keep your contribution graph active

---

## 📚 Additional Resources

- [GitHub Profile README Guide](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [Shields.io](https://shields.io/) - Create custom badges
- [Skill Icons](https://skillicons.dev/) - Technology skill icons
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - Dynamic stats cards

---

## 🤝 Need Help?

If you encounter any issues:
1. Check the Actions tab for workflow errors
2. Verify all files are in correct locations
3. Ensure repository name matches username exactly
4. Make repository public (private repos won't show)

---

## ✅ Checklist

- [ ] Created repository named `Aishwary0402`
- [ ] Repository is public
- [ ] Uploaded README.md
- [ ] Created .github/workflows/snake.yml
- [ ] Enabled GitHub Actions
- [ ] Ran snake workflow successfully
- [ ] Updated LinkedIn URL
- [ ] Verified profile displays correctly
- [ ] Pinned best repositories

---

**Happy Coding! 🚀**

*Remember: Your GitHub profile is your professional portfolio. Keep it polished and up-to-date!*
