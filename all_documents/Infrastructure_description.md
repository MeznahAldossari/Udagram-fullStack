
![Untitled Diagram drawio (1)](https://user-images.githubusercontent.com/97708390/209306298-c6649b1e-840c-4624-809b-6e0c35ca4547.png)


## AWS Description

1- User<br>
the user deals with frontend part through visiting app link <br>

2- S3 Bucket <br>
It is used for frontend part. The app uses this service for displaying the content of page through deploying the frontend to this server.<br>

3- RDS: <br>
It used for database part. The app uses this service for storing the data.<br>

4- Elastic Beanstalk (EB) <br>
It used for backend part. The app deployed the backend into this service. <br>

### URL

The URL of each service is listed below <br>
1- S3 URL: <br>
http://udagram1200m.s3-website-us-east-1.amazonaws.com/ <br>

2- RDS URL: <br>
postgres://postgres:postgres@database-1.cp1zhiszjvxa.us-east-1.rds.amazonaws.com:5432/postgres <br>

3- EB URL: <br>
http://udagramsapp-env.eba-sukewzx8.us-east-1.elasticbeanstalk.com/ <br>
