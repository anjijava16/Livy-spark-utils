# LivyDemo

# youtube
1. https://www.youtube.com/watch?v=eZiglGrPH8M&list=PLmZzyjM-vqX7LvfN9vONdClnNxigeENw6


# A Data Engineer's Lunch demo of Apache Livy

https://github.com/anomnaco/python_etl

https://www.slideshare.net/AnantCorp/data-engineers-lunch-41-pygrametl


https://www.slideshare.net/AnantCorp/presentations


https://livy.apache.org/examples/

https://github.com/anomnaco/LivyDemo

livy.file.local-dir-whitelist = /workspace/LivyDemo/spark-2.4.8-bin-hadoop2.7/examples/jars/



https://community.cloudera.com/t5/Community-Articles/How-to-Submit-Spark-Application-through-Livy-REST-API/ta-p/247502



# Data Engineer Links
1. https://github.com/Anant/example-elassandra-kafka-spark
2. https://github.com/anomnaco/python_etl



# Start the Spark & Livy
cd spark-2.4.8-bin-hadoop2.7/sbin
$./start-master.sh
$./start-slave.sh spark://host:7077
export SPARK_HOME=/workspace/LivyDemo/spark-2.4.8-bin-hadoop2.7
$ cd apache-livy-0.7.1-incubating-bin/bin/livy-server start
livy.file.local-dir-whitelist = /workspace/LivyDemo/spark-2.4.8-bin-hadoop2.7/examples/jars/
