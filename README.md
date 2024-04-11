# test-bezzwax
## Devops Exercise for Bezzwax

For this exercise, you will be creating a deployment pipeline for a full stack web application. You may use any modern technology and any hosting solution.

The READMEs for the repositories below include instructions for getting started, installation, building, and deployment. Beyond what is described here, you are not restricted in any way; however, you will be asked why you made the decisions that you did. For example, you may combine the client and server repositories into a monorepo, if you prefer.


## Frontend code (React application):

https://github.com/beezwax/exercise-devops-client

## Backend code (Node application):

https://github.com/beezwax/exercise-devops-server

We recommend successfully running the applications locally first before working on any deployment steps. The exercise is considered completed when the full stack application has been deployed to a live environment and it is possible to access the frontend via a public URL such as https://foobar.domain.com.

Note that this submission may be reviewed by others in the hiring team, so considerations such as clean design, documentation, and similar best practices are encouraged.

When finished, share your repository or repositories containing the deployment artifacts with us and send us the answers to the questions below.

## Architecture Diagram
====

### What is the public URL of the frontend application?

***

### How would you support a requirement where changes to `master` branch are automatically deployed to the live environment?

***

### How would you support a requirement for multiple environments, where changes to `master` branch are automatically deployed to a staging environment, which can then be promoted to a production environment on demand?

***

### How would you support a requirement where multiple backend instances are available to clients behind a load balancer?

***

### How would you support a requirement where the `npm test` script is run whenever a PR is published, and the PR is blocked from merge if the script finds errors (e.g. failing test)?

***

### How would you support a requirement where whenever a PR is published, a new environment is dynamically provisioned and the PR build is deployed to that new environment for preview, testing, validation purposes?
***
