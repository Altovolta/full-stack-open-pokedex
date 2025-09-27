In javascript there are different tools for linting, testing, and building, some of them are:

- Linting: eslint, jshint, jslint, standardjs, jscs. Tambien esta SonarTS para typescript
- Testing: playwright, supertest, jest, vitest, cypress, puppeteer, Mocha, and others
- Building: webpack, babel, vite, esbuild, swc, parcel, snowpack and others

Apart from Jenkins and Github CI/CD, some other alternatives for CI are: GitLab CI/CD, Azure DevOps Pipelines, AWS CodePipeline, Bitbucket Pipelines, ArgoCD, CircleCI, Travis CI and more.

The setup of the CI for this project is better on a cloud-based environment because it's not a big project so there is no need to use a self hosted option and it does not need more resources than the one, in this case, github offers and it is not needed to do all the setup steps than the self-hosted options have. 

Normally to decide which setup is better i would need to know:
- Size of the project: in case its a big project it could be a good option to self host it since its quite probable that i would need more resources. Also if the project is small, the is no need to do al the setup involved in self-hosted options
- Complexity of CI/CD: in case its necessary to make a complex CI it would be a better option to use a self-hosted service since the cloud based solutions are more limited. In smaller projects it tends to have a more simple CI than on a big project
- Money: some cloud-based options are not free and tends to be more expensive than  self-hosted options