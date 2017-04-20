# ps-java

Example Dockerfile:

```
FROM pasientskyhosting:ps-java:latest
MAINTAINER Andreas Krüger <ak@patientsky.com>

# Add service jar files to /data
COPY service.jar /data/service.jar

# You can add adaptions to /adaptions too
```
