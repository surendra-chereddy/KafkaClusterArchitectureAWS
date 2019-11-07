# KafkaClusterArchitectureAWS
Setup and administration of kafka cluster on AWS from End To End 

Prequisities:

Zookeeper and kafka must know their Hostname and ip adresses
Hostnames and ip Adresses not supposed to change over time even  after a reboot otherwise the cluster will be broken
 1. Use an Elastic Public ip == constant Ip to acces to the cluster from outside 
 2. Use a secondary ENI == constant private ip  we will not be able to access to the cluster from outside only from the same VPC

 3. Use DNS names no need to keep fixed ips and we will able to access to cluster from inside and outside VPC

