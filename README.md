# flask-redis
create stackdemo directory and go in it
create multi node environment by using docker swarm
** docker swarm init --advertise-addr=ipofhost **
also join node machines 

update the docker-compose version if not supported by below steps
/* 
rm /usr/bin/docker-compose
curl -SL https://github.com/docker/compose/releases/download/v2.17.2/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
chmod o+x /usr/bin/docker-compose
*/
clone this replository by git clone ******
run the below steps
** docker stack deploy --compose-file docker-compose.yml stackdemo **

you'll be access the page through localhost:8000 




