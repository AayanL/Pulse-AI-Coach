# Pulse AI Coach - AI-Powered Habit Tracking Dashboard

A full-stack web application that combines habit tracking with predictive analytics to help users improve their daily routines through data-driven insights and AI-powered recommendations.

## 🚀 Features

- **📊 Habit Tracking**: Log daily sleep hours, water intake, and mood (1-5 scale)
- **🤖 AI Predictions**: Machine learning model predicts future mood based on habit patterns
- **📈 Real-time Visualizations**: Interactive charts showing trends and progress over time
- **🎯 Personalized Feedback**: AI-generated insights and recommendations for improvement
- **📱 Responsive Dashboard**: Clean, intuitive interface accessible on any device

| Layer | Technology |
|-------|------------|
| **Backend** | FastAPI, Python |
| **Database** | SQLite, SQLAlchemy ORM |
| **Machine Learning** | scikit-learn, pandas, numpy |
| **Data Visualization** | Matplotlib, Seaborn |
| **Frontend** | HTML, CSS, JavaScript |
| **Server** | Uvicorn ASGI server |

## 📊 How It Works

1. **Data Collection**: Users input daily sleep, water, and mood data through an intuitive web interface
2. **Trend Analysis**: System calculates 3-day rolling averages and trend slopes using linear regression
3. **AI Prediction**: Random Forest Regressor model forecasts future mood based on historical patterns
4. **Feedback Generation**: Personalized insights and recommendations generated from analysis results
5. **Visualization**: Interactive charts dynamically display progress and predictive trendlines