# Nagios-AWS-Plugins

This repository aims to make available Nagios plugins for Amazon Web Service (AWS) to the DevOps community.

These plugins have been developed by SecludIT and already made available on Nagios-Exchange:
 * Check_AWS_CloudWatch_metrics plugin on Nagios-Exchange: 
   This is a ruby script that retrieve metrics from Amazon Web Service EC2, ELB or RDS using Amazon CloudWatch API (supports all AWS region).
   https://exchange.nagios.org/directory/Plugins/Operating-Systems/%2A-Virtual-Environments/Others/Check_AWS_CloudWatch_metrics/details
 * Check_AWS_EC2_instance_status:
   This is a ruby script that checks the status of an instance on Amazon Web Service EC2 using Amazon EC2 API.
   https://exchange.nagios.org/directory/Plugins/Operating-Systems/%2A-Virtual-Environments/Others/Check_AWS_EC2_instance_status/details

This is a ruby script that retrieve metrics from Amazon Web Service EC2, ELB or RDS using Amazon CloudWatch API (supports all AWS region).
The Amazon credentials (Access Key ID and Secret Access Key) are read from an encrypted file.

NB: Amazon CloudWatch Namespaces, Dimensions, and Metrics Reference: http://docs.aws.amazon.com/AmazonCloudWatch/latest/DeveloperGuide/CW_Support_For_AWS.html

####  CHANGELOG  ####
##  1.0.0
  - Initial import the Nagios AWS CloudWatch plugin from SecludIT repository (SVN Rev 6433)

## Contributing

1. Create your fork by clicking Fork button on top of the page.
2. Download your repository: `git clone https://github.com/SecludIT/Nagios-AWS-Plugins.git`
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'My new feature description'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request
