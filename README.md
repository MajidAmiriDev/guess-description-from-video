

### Try it out!!!
* Please feel free to raise PR with necessary suggestions.
* Clone the repository`
  * `git clone https://github.com/scopeInfinity/Video2Description.git`
* Install docker and docker-compose
  * Current config has docker-compose file format '3.2'.
    * https://github.com/docker/compose/releases
  * ```bash
    sudo apt-get install docker.io
    sudo curl -L "https://github.com/docker/compose/releases/download/1.25.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    sudo chmod +x /usr/local/bin/docker-compose
    ```
  * docs
    * https://docs.docker.com/install/linux/docker-ce/ubuntu/
    * https://docs.docker.com/compose/install/

* Pull the prebuild images and run the container
```bash
$ docker-compose pull
$ docker-compose up
```
* Browse to `http://localhost:8080/`
  * backend might take few minutes to reach a stable stage.
