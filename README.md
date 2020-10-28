# BambooManual
Bamboo is a Continuous Integration (CI) server that can be used to automate the release management for a software application, thus creating a continuous delivery pipeline. This means that builds, unit tests, integration tests and so forth are performed or triggered whenever code is committed to the repository. This methodology ensures that new changes are integrated well into the existing code base. Integration builds provide feedback on the quality of new changes.

Bamboo solves numerous problems for solo and team projects. Solo developers can rely on the automated builds and test processes to check for the quality of new code, therefore allowing them to focus on coding. Another advantage of Bamboo is that the deployments can be automated to a server, such as App Store, Google Play or Azure. Additionally Bamboo is a way to manage different builds that have different targets or requirements. This is useful because production builds have different requirements than development or test builds.

The above advantages also work for teams. In addition, builds and test processes are not dependent on a specific local environment. Lastly, builds and integration tests are triggered automatically as soon as the developer commits code, thus allowing for continuous integration.

Bamboo creates these advantages by implementing the functionalities below:

●	Bamboo is a central management server which schedules and coordinates all work.
●	Bamboo implements interfaces and plugins for different types of work.

Bamboo works in the following order:

1.	Bamboo retrieves your source from a source repository.
2.	Bamboo starts the build by calling something like MSBuild to build your Visual Studio solution.
3.	Once the solution or project is built, you have artifacts like build results, executable apps, config files, etc.
4.	With these artifacts you can zip them up and copy them or install them on a test server to make sure everything runs fine.
