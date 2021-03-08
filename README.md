# Beer_Recommendation_System
Student name : Chinh Ho

Instructor Name: Yish Lim

# Applications Used:

Data Science Tools Used:
- Jupyter Notebook
- Pandas
- Requests
- Matplotlib
- Numpy
- Sklearn
- Surprise
- Keras
- LightFM
- GridsearchCV

Websites used:

- https://www.beeradvocate.com/beer/top-styles/

# Data Scraping:

- Total beers scraping were 6000 kind of beer.
- Total raters were 61055 raters.
- Combined beers and raters together by using beer IDs.

# EDA:
- Top 10 raters
![Screen Shot 2021-03-07 at 9 39 20 PM](https://user-images.githubusercontent.com/72099238/110278218-733dfc80-7f9c-11eb-928d-05485f3d3906.png)
- Top 10 beers
![Screen Shot 2021-03-07 at 9 38 38 PM](https://user-images.githubusercontent.com/72099238/110278228-79cc7400-7f9c-11eb-978d-0ee08ffb7bf0.png)
- Most ratings were 3.4-3.8
![Screen Shot 2021-03-07 at 9 39 39 PM](https://user-images.githubusercontent.com/72099238/110278320-a7b1b880-7f9c-11eb-9b20-1b8cff4bbb6f.png)
-ABV
![Screen Shot 2021-03-07 at 9 39 53 PM](https://user-images.githubusercontent.com/72099238/110278327-a97b7c00-7f9c-11eb-899a-22b3c51115f0.png)

# Surprise Library:
- Simple Prediction
![Screen Shot 2021-03-07 at 10 36 18 PM](https://user-images.githubusercontent.com/72099238/110278450-e2b3ec00-7f9c-11eb-9be3-9525ab810073.png)
- Item to Item prediction
![Screen Shot 2021-03-07 at 10 37 40 PM](https://user-images.githubusercontent.com/72099238/110278464-e9426380-7f9c-11eb-8b15-2a2230eeea47.png)

# Neural network

![Screen Shot 2021-03-07 at 10 41 03 PM](https://user-images.githubusercontent.com/72099238/110278538-0d05a980-7f9d-11eb-8725-ec44ea4f525a.png)

# LightFM

- Pure Collaborative Filtering : only fit user id and beer id to model.
- Hybrid model: beside user id and beer id, also fit item feature and user feature. 
- Pure Collaborative Filtering performed better with AUC: 0.75
![Screen Shot 2021-03-07 at 10 53 19 PM](https://user-images.githubusercontent.com/72099238/110278609-29a1e180-7f9d-11eb-82fe-f02b6f505834.png)

# Conclusion:

- Depends on situations, company can use my models to predict whether item to item with KNNBaseline or Collaborative Filtering with Neural Network.
- Cold start problem also solved with LightFm.

# Future Work:

- Try to optimize LightFM and Neural network using GridSearchCV or Talos.
- Scrape description of beers to predict beer base on content base.





