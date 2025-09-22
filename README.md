<h1>PCA Implementation and Analysis</h1>
<p>This repository contains a Jupyter notebook that demonstrates the application and implementation of <strong>Principal Component Analysis (PCA)</strong>. The project uses <code>scikit-learn</code> for a practical application of the algorithm and then re-implements a simplified version from scratch using <code>NumPy</code> to deepen understanding of how it works.</p>
<hr>
<h2>Key Concepts Covered</h2>
<ul>
    <li><strong>Dimensionality Reduction:</strong> Reducing the number of variables in a dataset while retaining most of the information.</li>
    <li><strong>Principal Component Analysis (PCA):</strong> A classic algorithm for dimensionality reduction that identifies the directions (principal components) of maximum variance in the data.</li>
    <li><strong>Explained Variance Ratio:</strong> A metric that indicates how much of the dataset's variance is captured by each principal component.</li>
    <li><strong>Data Visualization:</strong> Plotting multi-dimensional data in a 2D space to uncover patterns.</li>
</ul>
<hr>
<h2>Project Structure</h2>
<p>The core of this project is the Jupyter notebook, which is divided into two main tasks:</p>
<ul>
    <li><strong>Task 1: Using Scikit-Learn's PCA:</strong> This section demonstrates how to use <code>scikit-learn</code> to perform PCA on a given dataset. It explores key attributes of the fitted model, such as the <code>explained_variance_ratio_</code> and <code>components_</code>.</li>
    <li><strong>Task 2: Implementing PCA from Scratch:</strong> This section builds on the concepts from Task 1 by implementing the PCA algorithm using only the <code>NumPy</code> library. This serves as a great way to understand the underlying mathematics of the algorithm, including calculations of the covariance matrix, eigenvectors, and eigenvalues.</li>
</ul>
<hr>
<h2>Getting Started</h2>
<h3>Prerequisites</h3>
<p>To run this notebook, you'll need a Python environment with the following libraries:</p>
<ul>
    <li><code>pandas</code></li>
    <li><code>numpy</code></li>
    <li><code>matplotlib</code></li>
    <li><code>scikit-learn</code></li>
</ul>
<p>You can install them using <code>pip</code>:</p>
<pre><code>pip install pandas numpy matplotlib scikit-learn</code></pre>
<h3>Running the Notebook</h3>
<ol>
    <li><strong>Clone the repository</strong> to your local machine:
    <pre><code>git clone https://github.com/your-username/your-repository.git</code></pre>
    </li>
    <li><strong>Navigate to the project directory</strong>:
    <pre><code>cd your-repository</code></pre>
    </li>
    <li><strong>Launch Jupyter Notebook</strong>:
    <pre><code>jupyter notebook</code></pre>
    </li>
    <li><strong>Open the <code>[notebook-name].ipynb</code> file</strong> to view and run the code.</li>
</ol>
<hr>
<h2>Dataset</h2>
<p>The project uses a simple dataset named <code>data.csv</code>, which contains 999 samples with 5 features (<code>xi1</code> to <code>xi5</code>). The structure of this data is designed to showcase how PCA can effectively identify and reduce redundant features.</p>
