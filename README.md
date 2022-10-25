# sylph
To run the container run the following commands.

0a. Considering the Flask Application is not built run this command to check if the program runs.

0b. python -m flask --app .\app.py run.

If Flask Application works then use these commands.

1  docker build -t docker-flask .

2  docker run -p 5000:5000 -d docker-flask

3  Then go to your preferred browser and write localhost:5000

4  Congratulations! You containerized your Flask code
