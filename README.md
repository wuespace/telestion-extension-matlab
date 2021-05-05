# telestion-extension-matlab

This Telestion extension provides access to Matlab scripts.
It executes basic scripts inside a given folder and forwards data from and to the scripts.
The data is interpreted and published back into the Vert.x system.

## Run locally

Add the `engine.jar` of Matlab to the lib folder.

To fetch the dependencies locally you need a Github personal access token with `packages:read` rights.
Either add your github user name and the token as `GITHUB_ACTOR` and `GITHUB_TOKEN` to your environment variables 
or copy the file `.github.credentials.template` and rename it to `gradle.properties`. Then you can insert the credentials in it.
