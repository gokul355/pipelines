# pipelines
This repository contains multiple pipeline file of different use cases


jenkinsfilefrontend => 
1. This pipeline builds an angular application and sync it to s3 bucket. 
2. Then it will update the cdn origin.
3. please note that the instance which your instance is running should necessary I am attached to it.


jenkinsfilebackend
1. This pipeline build the docker images for each container the context of the docker contianer is   mentioned in root folder array
2. Please note that , all the three arrays should have elements respective order .
3. Please change the ecr url and other details