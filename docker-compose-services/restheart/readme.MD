# RESTHeart 
### MongoDB API

## Installation 
Download `docker-compose.restheart.yaml` and `default.properties` to .ddev directory.  

## Dependencies
Depends on mongodb being available already, so download `docker-compose.mongo.yaml` ([link](https://github.com/drud/ddev-contrib/blob/master/docker-compose-services/mongodb/docker-compose.mongo.yaml)) to the same directory.

## Default access settings
Default username is `admin` and default password is `secret`, by default all databases are accessible at `http://project-name.ddev.site:8880/<db>/<collection>` but this can be changed by modifying default.properties and changing the `root-mongo-resource` to '/db'. Replace /db with your database name, which simplifies the URL to `http://project-name.ddev.site:8880/<collection>`. 
