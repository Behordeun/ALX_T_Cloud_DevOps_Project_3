[![CircleCI](https://dl.circleci.com/status-badge/img/gh/Behordeun/ALX_T_Cloud_DevOps_Project_3/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/Behordeun/ALX_T_Cloud_DevOps_Project_3/tree/main)

## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

### Instructions

* [Selling CI/CD](instructions/0-selling-cicd.md)
* [Getting Started](instructions/1-getting-started.md)
* [Deploying Working, Trustworthy Software](instructions/2-deploying-trustworthy-code.md)
* [Configuration Management](instructions/3-configuration-management.md)
* [Turn Errors into Sirens](instructions/4-turn-errors-into-sirens.md)

### Project Submission

For your submission, please submit the following:

- A text file named `urls.txt` including:

  1. Public Url to GitHub repository (not private) [URL01]
  2. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]
  3. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03]
  4. Public URLs to deployed application back-end in EC2 [URL04]
  5. Public URL to your Prometheus Server [URL05]
- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder.

  1. Job failed because of compile errors. [SCREENSHOT01][SCREENSHOT01]
  2. Job failed because of unit tests. [SCREENSHOT02][SCREENSHOT02]
  3. Job that failed because of vulnerable packages. [SCREENSHOT03][SCREENSHOT03]
  4. An alert from one of your failed builds. [SCREENSHOT04][SCREENSHOT04]
  5. Appropriate job failure for infrastructure creation. [SCREENSHOT05][SCREENSHOT05]
  6. Appropriate job failure for the smoke test job. [SCREENSHOT06][SCREENSHOT06]
  7. Successful rollback after a failed smoke test. [SCREENSHOT07][SCREENSHOT07]
  8. Successful promotion job. [SCREENSHOT08][SCREENSHOT08]
  9. Successful cleanup job. [SCREENSHOT09][SCREENSHOT09]
  10. Only deploy on pushed to `master` branch. [SCREENSHOT10][SCREENSHOT10]
  11. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11][SCREENSHOT11]
  12. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12][SCREENSHOT12]
- Your presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder.

Before you submit your project, please check your work against the project rubric. If you haven’t satisfied each criterion in the rubric, then revise your work so that you have met all the requirements.

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)

[SCREENSHOT01]: screenshot01.png
[SCREENSHOT02]: screenshot02.png
[SCREENSHOT03]: screenshot03.png
[SCREENSHOT04]: screenshot04.png
[SCREENSHOT05]: screenshot05.png
[SCREENSHOT06]: screenshot06.png
[SCREENSHOT07]: screenshot07.png
[SCREENSHOT08]: screenshot08.png
[SCREENSHOT09]: screenshot09.png
[SCREENSHOT10]: screenshot10.png
[SCREENSHOT11]: screenshot11.png
[SCREENSHOT12]: screenshot12.png
