# docker-eventretrieve
Dockerized web-service providing communication between Sextant and a SPARQL endpoint.

EventRetrieve is used for the BDE SC7 Pilot and provides communication between Sextant and SemaGrow. 

Run the docker: $ docker run -p 9999:8000 bde2020/eventretrieve:1.0.0
Test it using the url: http://localhost:9999/eventDetection/search?keys=Camp
