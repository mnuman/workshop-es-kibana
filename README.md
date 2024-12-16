# ElasticSearch/Kibana Workshop
Source: https://github.com/LisaHJung/Beginners-Crash-Course-to-Elastic-Stack-Series-Table-of-Contents

Spin up the cluster (three ES nodes, one Kibana node) in detached mode using: `docker compose up --detach` ).

## Connect
The ElasticSearch cluster is running on port 9200, Kibana node is running on 5601. The password for the elastic user is configured in the .env file (default elastic).

## Dataset
- Download the news dataset from https://www.kaggle.com/datasets/rmisra/news-category-dataset
- E-commerce dataset from https://www.kaggle.com/datasets/carrie1/ecommerce-data

Removed memory limits for leader node of Elastic and Kibana to prevent OOM.



