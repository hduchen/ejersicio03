# Pasos para Ejerscio 3

* Bajar imagen nginx

    > docker pull nicopaez/passwordapi-java:java8-fabric

    > docker pull nicopaez/passwordapi-java:java8-alpine

* luego se realizo un docker inspect 

    >  docker inspect nicopaez/passwordapi-java:java8-fabric

    >  docker inspect nicopaez/passwordapi-java:java8-alpine
* Fabric tiene 10 layers

* alpine tiene 4 layers

* en comun tiene la layer --> sha256:73046094a9b835e443af1a9d736fcfc11a994107500e474d0abf399499ed280c
