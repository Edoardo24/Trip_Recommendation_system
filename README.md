# Trip_Recommendation_system
The project is to create a trip recommendation system that can guide the customer from the first stages of vacation planification to the last stages. Everyone has the problem, of first of all, identifying where to go on vacation and then which hotel to book. Therefore, the goal of this project is to suggest which destination to choose based on the choice of users like the one to whom the destination needs to be suggested. Once the place is identified with the help of user reviews and thanks to the preferences entered by the user, it will be possible to recommend a list of hotels that best suit the consumer.

For the recommendation of destinations, a dataset was taken that takes into analysis thousands of itineraries within Brazil. In this way it was possible to identify what type of traveler and for what purpose they travel in order to best suggest the destination to choose. The destination was the one that was mostly chosen by users who were in the same cluster as the user. ![Destination_results](https://github.com/Edoardo24/Trip_Recommendation_system/assets/46709461/118d17ed-fb1d-4be3-bb32-1558f2947977)

This was made possible using the KMean method and dimensionality reduction systems to visualize the dataset. Given the need to identify the optimal number of clusters, the combination of Elbow and Silhouette method was used.
![T_SNE](https://github.com/Edoardo24/Trip_Recommendation_system/assets/46709461/9c712e93-8180-4d5e-b858-615278a937f5)


In terms of hotel recommendation, inputs that the user will enter as different available tags (which will help identify the type of travel) and then the previously found destination were used. Based on user reviews and based on advertising plans, it was possible to compile a list of which hotels come closest to the user's needs.

![KMeans](https://github.com/Edoardo24/Trip_Recommendation_system/assets/46709461/35b09302-1990-4132-aae2-d9bfb1b86389)


## Author
Edoardo Berardi Vittur
Ali Yassine
Ethan Greene
