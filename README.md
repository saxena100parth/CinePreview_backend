# CinePreview_backend
This repository contain backend code for movie review application.<br>
-- Link for the frontend repository [click here](https://github.com/saxena100parth/CinePreview-frontend)
## Deployed end-points :
[API End-point (GET) ](https://cinepreviewbackend-production.up.railway.app/api/v1/movies) <br>
- this return all movies with details in json array 
<br>

[API End-point (POST) ](https://cinepreviewbackend-production.up.railway.app/api/v1/reviews) <br>
- you can test POST API with this sample body: <br>
 { <br>
    "reviewBody" : "I am going to watch this movie multiple times.", <br>
    "imdbId" :  "tt3915174" <br>
}
<br>

## what I build and which problem I want to solve.

Being a huge fan of movies, I decided to put my tech skills to good use by crafting a web application that tracks all the flicks I've already indulged in and those that I can't wait to feast my eyes on.

# Tech stack- React.js, SpringBoot & MongoDB.
MongoDB for the database, Java and Spring Boot for the back end, and React for the front end.

# Features
- Ability to watch trailers of all movies that have been added to our collection.
- The capacity to add multiple reviews for future reference.

# Future scope
- In the future, we can implement authentication to allow users to create their own private movie lists, and view the owner of each review.


### Why CinePreview ?
It combines the words "Cinema" (referring to movies) and "Preview" (referring to the trailers), and has a catchy ring to it. The name also implies that users can get a sneak peek at movies trailer and add their thoughts on them through reviews.

### Also used:
Railway - for deploying backend. <br>
GitHub-pages - for deploying frontend. <br>
MongoDB Atlas - for cloud MongoDB database. <br>
Maven - build automation tool. <br>
tmdb.org - a website which provides free to use API for development, I use it for posters of movies. <br>

![CinePreview](https://user-images.githubusercontent.com/87128985/232482614-bf559a1b-165e-448b-ad61-cb10f389eb3a.jpg)
![CinePrevier_review](https://user-images.githubusercontent.com/87128985/232487453-5689cf3d-f8da-482b-9e50-93fe93dfe6a7.jpg)


