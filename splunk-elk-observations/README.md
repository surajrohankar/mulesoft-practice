Splunk vs ELK::
========================
Splunk Instance:
1) Need to download only one instance.
2) UI will be in same instance.
3) Splunk comes with pre-loaded wizards and features.
4) Splunk’s dashboards incorporate much more accessible features than ELK’s.
5) Splunk’s license fee is based on the Daily Log Volume that is indexed.
6) No performance issue.

Splunk Cloud:
1) Dont need to do much configuration. Avalaible on Splunk cloud itself.

ELK Instance:
1) Need to download Elasticsearch, logstash, kibana and filebeat.
2) Open source but have to pay for Kibana for UI.  
3) Elasticsearch has no pre-loaded wizards and features.
4) No performance issue.

ELK Cloud:
1) ELK services has availble on AWS, GCP and Azure.
2) Else we can deploy ELK instance on AWS, GCP or Azure.
3) Need to configure Kibana, Logstash, Elasticsearch as per requirement on ELK Cloud itself.
4) If you want to go for Filebeat to collect logs then you should configure Filebeat on sever where your runtime is present(i.e. on-prem).

 

