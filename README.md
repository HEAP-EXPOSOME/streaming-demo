# streaming-demo
Streaming tutorial notebooks for PPG data 

This is an example of producing and consuming streaming data from external Kafka topic into Hopsworks.
We use dummy PPG data for simulating streaming data. It needs a Kafka cluster and a topic created as an initial step. After the cluster is created run

 -  notebook `producer_data_external` for producing messages to a topic
 - notebook `consume_ppg_data_external` for consuming stream a topic and ingest to Hopsworks

 Reference

- HeartPy https://github.com/paulvangentcom/heartrate_analysis_python