# Video-Recommendation-System
Data Collection:

Video Data:
Use the provided API endpoint https://api.socialverseapp.com/feed?page=1 to fetch video data.
Implement pagination to retrieve more data if needed. You can use fields such as title, comments, rating, view counts, share counts, inspiration score, inspired user count, and category for building your recommendation model.
User Data:
Create a dummy dataset for users. The dataset should include fields like watch history, language, and location.
Data Preprocessing:

Clean and preprocess both video and user data.
Convert categorical fields such as category, language, etc., into numerical representations (e.g., using one-hot encoding).
Normalize numerical fields like view counts, share counts, etc.
Feature Engineering:

Create meaningful features for the recommendation algorithm. For instance, you could aggregate user watch history to determine preferences in categories or languages.
Consider combining various fields to create composite features that might improve the recommendation's accuracy.
Model Selection:

Choose a recommendation algorithm. You can start with collaborative filtering, content-based filtering, or a hybrid approach.
Implement and train your model using the dummy user data and fetched video data.
Recommendation Engine:

Once your model is trained, implement the recommendation logic.
For each user in your dummy dataset, generate a list of recommended videos.
Testing & Validation:

Test the recommendations on the dummy user dataset to evaluate the algorithm’s performance.
