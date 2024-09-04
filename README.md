# Recommender Engine

A recommender engine based on data obtained by Steam Australia. It uses collaborative filtering using ALS (Alternating Least Squares) to obtain top recommendations of items to users and item-to-item similarities. This is done using Implicit feedback data. The item-to-item similarities are obtained using cosine similarity between their factors in the model.

This recommender engine can be used for bootstrapping a game blog with personalized content, as the users have come to expect personalized recommendation after the advent of Facebook, Google and Netflix.

## Sources
Data: <br>
Apurva Pathak, Kshitiz Gupta, Julian McAuley Generating and Personalizing Bundle Recommendations on Steam. SIGIR, 2017.
Wang-Cheng Kang, Julian McAuley Self-attentive sequential recommendation. ICDM, 2018. <br>
Apurva Pathak, Kshitiz Gupta, Julian McAuley Item recommendation on monotonic behavior chains. RecSys, 2018. <br> <br>
Useful links: <br>
https://towardsdatascience.com/building-a-recommendation-system-with-spark-ml-and-elasticsearch-abbd0fb59454
https://towardsdatascience.com/prototyping-a-recommender-system-step-by-step-part-2-alternating-least-square-als-matrix-4a76c58714a1



## Roadmap
TODO: add model export and implementation using elastic search

## License
MIT License

## Project status
Active

