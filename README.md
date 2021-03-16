# Rebalancing Kafka Cluster

   When New Brokers are added to an existing Kafka cluster, these brokers will not be assigned any data partition of the existing topics in the cluster, 
unless the partitions are moved or new topics are created the brokers won’t be doing much work. Rebalancing the cluster will move the topic partitions across the kafka cluster makes it a balanced
brokers which will distribute the Load on the brokers.

