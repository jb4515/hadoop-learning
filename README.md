# hadoop-learning
# Basic app for running on local 

# provide conf directory that is outside hadoop ecosystem and inside your maven project
export HADOOP_CONF_DIR={path_to_conf_directory_under_resources}
#start namemodes and datanode
> {PATH_TO_HADOOP}/bin/hdfs namenode -format
>  {PATH_TO_HADOOP}/bin/hdfs datanode -format
>  {PATH_TO_HADOOP}/sbin/start-dfs.sh

#run below command to verify
> {PATH_TO_HADOOP}/bin/hadoop fs -lsFound 2 items

