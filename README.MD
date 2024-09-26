FIRST CONFIGURATIONS<br>
1. At traefik.yml configure the lines that have comments<br>


RATE-MONITORING<br>
At a browser, enter http://localhost:3000. Then go to dashboards and you will see Rate-Monitor dashboards. There you can adjusts rates.<br>
If there is no dashboard you can import dashboard using Rate-Monitor JSON file. For the prometheus data source, http://prometheus:9090 url can be used.<br>
RATE-LIMITING<br>
Change the error html file as your custom response.<br>
LOAD BALANCING<br>
At traefik.yml, add the docker service urls to be used in load-balancing.<br>
CERTIFICATE<br>
Be sure that hosting has ACME enabled.