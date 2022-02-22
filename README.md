# STweep CLI github actions example.

This repository is an example of how STweep CLI can be used in a build server environment as Github Actions.
The repository contains an unformatted TwinCAT PLC project and a Github actions workflow file.

The workflow is automatically executed on a push and formats the PLC code with STweep CLI. 
If any changes are detected a pull request is created for the user to review.

