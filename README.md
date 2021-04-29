DVWA Servers
Two highly available DVWA web servers for pen testing, supported by one load balancer, provisioned by Ansible from a Jumpbox with firewall rules. Deployed on Azure.

ELK Stack Server
ELK Stack server, provisioned with Ansible, that uses Logstash to pipe traffic data from the DVWA servers, uses Elastic to organize the traffic data, and use Kibana to provide a dashboard. ELK server has Log Beat and Metric Beat on it.