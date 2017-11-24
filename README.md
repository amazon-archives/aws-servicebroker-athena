# Amazon Athena for the AWS Service Broker
Provision, manage and connect to [Amazon Athena](https://aws.amazon.com/athena/).

## Prerequisites

**IAM resources** - see the [AWS Service Broker Requirements](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/Overview.md#requirements) for details

## Plans

### athena-table
Creates an Athena table using the s3 source path and column definition provided

## Retained resources

The Athena database is retained, and will only be created if it does not already exist.

## Resources

[Getting Started With OCP and the AWS Service Broker](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/getting-started.md)  
[AWS Service Broker Overview](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/Overview.md)  
[FAQ](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/FAQ.md)  
[Troubleshooting](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/Troubleshooting.md)  

## License

This library is licensed under the Apache 2.0 License.