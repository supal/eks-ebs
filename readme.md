## Running EKS Cluster with EBS

### Objective

The goal is to run an EKS cluster with Amazon EBS.

### Steps

1. **Create EBS Storage Manually**
   - First, manually create an EBS volume using the AWS Management Console or AWS CLI.

2. **Set Up Persistent Volume (PV) and Persistent Volume Claim (PVC)**
   - Use the provided YAML files to create the Persistent Volume (PV) and Persistent Volume Claim (PVC) in the EKS cluster.
   - Ensure that the PV is correctly associated with the manually created EBS volume.

3. **Run the Pod**
   - Once the PV and PVC are set up, deploy the pod that will use the EBS volume for storage.
