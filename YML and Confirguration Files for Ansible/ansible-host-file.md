## [webservers]
## alpha.example.org
## beta.example.org
## 192.168.1.100
## 192.168.1.110

[webservers]
[IP Address of webserver VM] ansible_python_interpreter=/usr/bin/python3
1[IP Address of webserver VM] ansible_python_interpreter=/usr/bin/python3
[IP Address of webserver VM] ansible_python_interpreter=/usr/bin/python3

[elk]
[IP Address of ELK VM] ansible_python_interpreter=/usr/bin/python3

# If you have multiple hosts following a pattern you can specify
# them like this:

## www[001:006].example.com

# Ex 3: A collection of database servers in the 'dbservers' group

## [dbservers]
## 
## db01.intranet.mydomain.net
## db02.intranet.mydomain.net
## 10.25.1.56
## 10.25.1.57

# Here's another example of host ranges, this time there are no
# leading 0s:

## db-[99:101]-node.example.com