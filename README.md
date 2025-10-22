# Deploy Node App on Docker Container

# Step 1

```bash
 https://github.com/muhammadaliazhar/NodeApp-docker.git
```

# Step 2

```bash
docker build -t node-app .
```

# Step 3

```bash
docker run -d -p 8000:8000 node-app
```


<img width="1507" height="226" alt="image" src="https://github.com/user-attachments/assets/f07ae859-bab2-4c2c-8e6c-465161a75977" />



# Step 4

Open port 8000 on your instance security group ( firewall rule )

Hit public-ip:8000 of your instance on a browser


<img width="1366" height="645" alt="image" src="https://github.com/user-attachments/assets/0cbfd262-c26f-4874-9d4c-3afbd31a9ec5" />


# Step 5

Check container logs
```bash
docker logs <container-id>
```


# Real-time container logs
To see real time logs of a docker container we use attach command, this will attach our host terminal with the container terminal

```bash
docker attach <container-id
```





