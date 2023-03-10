# Week 1 — App Containerization

### Containerize Application (Dockerfiles, Docker Compose)

I was able to containerize the cruddur app by firstly creating a dockerfile for each of the backend and frontend apps and the created a docker-compose file for the app as a whole

> The frontend Dockerfile
![The frontend Dockerfile](assets/week-1/frontendApp-Dockerfile-wk1.png)

> The backend Dockerfile
![The backend Dockerfile](assets/week-1/backendApp-Dockerfile-wk1.png)

> The Docker-compose file and proof it's running
![The Docker-compose file and proof it's running](assets/week-1/docker-compose-runnung-wk1.png)

> The Docker-compose file and proof of ports it's running on
![The Docker-compose file and proof of ports it's running on](assets/week-1/docker-compose-runnung-ports-wk1.png)

> Proof that both the backend and frontend app runs after running docker-compose up command
![Proof that both the backend and frontend app runs after running docker-compose up command](assets/week-1/App-runs-wk1.png)


### Write a Flask Backend Endpoint for Notifications
following the instruction on the video, I was able to successfully write the notification flask backend endpoint

> Notification open api endpoint
![Notification open api endpoint](assets/week-1/notification-endpoint-wk1.png)

> Notification flask route definition
![Notification flask route definition](assets/week-1/notification_route_and_activities-wk1.png)

> Proof that the Notification flask backend works
![Proof that the Notification flask backend works](assets/week-1/testing-notification-wk1.png)

### Write a React Page for Notifications 	
I was also able to write the notification react page following the instruction on the video

> Notification react page
![Notification react page](assets/week-1/notification_react_codes-wk1.png)

> Notification UI page
![Notification UI page](assets/week-1/notification_ui_page-wk1.png)

### Run DynamoDB and Postgres Local Container
> DynamoDB and Postgress docker-compose code
![DynamoDB and Postgress docker-compose code](assets/week-1/dynamo_postgress_dockerCompose_code-wk1.png)

> DynamoDB and Postgress container running
![DynamoDB and Postgress container running](assets/week-1/dynamo_postgres_containers_running-wk1.png)

#### Running DynamoDB Local Container and ensuring it works
> DynamoDB local container works
![DynamoDB local container works](assets/week-1/dynamoDB_working-wk1.png)

#### Running Postgres Local Container and ensuring it works
> Postgres local container works
![Postgres local container works](assets/week-1/postgress_working-wk1.png)

# Week 1 — Extra efforts

### Installation of snyx CLI
I attempted to install the snyx CLI following the documentation below:

> Link to snyx CLI installation documentation
[Link to snyx CLI installation documentation](https://docs.snyk.io/snyk-cli/install-the-snyk-cli)
![Image below](assets/week-1/install_snyx_CLI-wk1.png)
