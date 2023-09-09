> hdfs-site.xml

> dfs.permissions  # default is true, can be turned off

#  run mapreduce jobs

> hadoop jar /opt/cloudera/parcels/CDH/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar pi 10 10

# get file block informations

> hadoop fsck /usr/bob -files -blocks -locations


## instal wireshark

> yum install libpcap
> yum install wireshark

> sudo dumpcap -i eth0

> sudo tshark -r /path/to capture files/  -v | grep -i foo
