# Dockerized GIS Earthquake Web App
Cloud-Deployed Web Application for Earthquake Likelihood Prediction
This repository contains the source code for a web application that visualizes historical earthquake data and provides a likelihood prediction of an earthquake at a user-specified location, based on the proximity to past seismic events. A core aspect of this project was its full Dockerization and cloud deployment to an AWS EC2 instance, making it accessible via a custom URL.

## 💡 Project Overview
This web application leverages Geographic Information Systems (GIS) to present a dynamic map interface. Users can explore a database of historical earthquakes, and, more importantly, interact with the map to pin a specific location. Upon pinning, the application calculates and displays the likelihood of an earthquake occurring at that spot, primarily determined by its distance from known past earthquake events in the database.

The project highlights robust cloud deployment practices, demonstrating the ability to containerize a complex web application using Docker and deploy it to a scalable AWS EC2 instance, accessible through a custom domain. This entire setup ensures a highly available and easily manageable application environment.

## ✨ Features
Interactive Earthquake Map: Visualize historical earthquake data plotted on a geographical map.

Location-Based Likelihood Prediction: Click anywhere on the map to determine the likelihood of an earthquake at that pinned location, calculated by its proximity to recorded past earthquakes.

Dynamic Data Display: View details of individual earthquakes upon interaction.

Dockerized Deployment: The entire application stack (Django, database, GIS components) is containerized using Docker.

Cloud Hosting: Deployed and accessible via an AWS EC2 instance.

Custom URL Accessibility: Configured for access through a custom domain, showcasing real-world deployment capabilities.

## 🛠️ Technologies Used
Web Framework: Django

Geographic Information System (GIS): Used for map visualization and spatial data processing.

Containerization: Docker

Cloud Platform: Amazon Web Services (AWS) - specifically EC2 for hosting.

Database: PostgreSQL with PostGIS

Deployment: Custom URL configuration.

## 🚀 Getting Started (Deployment & Local Setup)
This project is designed for cloud deployment, but can also be run locally using Docker.

## Prerequisites:
Docker and Docker Compose installed on your machine.

An AWS account with EC2 access (for cloud deployment).

Familiarity with Django and GIS concepts is beneficial.

## Cloud Deployment to AWS EC2:
The most significant learning from this project was the end-to-end deployment to AWS EC2.

🤝 Contributing
This project was developed as a personal learning endeavor. While not actively seeking external contributions, feel free to fork the repository, experiment, and adapt it for your own purposes.
