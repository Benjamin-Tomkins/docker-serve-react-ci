How to use 
===========

From the commad line `docker build -t <username>/mismocodes:latest .`  
Once completed `docker push <username>/mismocodes:latest`   
To run the project `docker run -it -d --rm -p 80:5000 <username>/mismocodes`  
Go to `localhost` in your browser to view the project  

To stop running the project  
Type `docker ps`  
Copy the `<CONTAINER ID>`  
Type `docker stop <CONTAINER ID>`  
