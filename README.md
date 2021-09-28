# elastic-kibana-docker

3 node elasticsearch cluster and kibana docker-compose file for self learning

this is a docker-compose file which contains yml code for setup of a 3 node elasticsearch cluster with 1 master and 2 data nodes. 
There is also a kibana image attached which helps the user to use the elasticsearch-kibana 

For usage follow the commands on a terminal after cloning this repo:

get into the repository
`cd elastic-kibana-docker`

use the command to pull the images from docker hub and start them:
`docker-compose up`

Now you would be able to access Kibana on http://localhost:5601/

