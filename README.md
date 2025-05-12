
# 🧠 Weighted Consensus Clustering Ensemble

Welcome! This project explores how to bring multiple clustering algorithms together to form a powerful, **weighted consensus ensemble**. It intelligently chooses the best number of clusters, evaluates performance using silhouette scores, and delivers a final robust clustering using spectral methods.

---

## 🚀 How to Use

1. **Install the required libraries**:
   Make sure Python 3.7+ is installed, then run:

   ```bash
   pip install -U scikit-learn matplotlib seaborn pandas scikit-fuzzy scipy

2. **Prepare your dataset**:

   * By default, the script loads `Wine.csv`.
   * You can replace this with your own dataset in CSV format.

3. **Run the main script**:

   ```bash
   python final_year_project_restructured.py
   ```

4. **View the results**:

   * The script will display plots of different clustering algorithms.
   * It visualizes the consensus matrix as a heatmap.
   * A final clustering plot and comparison table with silhouette scores will appear.

---

## 🔍 Methodology

This project follows a step-by-step ensemble clustering approach:

* 🧹 **Data Preprocessing**: Cleans, encodes, scales, and reduces dimensionality using PCA.
* 🔍 **Finding Optimal `k`**: Uses silhouette scores to choose the best number of clusters.
* 🧪 **Clustering Ensemble**: Applies multiple algorithms – KMeans, GMM, Fuzzy C-Means, Spectral, DBSCAN, and OPTICS.
* ⚖️ **Weighted Consensus**: Builds a consensus matrix by weighting each clustering based on its silhouette score.
* 🌐 **Final Clustering**: Performs spectral clustering on the consensus matrix.
* 📊 **Evaluation**: Displays silhouette scores and visual comparisons.

---

## 📈 Output

Here’s what you’ll get when you run the script:

* 📉 Plot of silhouette scores across different `k` values
* 📌 Visualization of each clustering algorithm’s result (PCA-reduced)
* 🧩 Consensus matrix heatmap with hierarchical clustering
* 🌟 Final clustering result from consensus
* 📋 A score table comparing all algorithms + the consensus method

---

## 📚 References

* [scikit-learn Documentation](https://scikit-learn.org/stable/)
* [scikit-fuzzy (FCM)](https://pythonhosted.org/scikit-fuzzy/)
* [Consensus Clustering](https://en.wikipedia.org/wiki/Cluster_analysis#Ensemble_clustering)

---

## 👨‍💻 Author

Final Year Project – 2025
**Sahil Bera**

If you're working on clustering, machine learning ensembles, or anything in between — I’d love to connect!

---

## 💬 Feedback

Found something useful? Confused about a section?
Feel free to:

* Open an issue
* Suggest improvements via pull requests
* Star the project if you found it helpful ⭐

Your feedback helps make this better for everyone!

---

## To check clustering accuracy use the another notebook as `Weighted_consensus_accuracy` method is same

