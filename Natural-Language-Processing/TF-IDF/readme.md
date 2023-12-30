# Term Frequency - Inverse Document Frequency (TF-IDF)
- A widely used statistical method in natural language processing and information retrieval. It measures how important a term is within a document relative to a collection of documents (i.e., relative to a corpus).
- TF-IDF can be performed by following 2 steps :
- Step 1 - Calculating term frequency as
<p align="center">
  <img src="https://github.com/who-deepanshu/Deep-Learning/assets/129099978/852981d8-fd03-479e-85f2-617ab46854f9">
</p>
- Step 2 - Calculating inverse document frequency
<p align="center">
  <img src="https://github.com/who-deepanshu/Deep-Learning/assets/129099978/7e376615-1823-40cb-8c09-dd98cb1e9fa5">
</p>
- Step 3 - Finally, 
<p align="center">
  <img src="https://github.com/who-deepanshu/Deep-Learning/assets/129099978/0c52c363-e667-422f-8cbc-66d80d0ead21">
</p>


# Disadvange :
- TF-IDF assign low values to words that are relatively important, to be overly sensitive on the extensive margin, and to be overly resistant on the intensive margin.
