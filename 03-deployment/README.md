# 03-deployment ☸
Basic documentation about Deployment of Kubernetes

### Short Description
-----------------
* DEPLOYMENT:

  Manager of replicasets and pods.
  

### Other resources in the deployment manifest
-----------------


|    Resources    | Description  |
| :--------- | :-----------------: |
| StartupProbe<br/> | Checks when Pod is available after startup |
| ReadinessProbe <br/> | Used when we are creating a new Pod, as the Pod is unable to process requests |
| LivenessProbe <br/>| Process that checks if the process (Pod) is alive or dead |
| EnvFrom <br/>| Used to load Secrets and ConfigMap into environment variables |
| VolumeMounts <br/>| .... |
| Volumes <br/>| .... |

