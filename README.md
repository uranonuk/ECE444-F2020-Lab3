# Lab 4
# To build:
    docker build -t docker-sample:latest .
# To run:
    docker run -d -p 5000:5000 docker-sample
# Notes:
    I used the https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial as my guide for Lab3, therefore it looks different from the example produced in the book. I used my Lab3 website, and deployed it in Docker
   
# Directory
lab3.py is the main application.
routes are in app/routes.py
templates are in app/templates
whole project is in ECE444-F2020-Lab3

# Screenshots
Screenshot of my terminal outputs, browser, and docker is under ECE444-F2020-Lab3.

# Answer to 3)
Docker consists of many running processes, which are called containers. A container shares the kernel of the host machine that the container is running on, whereas a VM runs on a separate kernel with virtual access to resorces of the host machine. This is why Docker offers a lightweight alternative to VM memory-wise. 
