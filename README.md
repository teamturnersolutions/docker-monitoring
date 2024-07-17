![image](https://github.com/user-attachments/assets/67884533-8164-4b3e-89e9-c59045a8e497)


# docker-monitoring
monitoring docker containers using cadvisor, prometheus,redis and grafana
# run - docker-compose up
if everything is working good, you should see this message <br>
msg="Server is ready to receive web requests." <br>
check three containers are running using docker-compose ps
# accessing cadvisor
http://localhost:8080
# accessing prometheus
http://localhost:9090
# running grafana on docker host
docker run -d --name grafana -p 3000:3000 grafana/grafana <br> <br>
Access grafana using
http://localhost:3000
# configure grafana to use prometheus as data source 

# Shout out NetworkNuts for the template
## Link to the Resources:

### https://www.docker.com/
### https://www.portainer.io/
### https://ibm.github.io/ibm-z-oss-hub/containers/cadvisor.html
### https://prometheus.io/
### https://grafana.com
### https://youtu.be/Q_tmu5Wte9E?si=5KnU9E9lgTqh2yDb


