# install Docker on Amazon Linux
**The procedure to install docker on Amazon Linux is as follows:**


<sub>Note: To install [docker compose](https://github.com/saiunes/install-docker-compose-Amazon-Linux/) follow instructions on [this page](https://github.com/saiunes/install-docker-compose-Amazon-Linux/)</sub> 


```
sudo amazon-linux-extras install docker
```

```
sudo service docker start
```

```
sudo usermod -a -G docker ec2-user
```

**Docker automatic start**
```
sudo chkconfig docker on
```

**Reboot the EC2**

```
sudo reboot
```
