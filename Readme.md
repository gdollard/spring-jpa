
Start up the mysql container: docker-compose up -d

If port is already in use:
doccker-compose down 
or of that fails for some reason:
sudo kill `sudo lsof -t -i:3306`

Some handy docker commands:
docker inspect <pid>
docker inspect <pid> | grep "IPAddress"




