# centos6.4_ambari
c6401 - bootstarpped with ambari-server, ambari-agent, kdc server, mysql server
c6402 - bootstrapped with ambari-agent pointing at c6401
c6403 - bootstrapped with ambari-agent pointing at c6402
c6404 - bootstrapped with apache webserver in reverse proxy mode on port 1100 to be used in Oozie HA scenario

note: the ambari version is the lates trunk
