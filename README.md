Reference from geeks for geeks : https://www.geeksforgeeks.org/restaurant-recommendation-app-using-mean/

MEAN STACK  --> Mongo Express Angular Node.js


### Approach

The project will be divided into two main parts:

Client-side: The client-side will be built using Angular, a popular JavaScript framework for building web applications. We'll create the necessary components, services, and routing to handle the user interface and interact with the server-side.

Server-side: The server-side will be built using Node.js and Express, a web application framework for Node.js. We'll create the API endpoints, handle database operations using Mongoose, and manage Cross-Origin Resource Sharing (CORS) policies.


## CI/CD Readme:

1. This Repo has both jenkins CI Pipeline and Gitlab CI Pipeline. If you are using `jenkins` then please read the `jenkins_file_Readme.md`, if you are using `Gitlab` then please read the `gitlab_readme.md`.

2. For CD part we will be using `ArgoCD`. Please Read `ArgoCD_readme.md` for CD. We are going to deploy our application in `Eks Cluster`.