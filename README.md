# Image Classification on Webtoon Thumbnails Using CNN/RNN Architecture and Image Search Using Locality Sensitive Hashing
<p>
  <a><img src="https://img.shields.io/badge/CSCI 6380-Data Mining-F3BF1E?style=for-the-badge"/></a>
  <a href="https://github.com/JP1128/Webtoon-Thumbnail-Classification/blob/main/CSCI_6380_Final_Report.pdf"><img src="https://img.shields.io/badge/LINK TO PAPER-0077b5?&style=for-the-badge"/></a>&nbsp;
</p>

Authors: **Jae Park (JP)**

## Abstract
We created CNN and RNN models to classify Webtoon thumbnails into the respective artist and genre. We then used image embedding and locality sensitive hashing to simulate similar image search. The classifier for the artist was not able to generalize beyond the training set; however, the genre classifier and the similar image search showed promising result.

## CNN/RNN Architecture
### Author 

#### CNN/RNN Model
![](images/author_model.png?raw=true)

#### Result
![](images/author_output.png?raw=true)

### Genre

#### CNN/RNN Model
![](images/genre_model.png?raw=true)

#### Result
![](images/genre_output.png?raw=true)

## Image Similarity

### Result 1
![](images/img_sim1.png?raw=true)

### Result 2
![](images/img_sim2.png?raw=true)
