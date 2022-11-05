# Synthetic-Music-Dataset
Graph Database Project , GTA - 5th Sem


## Introduction to Dataset 
The dataset was synthetically generated using a python script. The generated dataset consists of 7 columns – id, label, name, _start, _end, _type, rating
The data consists of songs from the 1950s, the different genres that they belong to, and around 300 people. There are two relationships between the labels user (people listening to music), genre and track (or song). Users listen to tracks and every track belongs to a genre. There are 7 genres, 300 users and approximately 1000 tracks. There are nearly 5500 relationships in this dataset.
  
    
## Analysis and Inferences  
![image](https://user-images.githubusercontent.com/66276711/200131824-b62282be-d917-46d3-9a74-f82b68f86080.png)  
The above picture shows the popularity of each genre. 1159 users listen to pop music, 864 listen to country as so on. The most popular genres are pop, country and jazz. 
The least listened to genre is hip hop.
![image](https://user-images.githubusercontent.com/66276711/200131842-01a72946-cd3e-43cc-a311-b846630271fe.png)  
The above picture shows the distribution of songs across genre. We can see that pop has highest number of songs followed by country and blues. Hip hop is seen to have least no of songs.


## Conclusion
In this project neo4j has been used to recommend music to users using collaborative and content filtering methods. In content filtering, a user is recommended music based on the genre of songs he listens to. Collaborative filtering on the other hand relies on other users, so users with similar taste will be recommended similar music. It was seen that Harry Mulisch was recommended rock songs like ‘All I want’, ‘repeater’ etc by content filtering because he listened to a rock song (‘While I Wait’). Whereas in collaborative filtering the suggestions were not limited to any one genre and Harry was recommended a variety of songs based on other users with similar taste.   

Various inferences can also be made from this dataset. For example, we were able to find the most popular genre (pop) and the distribution of songs for each genre.
