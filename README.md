# stock-gh-workflows
Stock Github workflows that can be taken and edited in your projects.

Add workflows as appropriate to `.github/workflows` in your repo.

* `build-and-test.yml` - Build and test C#/.NET code before merging to `main`
* `label.yml` - Add labels to describe PRs
* `release-to-nuget.yml` - Release a C#/.NET package to the Nuget package index
* `release-to-docker-hub-unstable.yml` - Release an image of a C#/.NET app to Docker Hub, tagged with the SHA of the latest merge commit to `main`. Runs on merge to `main`
* `release-nextjs-to-az-appservice.yml` - Release a Next.js frontend app to Azure App Service on merges to `main`.
