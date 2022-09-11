## Install docker & docker-compose
   Install Docker using this guide
```bash
https://docs.docker.com/engine/install/ubuntu/
```
Install docker-compose with the following commands (pip)
```bash
$sudo apt install python3-pip
$python3 -m pip install docker-compose
```

## Create the .env File
 
  ```bash
VERSION=<latest version (2.1.0p10)>
TYPE=check-mk-free
 ```
 
  ## Checkmk free version
   ```bash
$wget https://download.checkmk.com/checkmk/<latest version like 2.1.0p10>/check-mk-free-docker-<latest version>.tar.gz 
  ```
run the downloaded file


 ```bash
$docker load -i check-mk-free-docker-2.0.0p10.tar.gz
```


and finally run the docker-compose
 ```bash
 $docker-compose up
 ```
