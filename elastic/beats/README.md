# Example Beat Configurations

## Filebeat

| **Rule File** | **Description** |
| --- | --- |
| apache_mysql.yaml | Forwards all Apache logs and MySQL query logs to Logstash |
| apache.yaml | Forwards all Apache logs to Logstash |
| cobaltstrike.yml | Forwards web and event logs generated by Aggressor scripts (/resources/cobaltstrike/) to Logstash |


## Metricbeat

| **Rule File** | **Description** |
| --- | --- |
| metricbeat.yaml | Forwards CPU usage to Logstash |