# AWS Snowball

**Overview**
- Snowball
    - Petabyte scale data transport solution. Uses secure appliances to transfer large amounts of data into and out of AWS
    - Could be 1/5th the cost of using internet to transfer
    - Tamper resistant
    - Encryption
    - Full chain of custody
    - Performs software erasure of the snowball appliance
    - 1gbps - use snowball for 60TB or more data storage size
    - Can import to S3
    - Can export from S3
- Snowball Edge is 100TB - has onboard storage and compute capabilities. e.g. can run lambda functions
    - Support local workloads in remote or offline locations
    - Like having a mini AWS at your disposal
    - Can cluster today to form a local storage tier
- Snowmobile
    - Exabyte scale data transfer service used to move extremely large amounts of data to AWS
    - 100PB per snowmobile
    - Shipping container size on a trailer being moved by a truck
- **Snowball Lab**
    - Can submit snowball jobs
    - Shows job created, appliance preparation, shipment etc. and then tracks sending the appliance back
    - Handle to open the panel on both sides
    - Doesnt come with its own power lead. Uses 3 pin kettle shape, need your own
    - Can use RJ45, optical etc. cables to do the transfer
