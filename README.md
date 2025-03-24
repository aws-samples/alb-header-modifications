## Securing your web applications and optimizing their performance with AWS Application Load Balancer

Amazon Web Services (AWS) Application Load Balancers (ALBs) provide a powerful feature for [modifying request and response headers](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/header-modification.html), allowing you to fine-tune your application’s behavior in numerous ways. From bolstering security with essential headers such as Content Security Policy and HTTP Strict Transport Security, to enhancing performance through caching strategies and efficient resource delivery, ALBs offer a versatile toolkit for developers and system administrators. Whether you're aiming to comply with industry standards, integrate with API gateways, or implement custom application logic, mastering header modification can significantly elevate your application's robustness and efficiency.

## Solution overview

To enable these features or use cases at scale, you can use the following solution, which queries ALBs in an [AWS Region](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/) based on the tag provided, and modifies the headers of your choice for all the ALBs with that specific tag. This solution deploys an [AWS Lambda](https://aws.amazon.com/lambda/) function to modify ALB headers at scale. The solution can run multiple times by changing the Environment variables associated to Lambda. 

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

