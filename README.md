# Unit 13 Homework Assignment - The Power of the Cloud and Unsupervised Learning

## Background

It is time to take what you have learned about unsupervised learning and the AWS services and apply it to new situations. For this assignment, you will need to complete **one of two** (not both) challenges. Which challenge you take on is your choice. Just be sure to give it your all -- as the skills you hone will become powerful tools in your FinTech tool belt.

### Before You Begin

1. Create a new repository for this project called `unit13-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Inside your local git repository, create a directory for the challenge assignment you choose. Use folder names corresponding to the challenges: **RoboAdvisor** or  **ClusteringCrypto**.

4. Add your solution files to this folder.

5. Push the above changes to GitHub or GitLab.


<summary>Option 2: Clustering Crypto</summary>

#### Data Preprocessed  (18 points)

##### To receive all points, your code must:

* Load the data into a Pandas DataFrame named `crypto_df`. (9 points)
* Complete all assigned data preprocessing tasks. (9 points)

#### Data Dimension Reduced  (12 points)

##### To receive all points, your code must:

* Use the PCA algorithm from sklearn to reduce dimensions. (7 points)
* Create a DataFrame named `pcs_df` using `crypto_df.index` as the index. (5 points)

#### Cryptocurrency Clustered  (25 points)

##### To receive all points, your code must:

* Use K-Means to cluster the cryptocurrencies using PCA data. (7 points)
* Use the Elbow Curve with the `pcs_df` DataFrame to find the best value for k. (7 points)
* Use the Kmeans algorithm to predict the k clusters for the cryptocurrency data. (7 points)
* Create a new DataFrame named `clustered_df` that includes the assigned columns and index. (4 points)

#### Visualizing Results  (15 points)

##### To receive all points, your code must:

* Using Plotly and the `clustered_df` DataFrame, create a 3D-Scatter plot with the assigned paramaters. (5 points)
* Create a Data table with the assigned columns using hvplot.table for all current tradable cryptocurrencies. (5 points)
* Create a scatter plot using hvplot.scatter that presents the clustered data using the assigned parameters. (5 points)

#### Optional Bonus: AWS Sagemaker Deployment (20 points)

##### To receive all points, your code must:

* Optional: Upload and deploy the Jupyter notebook using Amazon SageMaker. (20 points)

#### Coding Conventions and Formatting (10 points)

##### To receive all points, your code must:

* Place imports at the beginning of the file, just after any module comments and docstrings and before module globals and constants. (3 points)
* Name functions and variables with lowercase characters and with words separated by underscores. (2 points)
* Follow Don't Repeat Yourself (DRY) principles by creating maintainable and reusable code. (3 points)
* Use concise logic and creative engineering where possible. (2 points)

#### Deployment and Submission (10 points)

##### To receive all points, you must:

* Submit a link to a GitHub repository that’s cloned to your local machine and contains your files. (5 points)
* Include appropriate commit messages in your files. (5 points)

#### Code Comments (10 points)

##### To receive all points, your code must:

* Be well commented with concise, relevant notes that other developers can understand. (10 points)

</details>

---

© 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
