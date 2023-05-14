## Installation and setup

### Download and install elastic -> https://www.elastic.co/downloads/elasticsearch
### Download and install Kibana -> https://logz.io/blog/brew-install-elasticsearch-mac/


* After installation
  * goto /elasticsearch-8.7.1/bin -> 
  * hit the cmd `./elasticsearch -E xpack.security.enabled=false`
  *  `brew services start elastic/tap/kibana-full`
* Load the postman collection [PostmanCollection](/postmancollection.json) in Postman app and hit the APIs



