# WuKong

##  Analysis

We describe the [operations](docs/Operations.md).suppoted by the system mentioned below.
Then, we give the parameters of each system in detail.


TABLE I: The list of supported System
|  Country  |   Type    |   Name    |  Offical  |  Support  |
| :-------: | :-------: | :-------: | :-------: | :-------: |
|  ---      | Container | Kubernetes|    No     |    Yes    |
|  ---      | Container | OpenShift |    No     |    Yes    |
|  ---      | Container |   Docker  |    No     |  **No**   |
|  America  |     VM    |   Amazon  |    Yes    |    Yes    |
|  America  |     VM    |   Azure   |    Yes    |  **No**   |
|  America  |     VM    |   Google  |    Yes    |    Yes    |
|  China    |     VM    |   Aliyun  |    Yes    |    Yes    |
|  China    |     VM    |   Tencent |    Yes    |    Yes    |
|  China    |     VM    |   Baidu   |    Yes    |    Yes    |
|  China    |     VM    |   JD      |    Yes    |    Yes    |

**Node that the value of "No" in column "Support" just means the related API
of target system does not satisfy our assumptions**


### Container

1. [Kubernetes](docs/Kubernetes-Analysis.md)
2. [OpenShift](docs/OpenShift-Analysis.md)


### VM
1. [Amazon EC2](docs/AmazonEc2-Analysis.md)
2. [Aliyun ECS](docs/AliyunECS-Analysis.md)
