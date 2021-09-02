```
_______                       __                           
/       \                     /  |                          
$$$$$$$  |  ______    _______ $$ |   __   ______    ______  
$$ |  $$ | /      \  /       |$$ |  /  | /      \  /      \ 
$$ |  $$ |/$$$$$$  |/$$$$$$$/ $$ |_/$$/ /$$$$$$  |/$$$$$$  |
$$ |  $$ |$$ |  $$ |$$ |      $$   $$<  $$    $$ |$$ |  $$/ 
$$ |__$$ |$$ \__$$ |$$ \_____ $$$$$$  \ $$$$$$$$/ $$ |      
$$    $$/ $$    $$/ $$       |$$ | $$  |$$       |$$ |      
$$$$$$$/   $$$$$$/   $$$$$$$/ $$/   $$/  $$$$$$$/ $$/   

```

# docker-mongo-cluster
docker로 구성한 mongo-cluster 연습

## Environments
 - Ubuntu 20.04.2 LTS
 - Mongo DB version 4.4.6
 - docker

## Get started
1. Run each config-server container 

server1 - /config1/docker-compose.yaml
```
docker-compose up
```

server2 - /config2/docker-compose.yaml
```
docker-compose up
```

server3 - /config3/docker-compose.yaml
```
docker-compose up
```
