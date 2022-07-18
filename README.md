# Pasos para Ejerscio 3

* Bajar imagen nginx

    > docker pull nicopaez/passwordapi-java:java8-fabric

    > docker pull nicopaez/passwordapi-java:java8-alpine

* luego se realizo un docker inspect 

    >  docker image history nicopaez/passwordapi-java:java8-fabric

    >  docker image history nicopaez/passwordapi-java:java8-alpine

* Fabric tiene 17 capas

* alpine tiene 11 capas

* en comun tienen
    >  CMD ["/bin/sh"]

    >  ADD file:25f61d70254b98

