# Ecommerce_website

This project is a FastAPI application for managing e-commerce products, with a PostgreSQL database and Docker integration.

## Docker Instructions

To build, push, pull, and run the Docker image, use the following commands:

docker build -t mokshsenkusha/ecommerce_website:v1.0.0 --build-arg APP_NAME="EcommerceApp" .
docker push mokshsenkusha/ecommerce_website:v1.0.0
docker pull mokshsenkusha/ecommerce_website:v1.0.0
docker run -p 8000:8000 mokshsenkusha/ecommerce_website:v1.0.0
