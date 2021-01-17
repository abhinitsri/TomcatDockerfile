# TomcatDockerfile
The download link for tar file will change time to time and according to version.

# Souce 
https://github.com/lobster1234/dockerfiles/blob/master/tomcat8/Dockerfile

# Building the image
docker build -t tomcatimage . 

# Running the image
docker run -d -p8000:8080 --name tomcatcontainer Image_id

# Localhost

After this the tomcat server will be avaliable at localhost:8000
