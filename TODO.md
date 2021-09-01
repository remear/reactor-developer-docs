# Docs, Docker, GitHub Actions

## Background

reactor-developer-docs is a Jekyl-based project that builds a documentation
website for the Reactor API. The project is open source, and anyone may
contribute to the project.


We're in the process of migrating this site from a deprecated hosting
solution to a managed Kubernetes cluster. The build workflow is
currently broken.

## Exercise Goals

- Fix the build workflow .The build should push a Docker image to the GitHub registry.
- Utilize Helm for managing the application for use on Kubernetes
- Deploy the application to a dev Kubernetes cluster

## Helpful Links

- [Reactor Developer Docs](http://developer.adobelaunch.com)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Helm](https://helm.sh)
