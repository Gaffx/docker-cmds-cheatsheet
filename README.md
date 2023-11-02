# docker-cmds-cheatsheet
**A bunch of useful Docker commands**



`docker images`

`docker run --name <container-name (not the image)> -it ubuntu bash`

`docker cp ./remnux_install.sh remnux-sift:/root`

`docker start -i <container-name>`

`docker stop <container-name>`

`docker rm <container-id>    (get the container id using  $docker ps -all) then delete the image using :`

`docker rmi <container-name>`

`docker ps -all`

