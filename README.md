# What is GitOps

GitOps is a way to do continuous delivery, which involves using Git as a source of truth for defining the desired state of applications and infrastructure, and then using that information to drive automated deployment processes. The basic idea of GitOps is to use Git repositories to store the configuration of your applications and infrastructure, and then use Git to manage and enforce the desired state. This means that all changes to your systems are made through pull requests, code review, and version control, just like you would for any other software project.

With GitOps, the deployment process is automated and triggered by changes to the Git repository. For example, if a new version of an application is pushed to the repository, the continuous delivery pipeline is triggered, which automatically deploys the new version to production. This helps to ensure that the desired state of the system is always maintained and that deployments are consistent, repeatable, and reliable.

GitOps is particularly well suited to cloud-native environments, where infrastructure is often managed as code, but it can also be applied to other types of infrastructure and applications. By using Git as the source of truth, GitOps can provide a high level of visibility and control over the deployment process, making it easier to track changes and debug issues.
