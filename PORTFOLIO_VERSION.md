# NutriVision - Portfolio Version

## What's Different from the Fork?

This is your **personal portfolio version** of the group project, enhanced with:

### ✅ Professional Documentation
- Comprehensive README with badges, features, tech stack
- Detailed setup guide in docs/SETUP.md
- Clear model and data documentation

### ✅ Better Code Quality
- Improved error handling in app.py
- Added model caching for performance
- Better session state management
- Professional code comments

### ✅ GitHub Best Practices
- Professional .gitignore (excludes large files)
- MIT License
- Proper requirements.txt
- Clean project structure

### ✅ Portfolio-Ready
- Emphasizes YOUR contributions
- Showcases technical skills
- Professional presentation
- Ready to share with recruiters

---

## How to Use This for Your Portfolio

### 1. Delete the Fork

**In GitHub:**
1. Go to your forked repo: https://github.com/rizveea/NutriVision
2. Settings → Danger Zone → Delete this repository
3. Type repository name to confirm

### 2. Create Fresh Repository

```bash
# From your local machine
cd path/to/NutriVision_Improved

# Initialize git
git init

# Add files
git add .

# First commit
git commit -m "Initial commit: NutriVision - AI Food Health Dashboard"

# Create repo on GitHub (https://github.com/new)
# Name: nutrivision
# Description: AI-powered food recognition and health analysis system
# Public

# Connect and push
git remote add origin https://github.com/rizveea/nutrivision.git
git branch -M main
git push -u origin main
```

### 3. Add Missing Files

**Before first use, add these files (not in Git):**

1. `models/food_classifier.keras`
   - Get from your team's Google Drive
   - Or download from releases (if you create one)

2. `data/full_recipes_with_nutrition_and_cnn_class-1.csv`
   - Get from team's shared data
   
3. (Optional) Add screenshot to `images/` for README

### 4. Pin to Profile

1. Go to https://github.com/rizveea
2. Click "Customize your pins"
3. Select "nutrivision"
4. Save

---

## Project Highlights for Resume/LinkedIn

**"NutriVision - AI Food Health Dashboard"**

- Built CNN-based food classification system (85% accuracy, 11 categories)
- Developed custom health scoring algorithm using multi-nutrient analysis
- Created recommendation engine with 2M+ recipe database
- Deployed interactive Streamlit web application
- **Tech:** Python, TensorFlow, Keras, Streamlit, Pandas, Altair

**Key Achievements:**
- ✅ Real-time food recognition (< 1 sec inference)
- ✅ Smart filtering excluding 1M+ non-meal items
- ✅ Personalized recommendations based on dietary focus
- ✅ Interactive data visualizations

---

## What to Say in Interviews

**"Tell me about this project":**

*"NutriVision is an AI-powered food health dashboard I built as part of a machine learning course. Unlike basic calorie counters, it uses a CNN to classify food images into 11 categories, then applies a custom health scoring algorithm that considers multiple nutrients - not just calories - to rank recipes and suggest healthier alternatives.*

*The system analyzes a 2-million recipe database and filters intelligently to exclude things like beverages and condiments. Users can personalize recommendations based on their dietary goals, like reducing sodium or cholesterol.*

*I deployed it as a Streamlit web app with interactive visualizations. The technical stack includes TensorFlow for the CNN, Pandas for data processing, and Altair for charts. It achieves about 85% classification accuracy and provides recommendations in under a second."*

**"What was your specific contribution?":**

*"This was a group project where I focused on [choose based on your actual role]:*
- *The health scoring algorithm and recommendation logic*
- *Data preprocessing and the 2M recipe database integration*
- *The Streamlit web application and user interface*
- *Model training and optimization*

*For my portfolio version, I enhanced the code quality, added comprehensive documentation, and made it production-ready with proper error handling."*

---

## Next Steps to Enhance Further

### Quick Wins:
- [ ] Add screenshots to README
- [ ] Create a demo GIF showing the app in action
- [ ] Add your actual LinkedIn/portfolio links

### Future Enhancements:
- [ ] Deploy to Streamlit Cloud (free hosting)
- [ ] Add more food categories (Food-101 has 101!)
- [ ] Implement portion size estimation
- [ ] Create API endpoints
- [ ] Add user authentication
- [ ] Build nutrition tracking over time

---

## Files Overview

**Core Application:**
- `app.py` - Main Streamlit web interface
- `analyze_module1.py` - Health analysis logic
- `full_proj_ml.ipynb` - Model training notebook

**Documentation:**
- `README.md` - Main project documentation (CUSTOMIZED!)
- `docs/SETUP.md` - Setup instructions
- `LICENSE` - MIT License
- `PORTFOLIO_VERSION.md` - This file

**Configuration:**
- `requirements.txt` - Python dependencies
- `.gitignore` - Git exclusions (prevents large files)

**Directories:**
- `models/` - Trained CNN (excluded from Git)
- `data/` - Recipe database (excluded from Git)
- `images/` - Screenshots for README
- `docs/` - Additional documentation

---

## Remember

- ✅ This is YOUR portfolio version
- ✅ Update README with your links
- ✅ Customize based on YOUR actual contributions
- ✅ Delete old fork before creating this repo
- ✅ Don't forget to add model & data files locally

**This showcases your ML, data processing, and deployment skills professionally!**

Good luck! 🚀
