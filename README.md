# Titanic Survival Prediction

A machine learning application that predicts survival probabilities for Titanic passengers using historical data.

## Features

- Interactive data exploration with visualizations
- Machine learning model training with multiple algorithms
- Real-time survival predictions
- Detailed analysis of survival factors
- Responsive design for all devices

## Tech Stack

- React 18 with TypeScript
- Vite for fast development and building
- Chart.js for data visualization
- TailwindCSS for styling
- React Router for navigation

## Getting Started

1. Clone the repository
2. Install dependencies:
```bash
npm install
```
3. Start the development server:
```bash
npm run dev
```

## Project Structure

- `/src/components` - Reusable UI components
- `/src/pages` - Main application pages
- `/src/utils` - Helper functions and ML algorithms
- `/src/context` - React context providers
- `/src/data` - Dataset and data types

## Machine Learning Models

The application implements three different algorithms:
- Logistic Regression
- Decision Tree
- Random Forest

## Data Features

The model uses the following passenger features:
- Passenger Class (1st, 2nd, 3rd)
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket Fare
- Port of Embarkation

## License

MIT License
