# Automatic Docker package
DISCLAIMER: I don't know the security risks when using this template.

This is a template to automatically create a docker package as soon as a release gets published.

## How to use it

In [.github/workflows](https://github.com/dieser-niko/docker-action-package/tree/main/.github/workflows) there are two files. docker-image.yml and major-version-updater.yml.
The first one is more important, but the second one can be used as an addition so that the repo has the same tags as the package.

Just copy them into your repo and make sure that your Dockerfile is included.

Labels like release description, website, repo source URL, license and more will be automatically applied if available.

