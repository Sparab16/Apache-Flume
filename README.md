# Overview

Apache Flume is distributed, reliable, and available system for efficiently collecting, aggregating, and moving large amounts of data from many different sources to a centralized data store.

Here in this repository we have used the Apache Flume to transfer the data from : 

1. Netcat to HDFS

    Once config file is ready. Run the following command : 

    ```bash
    $ flume-ng agent --name <agent-name> -f <config-filename>
    ```

    Also run the below command in another shell :

    ```bash
    $ nc <IP Address> <Port Number>
    ```

    The data which is written is then stored into the HDFS file location which is given in the config file.

2. local file system(Spooled Directory) to HDFS

    Once the config file is ready. Run the following command :
    : 
    
    ```bash
    $ flume-ng agent --name <agent-name> -f <config-filename>
    ```

