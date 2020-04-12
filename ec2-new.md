{
  "AWSTemplateFormatVersion": "2010-09-09",

  "Description": "\"AWS CloudFormation Sample Template.",
  "Resources": {
    "EC2Instance": {
      "Type": "AWS::EC2::Instance",
      "Properties": {
        "AvailabilityZone": "us-east-1b",
        "ImageId": "ami-0f02ee371c8994d61",
        "InstanceType": "t2.micro",
        "KeyName": "mrezeino",
        "SecurityGroupIds": "sg-0fc7dc163dcbc5baf",
        "SecurityGroups": "kuberny",
        "SubnetId": "subnet-6ac82f35"
      }
    }
  }
}
