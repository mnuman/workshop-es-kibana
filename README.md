# ElasticSearch/Kibana Workshop
Source: https://github.com/LisaHJung/Beginners-Crash-Course-to-Elastic-Stack-Series-Table-of-Contents

Spin up the cluster (three ES nodes, one Kibana node) in detached mode using: `docker compose up --detach` ).

## Connect
The ElasticSearch cluster is running on port 9200, Kibana node is running on 5601. The password for the elastic user is configured in the .env file (default elastic).

## Dataset
- Download the news dataset from https://www.kaggle.com/datasets/rmisra/news-category-dataset
- E-commerce dataset from https://www.kaggle.com/datasets/carrie1/ecommerce-data

For importing the e-commerce dataset, I felt that bumping the memory limit to some 4GB was necessary. The default memory limit of 1GB would not allow the file to be analyzed before import. Probably also other ways around this.



