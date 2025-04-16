# **Movie Recommendation System**

### **Description**:
This repository contains a movie recommendation system that uses collaborative filtering techniques (user-based and item-based) and a Pixie-inspired random walk approach. The system is built using the **MovieLens 100K dataset** and provides personalized movie recommendations.

### **Features**:
- **User-based collaborative filtering**: Recommends movies based on similar users' ratings.
- **Item-based collaborative filtering**: Recommends movies based on similar movie ratings.
- **Pixie-inspired random walk algorithm**: Uses graph-based random walks to discover hidden relationships between users and movies.

### **Dataset**:
- The **MovieLens 100K dataset** is used, which includes **100,000 ratings** from **943 users** on **1,682 movies**.
- The dataset has been preprocessed and includes the following files:
  - `users.csv`: Contains user data.
  - `movies.csv`: Contains movie information (movie_id and title).
  - `ratings.csv`: Contains ratings provided by users for the movies.

### **Files**:
- **Movie_Recommendation.ipynb**: The Jupyter Notebook that contains the code for the recommendation system, including data preprocessing, collaborative filtering, and random walk algorithms.
- **users.csv**, **movies.csv**, **ratings.csv**: The CSV files that were used in the system, containing user data, movie data, and ratings, respectively.
- **Pixie_Algorithm_Explanation.pdf**: A detailed explanation of the Pixie-inspired random walk algorithm used in the system.
- **Recommendation_Report.pdf**: A report discussing the methods, results, and evaluation of the recommendation system.

### **How to Use**:
1. Clone this repository to your local machine.
2. Open `Movie_Recommendation.ipynb` in Jupyter Notebook.
3. Run the cells to preprocess the data and generate recommendations.
