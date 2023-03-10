### Docker installation
                                             
We are using Amazon Linux 2 OS for this. For reference

```
https://docs.aws.amazon.com/AmazonECS/latest/developerguide/create-container-image.html#create-container-image-install-docker
```
### Connect EC2 instance in AWS

* Create a security group that can allow all IP to all ports. Create inbound and outbound both.
* Launch an EC2 instance with AWS Linux 2 and create key pair in ppk format
* We are going to use Putty and Super putty to connect our instances. You can use any SSH client to connect.
* to connect any instance you need to provide
    * IP
    * Username
    * Password/private key
    * Port (SSH by default takes port number 22)

### Install Docker in AWS Linux 2
