
# Movie Recommendation System

This project is an AI-powered recommendation engine for a movie recommendation system. It provides personalized movie recommendations to users based on their browsing and purchase history, as well as other relevant data. The backend is hosted on Render, and the frontend is hosted on Vercel.

## Features

- **Data Collection and Preprocessing:**
  - Gathers and preprocesses data such as user behavior, movie information, and ratings data.
  - Handles missing data and edge cases to ensure a comprehensive dataset.
  
- **Model Development:**
  - Implements a hybrid recommendation model combining collaborative filtering (using SVD) and content-based filtering (using Nearest Neighbors).
  - Uses machine learning techniques to generate personalized recommendations.
  
- **Scalability and Performance:**
  - Ensures the recommendation engine can handle high traffic.
  - Provides low-latency responses for real-time recommendations.
  
- **Evaluation and Optimization:**
  - Continuously evaluates the recommendation engine's performance.
  - Optimizes the model based on evaluation metrics to improve recommendations over time.

## Project Structure

```plaintext
├── backend
│   ├── models
│   │   ├── recommendation_model.pkl
│   │   ├── nn_model.pkl
│   ├── data
│   │   ├── movies.csv
│   ├── app.py
│   ├── model.py
│   └── requirements.txt
├── frontend
│   ├── src
│   │   ├── App.js
│   ├── public
│   ├── package.json
│   └── README.md
└── README.md
```

## Backend (Flask)

### Requirements

List the required packages in `requirements.txt`.

### Setup Instructions

1. Clone the repository.
2. Navigate to the `backend` directory.
3. Install dependencies using `pip install -r requirements.txt`.
4. Run the model training script (`model.py`).
5. Start the Flask server (`app.py`).

## Frontend (React)

### Setup Instructions

1. Clone the repository.
2. Navigate to the `frontend` directory.
3. Install dependencies using `npm install`.
4. Start the React application using `npm start`.

## Deployment

### Backend

The backend is deployed on Render. Follow these steps:

1. Sign up for an account on Render.
2. Create a new Web Service and connect it to your GitHub repository.
3. Set the build and start commands.
4. Deploy the service.

### Frontend

The frontend is deployed on Vercel. Follow these steps:

1. Sign up for an account on Vercel.
2. Create a new project and connect it to your GitHub repository.
3. Set the build and start commands.
4. Deploy the project.

## Usage

- Access the deployed frontend URL.
- Enter a user ID and a movie title to get movie recommendations.
- View the recommended movies and hybrid recommendations based on the user's preferences.

---

This `README.md` provides a high-level overview and the necessary steps to set up, run, and deploy your movie recommendation system.