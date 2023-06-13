<p align="center"> 
  <img src="" alt="Netflix" width="200px" height="200px">
</p>
<h1 align="center"> Netflix Recommendation </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://certificates.almabetter.com/en/verify/24284787996614"> AlmaBetter Certificate </a> </h5>

<p align="center"> 
<img src="" alt="" height="382px">
</p>

Conducted EDA on Netflix Movie/TV Shows data, revealing content trends across regions, and developed a recommendation model leveraging textual features for personalized suggestions.


# :floppy_disk: Project Files:
This project contains three directories, one model as follows:
<ul>
 <li><b> notebooks: </b> This Folder contains .ipynb for the project</li>
 
 <li><b> data: </b> This folder contains</li>
 <t>a. data.csv : The raw data.</t><br>
 <t>b. intermediate.csv : The data processed to gain insights and performing EDA.</t><br>
 <t>c. final_data.csv : The data used for modelling purposes.</t>
  <li><b> reports: </b> This contains the powerpoint presentation related to the project. 
<li><b> model: </b> The model is joblib file of model. </li>
 </ul>
 
<h2> :book: Spectral Clustering</h2>

Spectral Clustering is a popular clustering algorithm that leverages the spectral properties of data to group similar data points together. It works by transforming the data into a lower-dimensional space using spectral techniques and then applying a traditional clustering algorithm on the transformed data.

In spectral clustering, we construct a similarity matrix that measures the pairwise similarities between data points. This matrix captures the relationships between the data points based on some similarity metric (e.g., Euclidean distance or Gaussian kernel). Next, we compute the eigenvalues and eigenvectors of the similarity matrix. The eigenvectors corresponding to the smallest eigenvalues are used to form a new representation of the data, often called the spectral embedding.

The spectral embedding effectively reduces the dimensionality of the data while preserving the underlying structure and capturing clusters or groups within the data. Finally, a clustering algorithm (e.g., k-means) is applied on the spectral embedding to assign data points to clusters.

Spectral clustering offers several advantages. It can handle complex and nonlinear data structures and is not limited to spherical or convex clusters. It also allows us to uncover clusters of varying sizes and shapes. Additionally, by using the spectral embedding, it can separate clusters that are intertwined or overlapping.

In summary, Spectral Clustering is a powerful algorithm that combines spectral techniques with traditional clustering methods to identify meaningful patterns and groups within data. It is particularly useful when dealing with complex data structures and non-convex clusters.

<h2> :books: References</h2>
<ul>
	<li> Google: www.google.com</li>
	<li> GeeksForGeeks: https://www.geeksforgeeks.org/ml-spectral-clustering/</li>
    <li> Analytics Vidhya: https://www.analyticsvidhya.com/blog/2021/05/what-why-and-how-of-spectral-clustering/</li>
    </ul>