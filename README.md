# e-commerce-analysis
This repo contains the code and the instructions to analise data - the csv file ***sample.csv*** - using Docker, PySpark, MongoDB Compass and Grafana.
\
\
Make sure to have installed **Docker Desktop**, **MongoDB Compass** on your PC.

## First Step
Download the docker compose file. Put it in a folder. Then, open your CMD shell and set the working directory in this folder in this way:

- *cd Desktop/YourFolderName*

Now, run the command:

- *docker-compose up*


## Second Step
Once the process in your shell has completed, check your Docker Containers section, you should see three cointainers running on different ports, one container for PySpark, one for MongoDB Compass and one for Grafana.
\
Open the shell ('exec') in the Grafana Container and run the command:

- *npm run server*

This will be necessary to connect Grafana to MongoDB Compass.


## Third Step
Now, you'ready to open PySpark and start your analysis on the file 'sample.csv'
