

# Personal-Information
MVC Framework

 Step 1: you must import the sql file that i already inserted here in files.
 
 Step 2: after you upload the sql file in localhost. dabatabae name must be "geric" and table name must be "geric_info"
 
 Step 3: Link must be: http://localhost/Geric/Cont/



# NameNode and DataNode Updates
Hadoop

To install the Hadoop :

Step 1: You need to Download the jdk of java 8 in this link: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html#license-lightbox 

Step 2: open your Environment Variables and in your Environment Variables add new variable name JAVA_HOME and at the bottom of it add a variable value which is your address file and in the System Variable add new pathway or address of your Jdk java 8 that you have downloaded.

Step 3: Open your CMD - Command Prompt and type the Javac and enter to see if it runs successfully.

Step 4: Download the Hadoop file in this link: https://hadoop.apache.org/releases.html 

Step 5: after you downloaded all the important files, you can go to your environment variables  again and add a variable name Hadoop_Home and the variable value you can put the address file. After that you can go to your system variable at the bottom of your environment variable. You can click the path and add the jdk address, hadoop address of bin, and hadoop address of sbin.

Step 6: Add some codes of your core-site.xml, hdfs-site.xml, mapred-site.xml, yarn-site.xml, and lastly you need to edit your hadoop-env and add the jdk file address of java 8. Take note that before you change or add codes to your hdfs you need first to create a 2 file of NameNode and DataNode.

Step 7: After that you can open your CMD - Command Prompt and type the hdfs namenode -format to see if it runs successfully again.

Step 8: If it runs successfully then you can type the start-dfs.sh to see the updates of namenode and datanode.
