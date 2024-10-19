# dvmhost-docker
1). git clone https://github.com/nf9k/dvmhost-docker.git  
2). cd ./dvmhost-docker  
3). cp ./config.example.yml ./config.yml  
4). Edit config.yml as needed:

    CHANGEME_IDENTITY - site identity (IN_ + 3-letter designator, ex. IN_IND)
    CHANGEME_ID - site peer ID (from connectivity plan, ex 311802)
    CHANGEME_LOCATION - site location name (i.e. Indianapolis, IN)

5). docker-compose up -d
