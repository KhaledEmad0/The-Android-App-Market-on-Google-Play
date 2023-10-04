# The-Android-App-Market-on-Google-Play
Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this project, I will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. I'll look for insights into the data to devise strategies to drive growth and retention. The data for this project was scraped from the Google Play website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former.
- apps.csv: contains all the details of the apps on Google Play. These are the features that describe an app.
- user_reviews.csv: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed, passed through a sentiment analyzer engine, and tagged with its sentiment score.
# 🌐 Project Overview:
Explored the expansive Android app market, comparing over 10k apps across diverse categories.
Sought game-changing insights to fuel growth and retention strategies.
Raw data? Extracted gold from the Google Play website through some savvy web scraping!
# 💡 4 Project Phases:
1. **Data Exploration:**
- Dived deep into the data ocean.

**Data Cleaning:**
- 🧹 Removed duplicated rows.
- ✂️ Cleaned out symbols like (+, $, /).
- 🔢 Converted numeric columns to sleek float data types.

**EDA Process (Exploratory Data Analysis):**
- 📊 Which category rules the (active) app realm?
- 🏆 Is there a reigning champion category in the market?
- 📉 What categories are the underdogs?
- 📏 Size matters? Explored the impact of app size on ratings.
- ⚙️ System-heavy or light? Unraveled user preferences.
- 💸 Does an app's price sway its rating?
- 💰 Free or paid? Unveiled the popularity dynamics.
- 📣 User reviews sentiment? Analyzed the vibes.

**Data Visualization:**
- 📈 Leveraged Matplotlib, Seaborn, and Plotly for captivating visualizations.
- 📊 Explored data aesthetics with Histograms, Box Plots, and Joint Plots.
