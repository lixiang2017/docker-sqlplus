# sqlplus in docker
## use docker to build
docker build --pull -t instantclient:12.2  .
## usage
docker run -it --rm  instantclient:12.2 

# 
rlwrap for support up/down/left/right, no unreadable code
sleep 1; in CMD to fix an error in rlwrap
# 
and, instantclient_12.2.tar.gz is a docker image package you can load it and use it directly.
However, the error [remote: error: File instantclient_12.2.tar.gz is 223.82 MB; this exceeds GitHub's file size limit of 100.00 MB]
so you need to build it by yourself...
