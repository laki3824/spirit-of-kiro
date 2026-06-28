Errors:

1. `ecs-local-endpoints-1 exited with code 2` on Mac Apple Silicon - This is a known compatiable issue with arm64. Just change the docker image in the podmad for ecs container to arm64 compatiable one

   Fix: Update the ecs-local-endpoints: image details in `docker-compose.yml`file 
    ```
    image: amazon/amazon-ecs-local-container-endpoints:latest-arm64
   ```
