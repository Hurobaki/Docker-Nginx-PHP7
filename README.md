# My docker Nginx - PHP7 configuration

Just to keep my Docker Nginx - PHP7 configuration

## Getting starting

You need to install Docker - [Install Docker](https://docs.docker.com/engine/installation/#server)

And docker-compose - [Install docker-compose](https://docs.docker.com/compose/install/#install-compose)

## Installation
The only thing you have to do before launching is to modify the "server_name" param into nginx.conf file

If you have a server with a DNS you can specifiy its name

In case of local configuration you have to create a new host in your /etc/hosts file

Just add new line for example 

```bash
$ 127.0.0.1	 nginx.dev
```
That's all ! You can put your code files into code directory that is shared with the container

## Authors

* **Théo Herveux** - *Initial Work* - [MyGit](https://github.com/Hurobaki)
