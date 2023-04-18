# sample-eks-cluster

Sample terraform project utilizing eks-mtp generic terraform modules to demonstrate how to build AWS EKS cluster with desired features.

## how to create AWS eks_mtp profile

AWS **eks_mtp** profile is needed since it is used across the scripts. You can create it from AWS CLI

```
aws configure --profile eks_mtp
```

Note: for non-default location of AWS credentials file see [this link](https://docs.aws.amazon.com/sdkref/latest/guide/file-location.html):

```
echo $AWS_SHARED_CREDENTIALS_FILE
```
