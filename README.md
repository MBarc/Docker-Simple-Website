# Docker-Simple-Website
Just add your html, start up the container, and voila.


Note: This custom nginx container is designed to hold an html-only website. 

Step 1: Download this repository.
Step 2: Add your html (the html could include css and js) to the html directory.
Step 3: In your local terminal, navigate to the directory that contains the Dockerfile. 
Step 4: Build the docker image.
> docker build -t simplewebsiteimage
Step 5: Run the docker container.
> docker run -dt -p 80:80 --name website simplewebsiteimage
