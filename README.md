# Cybercommons

## What?
Cybercommons is a web application that allow for storage of catalogs and other types of data onto a database. Our sponsor, Tyler Pearson, essentially describes Cybercommons as a Django REST framework API. Visit the Repo here -> https://github.com/cybercommons

## Technologies Used
Cybercommons makes use of many different technologies to get it running. For starters, the application uses Docker and Docker-Compose to built and run quickly on one's own local machine. Docker makes it easy to build the application without the issue of "well it works on my machine." The two languages used in Cybercommons are JavaScript and Python3. Django is another technology used for easy Python Web Development. MongoDB is an important technology used concerning with the storage of catalogs and data. All data stored in Cybercommons is stored as a JSON document format. Celery and RabbitMQ helps with messaging passing and constantly looking for new work to perform in Cybercommons to keep it running smoothly.

## Tasks Assigned
Our sponsor, Typer Pearson, had a good working system. He wanted us to add additional features to the application such as:
1) SSL Creation - current config with preset SSL.
2) NGINX Config
3) JWT Pay-Load
4) Integration with Kubernetes
