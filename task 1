import pandas as pd
import matplotlib.pyplot as plt

# Step 1: Load the dataset
data = pd.read_csv('/content/student_data (1).csv')

# Step 2: Generate Bar Chart for Gender Distribution
gender_counts = data['gender'].value_counts()

plt.figure(figsize=(8, 5))
plt.bar(gender_counts.index, gender_counts.values, color=['pink', 'purple'])
plt.title('Gender Distribution')
plt.xlabel('Gender')
plt.ylabel('Count')
plt.show()

# Step 3: Generate Histogram for Age Distribution
plt.figure(figsize=(8, 5))
plt.hist(data['age'], bins=8, color='skyblue', edgecolor='black')
plt.title('Age Distribution')
plt.xlabel('Age')
plt.ylabel('Frequency')
plt.show()
