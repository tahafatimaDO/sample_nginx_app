Commands to Build  and run it. Please run the below commands from the root directory.

Build Command: docker build --tag=simpleubuntu . 

Run Command:
docker run --detach --publish=5001:80\
    --name=simpleubuntu simpleubuntu
