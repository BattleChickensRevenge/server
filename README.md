[![Build Status](https://travis-ci.org/LightsHope/server.svg?branch=development)](https://travis-ci.org/LightsHope/server)

# Bug reporting:
Before opening any bug reports on the issue tracker, please read the guidelines [located here](https://github.com/LightsHope/server/blob/development/docs/).

# Development process overview:
Development work must be done by forking server to your own GitHub account and in your fork, making a new branch with a descriptive name, committing the new work to that branch and then issing a pull request to allow for your code to be automatically compiled by the continuous integration system and reviewed by other developers.

After receiving feedback and making any requested changes, your pull request will be squashed and merged to the development branch. Squashing your commits is to ensure that the development branch can be compiled at any point in its history as well as ensuring a clean history.

The development branch is used as the basis for the QA and PTR realms. To ensure the QA team receives ample opportunity to test each set of changes, the development branch will only accept pull requests for one week before being frozen for a week, during which time only essential fixes will be accepted.

Once the development branch has been tested by QA, it will be merged with the stable branch to become the next revision for the live realms. The only changes accepted to the stable branch, outside of the merge window, will be critical hotfixes to resolve game-breaking and stability issues.

As with any open source project, the workflow is subject to change as we receive feedback and discover what works best for the project and its contributors.
