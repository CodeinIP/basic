# CI/CD = Continuous Integration and Continuous Deployment

- ***Continuous Integration*** is the software engineering practive that requires frequent commits to a shared repository. You may have gotten so used to this practice that you may wonder why there's a term for it.

- To understand this better, let us consider the opposite fo CI. Before 
cI, people would work on feature branches for weeks or monghts and then try to merge this branch to a main branch. Think aobut all that could go wrong during such merge -- merge conflicts and failing tests, just to mention a few.
- Continuous Integration tries to prevent all of these by encouraging samll and frequent code updates. 
when code is committed to a repository, it can be build adn tested against setup workflows to ensure that the code does nto introduce any errors.
- ***Continuous Deployment*** means code changes are automatically deployed/released to a testing or production environment as sooon as they are merged. This is often interchangedwith continuous delivery and that's because they are very similar.
- The only difference is that in continous delivery, human intervention(e.g., the click of a button) is needed for the changes to be released. However, in continuous deployment, everything happens automatically. 
### Advantages of CI/CD
- Fault isolation is simpler and faster. Since changes are smaller, it is easier to isolate the changes that cause a bug after deployment. This makes it easier to fix or roll back changes if necessary.
- Since CI/CD encourages samll , frequent changes, code review time is shorter
- A major part of the CI/CD pipeline is the automated testing of critical flows for a project. This makes it easier to prevent changes that may break these flows in production.
- Better code quality is ensured because you can configure the pipeline to test against linting rules.

## What are GitHub Actions?
- GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, deployment pipeline.
- You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.