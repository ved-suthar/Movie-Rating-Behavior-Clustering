# Movie-Rating-Behavior-Clustering
This project analyzes user rating behavior using the MovieLens dataset.  The goal of this project is to group users based on how they rate movies using Unsupervised Machine Learning (KMeans Clustering).  I used around 20,000 movie rating records for this analysis.

📂 Dataset
Dataset Used: MovieLens Dataset
Data Used: ratings.csv (sampled 20,000 records)

Each record contains:
userId
movieId
rating
timestamp

⚙️ Project Steps
1️⃣ Data Loading
Loaded CSV files using Pandas.

2️⃣ Data Sampling
Randomly selected 20,000 rating records for analysis.

3️⃣ Feature Engineering
Grouped data by userId and created user-level features:
Total ratings given
Average rating
Rating standard deviation
Minimum rating
Maximum rating
This helped convert raw rating data into user behavior data.

4️⃣ Data Scaling
Used StandardScaler to normalize the features before clustering.

5️⃣ Finding Optimal Clusters
Used the Elbow Method (WCSS) to find the best number of clusters.

Optimal number of clusters selected: 4

6️⃣ KMeans Clustering
Applied KMeans algorithm with 4 clusters to group users.

7️⃣ PCA Visualization
Used PCA (Principal Component Analysis) to reduce dimensions to 2 components for visualization.
This helped in visualizing user clusters in 2D space.

📊 Results
The model divided users into 4 groups:
High rating users
Low rating users
Moderate rating users
Highly active users

🛠 Tools & Technologies Used

Python
Pandas
NumPy
Matplotlib
Scikit-Learn
KMeans
PCA

💡 Business Use Case

This type of clustering can help in:
Improving recommendation systems
Understanding customer behavior
Personalized marketing
Content targeting

🚀 What I Learned
Through this project, I improved my understanding of:
Feature Engineering
Data Scaling
Elbow Method
KMeans Clustering
PCA for visualization

IMAGES:
<img width="1186" height="801" alt="Screenshot 2026-02-18 185808" src="https://github.com/user-attachments/assets/e3cb5c14-3158-402e-9511-4e3110eb7505" />
<img width="1486" height="345" alt="Screenshot 2026-02-18 185748" src="https://github.com/user-attachments/assets/b8bb561f-2554-49f3-934c-546d01570dd6" />
<img width="1052" height="375" alt="Screenshot 2026-02-18 184859" src="https://github.com/user-attachments/assets/b81e2cf8-9b05-486a-a621-cbf73623cc67" />
<img width="1489" height="772" alt="Screenshot 2026-02-18 184845" src="https://github.com/user-attachments/assets/8b3ccd96-6ccd-48da-932e-e60356564d46" />
<img width="1644" height="219" alt="Screenshot 2026-02-18 184829" src="https://github.com/user-attachments/assets/2edacb25-ad9e-4aed-be94-69d24d709192" />
<img width="1640" height="764" alt="Screenshot 2026-02-18 184814" src="https://github.com/user-attachments/assets/717c69aa-ea27-4e57-b871-ac0c7c84e296" />
<img width="1639" height="694" alt="Screenshot 2026-02-18 184800" src="https://github.com/user-attachments/assets/b8646b3d-3539-417c-8504-34049da435af" />
<img width="1640" height="759" alt="Screenshot 2026-02-18 184744" src="https://github.com/user-attachments/assets/930d7e60-ce62-49ee-9501-a7727faedf7c" />
