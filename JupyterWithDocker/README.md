Step 1: Download all the files to a directory on you computer 

Step 2: Install Docker on your computer 

Step 3: In the project directory type 

	docker build -t datascience . 

Step 4: In the project directory type 

	docker-compose up 

Step 5: Visit http://localhost:8888 on you web browser 

To add python scipts to the container simply add it in the project folder and mount it in docker-compose.yml file 
Then type docker-compose up again 
 