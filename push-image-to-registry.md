# Push image to ECR

1. set up AWS credential บน เครื่อง development 

2. push docker image ขึ้นไปบน ECR ด้วยคำสั่ง
```sh
docker push <registry-address>:<tag>
```


## Other Docment
- [Create EC2 instance](./create-ec2.md)
- [Create ECR](./create-ecr.md)
- [Build Docker images](./build-docker.md)
- [Push images to registry (ECR)](./push-image-to-registry.md)