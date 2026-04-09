# FoodConnect Deployment Guide

## GitHub Repository Status
**Repository:** https://github.com/HarshilPatel-15/Food_Rating_Prediction.git  
**Status:** Successfully pushed to GitHub  
**Branch:** main  

## Deploy to Streamlit Community Cloud

### Step 1: Go to Streamlit Community Cloud
1. Visit https://share.streamlit.io/
2. Click "Sign in" and connect your GitHub account

### Step 2: Create New App
1. Click "New app" 
2. Select your repository: `HarshilPatel-15/Food_Rating_Prediction`
3. Select branch: `main`
4. Main file path: `app/app.py`
5. Python version: `3.9` (or latest available)
6. Click "Deploy"

### Step 3: Configuration
The app includes a `.streamlit/config.toml` file with:
- Custom theme colors
- Upload size limits
- Viewer toolbar mode

## What's Deployed

### Core Files
- `app/app.py` - Main Streamlit application
- `model/enhanced_rating_model.pkl` - Trained ML model
- `requirements.txt` - Python dependencies
- `.streamlit/config.toml` - Streamlit configuration

### Features Available
1. **Rating Predictor** - ML-based restaurant rating predictions
2. **Consumer Insights** - Budget-based dining recommendations
3. **Business Analytics** - Performance metrics for restaurant owners
4. **Industry Trends** - Market analysis for policymakers

## Expected Performance
- **Model Accuracy**: Enhanced Random Forest with R² score
- **Features**: 10 engineered features for predictions
- **Dataset**: 123,657 restaurant records
- **Cities**: Multiple metropolitan areas covered

## Troubleshooting

### If Deployment Fails
1. Check all files are pushed to GitHub
2. Verify `requirements.txt` is complete
3. Ensure model files are included in the repo
4. Check file paths in `app.py`

### Common Issues
- **Model loading errors**: Verify model file paths
- **Missing dependencies**: Check `requirements.txt`
- **Large file size**: Model file ~32MB should be acceptable

## Post-Deployment
Once deployed, your app will be available at:
`https://[your-app-name].streamlit.app`

You can:
- Share the URL with stakeholders
- Monitor app usage in Streamlit dashboard
- Update by pushing new commits to GitHub

## Support
For deployment issues:
- Streamlit documentation: https://docs.streamlit.io/
- GitHub repository: https://github.com/HarshilPatel-15/Food_Rating_Prediction
