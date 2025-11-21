---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Regression, Sklearn"

project:
  title: "Custom Clothing Size Measurement Model"
  type: "Machine Learning Project"
  url: "https://github.com/dixitmanav/clothing-size-measurement-recommendation-model"
  logo: "assets/images/projects/clothing_recommender/clothing_rec.jpeg"
  tech: "Scipy, Sklearn, SVM"

---
<p class="h3" style="color: #7a995d">TLDR: </p>
<p>
Have you ever been baffled that the same size across different brands leads to vastly different fits? This project builds a pipeline that uses a TF-IDF vectorizer based on customer reviews to customize product fit per person. A finall write up is available <a href="/assets/images/projects/clothing_recommender/FinalWriteUp.pdf">here</a>.
</p>

<p class="h2">Analysis:</p>
<p class="textp">We describe a method to determine whether a customer received a correctly fitting product. To help us achieve this, we use the RentTheRunway dataset and build a pipeline involving a <span style="color: #a9c191">TF-IDF vectorizer</span> and 3 different classifiers to determine which gave us results most similar to those that we were given in the dataset. </p> 
<p class="textp">Through using TF-IDF alongside <span style="color: #a9c191">Support Vector Classification</span>, <span style="color: #a9c191">Bagging Classification</span>, and <span style="color: #a9c191">KNeighbors Classification</span> models, we concluded that the Linear Support Vector Classification yielded the best results, therefore, is our most accurate model. By creating such a model that generates a classification output on whether or not a specific product fits or not, we would be able to take a step further in ensuring great customer services through the E-commerce market.</p>
