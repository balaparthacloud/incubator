# Docker

### videos
#### architecture | install | commands
- https://www.youtube.com/watch?v=zJ6WbK9zFpI

### hub
where are all images stored for docker:
- https://hub.docker.com/

### Repo
we have some repositories :
- balaparthacloud/new:latest

### Commands examples from in28minutes

```
  600  docker run in28min/todo-rest-api-h2:1.0.0.RELEASE
  650  docker run -p 5000:5000 in28min/todo-rest-api-h2:1.0.0.RELEASE
  651  clear
  652  docker run -p 8761:8761 springcloud/eureka
  653  clear
  654  docker run -d -p 5000:5000 in28min/todo-rest-api-h2:1.0.0.RELEASE
  655  docker run -d -p 8761:8761 springcloud/eureka
  656  docker images
  657  docker containers 
  658  docker containers ls
  659  docker container
  660  docker container ls
  661  docker container ls -l
  662  docker container ls -l
  663  docker container ls
  664  docker container ls -a
  665  clear
  666  docker container ls -a
  667  docker container start fed549e69e9d
  668  docker container ls
  669  docker container stop tender_ardinghelli
  670  docker container ls
  671  docker container ls -a
  672  clear
  673  docker container ls -a
  674  docker container start c165f459e7d7
  675  docker container stop 151a77679241
  676  docker container start c165f459e7d7
  677  docker container logs c165f459e7d7
  678  docker container logs c165f459e7d7
  679  docker container logs c165f459e7d7
  680  docker container logs c165f459e7d7
  681  docker container ls
  682  docker container ls -a
  683  docker container rm fed549e69e9d
  684  docker container ls -a
  685  docker container prune
  686  docker container ls -a
  687  docker container inspect 0967ba7aa180
  688  docker images
  689  docker image history f8049a029560
  690  clear
  691  docker images
  692  docker image history in28min/todo-rest-api-h2
  693  docker image history in28min/todo-rest-api-h2:1.0.0.RELEASE
  694  docker images
  695  docker image remove f8049a029560
  696  docker image remove 3094afcbdf12
  697  docker container stop c165f459e7d7
  698  docker image remove 3094afcbdf12
  699  docker container rm c165f459e7d7
  700  docker image remove 3094afcbdf12
  701  docker images
  702  docker containers ls
  703  docker container ls
  704  docker container ls -a
```