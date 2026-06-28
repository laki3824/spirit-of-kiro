Errors:

1. `ecs-local-endpoints-1 exited with code 2` on Mac Apple Silicon - This is a known compatiable issue with arm64. Just change the docker image in the podmad for ecs container to arm64 compatiable one
   ```
     Name	docker.io/amazon/amazon-ecs-local-container-endpoints
     Tag	latest-arm64
   ```
