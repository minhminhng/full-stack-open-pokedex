### Tools for C#
When using C#, the following tools can be used
* Linting: StyleCop, FxCop, SonarLint, ReSharper
* Testing: NUnit, xUnit, MSTest
* Building: MSBuild, NuGet, Cake Build
### Alternatives to set up the CI besides Jenkins and GitHub Actions
Azure DevOps, GitLab CI/CD, Circle CI, TeamCity, TravisCI, Bamboo, AppVeyor, Semaphore, etc
### Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?
Setting up for a language is better with a self-hosted or cloud-based depends on multiple factors. Firstly, it is necessary to consider the organization's infrastructure, whether we have enough resources, expertise to do all the work as well as maintain and update the system. Secondly, we need to consider the scalability requirement of our projects. Usually, cloud-based environment is more flexible for scaling. However, on the other hand, it is crucial to take into account the cost, which becomes higher in cloud-based environment for a long run. Besides, self-hosted environment provides the organization more control over security and compatibility with existing tools and workflow. Nevertheless cloud-based environments often offer better integrations with popular version control systems.