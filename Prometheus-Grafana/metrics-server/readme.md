## Metrics Server
Cluster-wide aggregator of resource usage data.

## Metrics Server Installation Steps:

1. To install the Metric-Server, first download this components.yaml file locally using:
   
   `wget https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml`

2. Use any editor of your choice to open and modify the components.yaml file:

    `vim components.yaml`

3. Modify the file in the vim editor (or your choice) and add this under deployment --> containers --> args:

    `--kubelet-insecure-tls`

Press ESCAPE key and then type :wq to write and quit. Then press ENTER. 


**Note**: The `components.yaml` file has been modified as mentioned above.

#### Reference:
https://github.com/kubernetes-incubator/metrics-server
