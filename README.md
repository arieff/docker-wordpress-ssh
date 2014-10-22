Dockerfile for Running wordpress & sshd inside container
This is a modified fork from "imankulov/docker-wordpress-ssh".

Start your image:

docker run -d -p 1080:80 -p 1022:22 -e ROOT_PASSWORD=qwert890 arif/wordpress-ssh
