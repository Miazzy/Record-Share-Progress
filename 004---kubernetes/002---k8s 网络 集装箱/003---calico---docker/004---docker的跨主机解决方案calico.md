
# 场景介绍   
- 场景一: 容器内可以访问calico宿主机   
    
- 场景二：容器内可以访问calico集群内非宿主机  
- 场景三：集群内的主机访问容器   
- 场景四：集群外在同一网段，可以访问容器  
- 场景五：集群外非同一网段，也可以访问容器   


docker network create --driver calico --ipam-driver calico-ipam net1














