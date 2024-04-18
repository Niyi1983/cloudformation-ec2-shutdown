# CloudFormation template to automatically shut down EC2 instances at midnight

Saving money and cutting cost is a top priority of any organisation . organisation can save money by manually shutting down thier servers when they’re not in use. . This script offers a solution to automate the server stop  procedure by scheduling with a cron job set at midnight. The idea is to fully automate the creation of the shutdown utility rather than manually creating a Lambda fucntion, attaching a role and schedulling with cloud watch.


**CloudFormation template**

The CloudFormation template cloudformation.yaml automatically creates all the AWS resources required for the Amazon EC2 solution to function. Complete the following steps to create your AWS resources via the CloudFormation template:

On the AWS CloudFormation console, choose Create stack.
Choose With new resources (standard).
Choose Template is ready and choose Upload a template file.
Upload the provided .yaml file and choose Next.
For Stack name, enter cloudformation-auto-stop-ec2.
Choose Next and provide tags, if needed.
Choose Next and review the stack details.
Select the acknowledgement check box because this template creates an IAM role and policy.
Choose Submit.
Open the stack and navigate to the Resources tab to track the resource creation status.
