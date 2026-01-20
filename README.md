## 📋 Overview

NutriVision identifies food from images and provides personalized health recommendations. This system calculates comprehensive healthiness scores and suggests better alternatives based on your dietary goals.

**Key Innovation:** Combines CNN-based food recognition with a custom health scoring algorithm that factors in multiple nutrients to rank recipes and suggest healthier alternatives.

**Live Demo:** Upload a food image → Get instant health analysis → Discover better options

---

## ✨ Features

- **🔍 Food Recognition:** CNN classifies meals into 11 food categories
- **📊 Health Scoring:** Custom algorithm evaluates nutritional quality
- **🌱 Smart Recommendations:** Healthier alternatives within and across categories
- **📈 Visual Analytics:** Interactive nutrition comparison charts
- **🎯 Personalized Focus:** Optimize for Sodium, Cholesterol, or other nutrients
- **🚀 Real-time:** Instant analysis through web interface

---

## 🛠️ Tech Stack

**Machine Learning:** TensorFlow/Keras, CNN, Transfer Learning  
**Data:** Pandas, NumPy, Food-11 (16K images), USDA Nutrition DB, 2M+ recipes  
**Web App:** Streamlit, Altair, Custom CSS

---

## 🚀 Quick Start

```bash
# Clone and setup
git clone https://github.com/rizveea/nutrivision.git
cd nutrivision
pip install -r requirements.txt

# Download model and data (see releases)
# Place in models/ and data/ directories

# Run
streamlit run app.py
```

Navigate to `http://localhost:8501`

---

## 💻 Usage

1. **Upload** a food image
2. **Select** health focus (Sodium/Cholesterol)
3. **View** results:
   - Food classification (11 categories)
   - Health score (0-100)
   - Top 3 healthiest recipes in category
   - Better alternatives from other categories
   - Nutrition comparison charts

---

## 📊 Performance

- **Classification Accuracy:** ~85% on validation set
- **Food Categories:** 11 (Bread, Dairy, Dessert, Egg, Fried, Meat, Pasta, Rice, Seafood, Soup, Vegetables)
- **Recipe Database:** 2M+ recipes with full nutrition data
- **Inference Speed:** < 1 second per image

---

## 🧠 How It Works

### 1. Food Classification
CNN model processes uploaded image → Predicts food category with confidence score

### 2. Health Scoring
Custom algorithm considers:
- Calorie density & nutrient balance
- Protein/fat/carb ratios
- Sodium & cholesterol levels
- Fiber content

### 3. Recommendations
- **Same Category:** Rank by health score
- **Cross Category:** Filter for nutrition thresholds (>120 cal, >3g protein)
- **Personalization:** Optimize for user's focus nutrient

---

## 📁 Project Structure

```
nutrivision/
├── app.py                   # Streamlit web application
├── analyze_module1.py       # Health analysis & recommendations
├── full_proj_ml.ipynb      # Model training notebook
├── requirements.txt         # Dependencies
├── models/                  # Trained CNN (not in repo)
└── data/                    # Datasets (not in repo)
```

---

## 🔮 Future Enhancements

- [ ] Expand to Food-101 (101 categories)
- [ ] Portion size estimation from images  
- [ ] Meal planning & weekly prep
- [ ] User profiles with dietary restrictions
- [ ] Nutrition tracking over time
- [ ] Mobile app (iOS/Android)
- [ ] Barcode scanner for packaged foods

---

## 👤 Author

**Rizvee A** -
- GitHub: [@rizveea](https://github.com/rizveea)
- Portfolio: [github.com/rizveea](https://github.com/rizveea)

---

## 📚 Datasets

- [Food-11 Image Dataset](https://www.kaggle.com/datasets/trolukovich/food11-image-dataset)
- [USDA Nutrition Database](https://www.kaggle.com/datasets/demomaster/usda-national-nutrient-database)
- [Recipe Nutrition DB](https://www.kaggle.com/datasets/thedevastator/better-recipes-for-a-better-life)

---

## 📝 License

MIT License - see [LICENSE](LICENSE) file

---

**⭐ Star this repo if you find it useful!**

*Last Updated: January 2025*
