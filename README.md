# Supervised landcover classification
Comparison of 2 supervised models for Land cover use classification from Sentinel 2 imagery over Corse region. 
- ee.Classifier.smileRandomForest() - An ensemble learning method that builds multiple decision trees and aggregates their predictions through majority voting.
- ee.Classifier.libsvm() - Support Vector Machine (SVM) using LIBSVM library : A powerful supervised learning algorithm that finds the optimal hyperplane to separate different classes in a high-dimensional feature space. It can use various kernel functions (e.g., linear, radial basis function (RBF), polynomial) to handle non-linear relationships.

In many geospatial land cover classification studies, Random Forest has become a popular and often highly effective choice due to its balance of accuracy, efficiency, and ease of use. 
However, SVM can also be a strong contender, especially when dealing with complex spectral signatures and with careful parameter optimization.

Core techs skills:
Platform: Google Earth Engine (GEE)
Imagery Data: Sentinel-2
Primary Programming Language: Python 
Python : geemap, ee
Development Environment: google colab

## Results:

In this example, model evaluation has shows that the Random Forest model provides the best perfomance of 73% over SVM (66%).


  <table style="border-collapse: collapse;">
  <tr>
    <td><img src="https://github.com/fadodo/Supervised_landcover_classification/blob/main/Capture%20d%E2%80%99%C3%A9cran%20du%202025-04-15%2016-48-17.png" width="300"></td>
    <td><img src="https://github.com/fadodo/Supervised_landcover_classification/blob/main/Capture%20d%E2%80%99%C3%A9cran%20du%202025-04-15%2016-49-47.png" width="300"></td>
    <td><img src="https://github.com/fadodo/Supervised_landcover_classification/blob/main/Capture%20d%E2%80%99%C3%A9cran%20du%202025-04-15%2016-51-06.png" width="300"></td>
  </tr>
</table>
