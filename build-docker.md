# Build Docker image

![Alt text](assets/build-docker/docker-1.png?raw=true)
1. clone ตัวอย่าง project จาก github repo โดยใช้คำสั่ง
```sh
git clone https://github.com/Morchana/thailand-plus-backend.git
```
2. cd ไปที่ directory ที่มีงานอยู่
```sh
cd thailand-plus-backend
```

3. สั่ง build เพื่อให้ได้ docker image
```sh
docker build -t <name>:<tag> .
```

## Other Docment
- [Create EC2 instance](./create-ec2.md)
- [Create ECR](./create-ecr.md)
- [Build Docker images](./build-docker.md)
- [Push images to registry (ECR)](./push-image-to-registry.md)
