To run execute:
`docker build -t fullcycle-hello-world .`

after that, run:
`docker run -d -it --name www fullcycle-hello-world`

later run the code below and get the IPAddress:
`docker inspect www | grep Address`

Now, put the IPAddress + port in browser like:
`http://172.17.0.2:8084/`
