FROM grafana/grafana:9.0.1-ubuntu

WORKDIR /dashboards
VOLUME [ "/dashboards"]
COPY /dockerfiles/addons/grafana/dashboards/    /dashboards/
 
EXPOSE 3000