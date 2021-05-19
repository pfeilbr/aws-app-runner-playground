# aws-app-runner-playground

learn [AWS App Runner](https://aws.amazon.com/blogs/containers/introducing-aws-app-runner/)

* autoscale, no clusters
* `apprunner.yaml`
* connect directly to github
* configure see [Create a source code repository service](https://docs.aws.amazon.com/apprunner/latest/api/API_CreateService.html#API_CreateService_Example_1) for all options
    * health check config
    * cpu, memory
    * instance role
* custom domain support
* [Node](https://docs.aws.amazon.com/apprunner/latest/dg/service-source-code-nodejs.html) and [Python](https://docs.aws.amazon.com/apprunner/latest/dg/service-source-code-python.html) managed container runtimes to start.
* public endpoints only (as of 2021-05-18)

## Pricing

> You are charged for the compute and memory resources used by your application. In addition, if you automate your deployments, you will pay a set monthly fee for each application that covers all automated deployments for that month. If you opt to deploy from source code, you will pay a build fee for the amount of time it takes App Runner to build a container from your source code.

---
## Resources

* [Introducing AWS App Runner](https://aws.amazon.com/blogs/containers/introducing-aws-app-runner/)
* [Documentation | AWS App Runner](https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html)
* [aws-containers/apprunnerworkshop](https://github.com/aws-containers/apprunnerworkshop)
* [apprunner-roadmap](https://github.com/aws/apprunner-roadmap/projects/1)
* [aws-containers/hello-app-runner](https://github.com/aws-containers/hello-app-runner)
* [AWS App Runner API Reference](https://docs.aws.amazon.com/apprunner/latest/api/Welcome.html)
* [Pricing](https://aws.amazon.com/apprunner/pricing/)