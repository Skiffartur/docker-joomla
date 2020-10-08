# About this Repo

This is the Git repo of the Docker [official image](https://docs.docker.com/docker-hub/official_repos/) for [joomla](https://registry.hub.docker.com/_/joomla/). See [the Docker Hub page](https://registry.hub.docker.com/_/joomla/) for the full readme on how to use this Docker image and for information regarding contributing and issues.

The full readme is generated over in [docker-library/docs](https://github.com/docker-library/docs), specifically in [docker-library/docs/joomla](https://github.com/docker-library/docs/tree/master/joomla).

See a change merged here that doesn't show up on the Docker Hub yet? Check [the "library/joomla" manifest file in the docker-library/official-images repo](https://github.com/docker-library/official-images/blob/master/library/joomla), especially [PRs with the "library/joomla" label on that repo](https://github.com/docker-library/official-images/labels/library%2Fjoomla). For more information about the official images process, see the [docker-library/official-images readme](https://github.com/docker-library/official-images/blob/master/README.md).

---

-	[Travis CI:  
	![build status badge](https://img.shields.io/travis/joomla-docker/docker-joomla/master.svg)](https://travis-ci.org/joomla-docker/docker-joomla/branches)

<!-- THIS FILE IS GENERATED BY https://github.com/docker-library/docs/blob/master/generate-repo-stub-readme.sh -->

# How to update the official docker-library/official-images repo

- [Since this Discussion with docker](https://github.com/docker-library/official-images/pull/8842#issuecomment-705099610) the @docker-library-bot has access to the [joomla-docker/official-images](https://github.com/joomla-docker/official-images)
- That bot [runs every six hours](https://github.com/docker-library/official-images/pull/8842#issuecomment-705099610) over the changes from this repo and prepares an branch to update the offical repo.
- So after a PR is merged here someone with write access to [joomla-docker/official-images](https://github.com/joomla-docker/official-images) can send a PR against the official repo.
- Such a user can use this link: https://github.com/docker-library/official-images/compare/master...joomla-docker:joomla that should already include all the changes required as well as the changelog as generated by the @docker-library-bot
- Please us that link to open the PR against the main repo [docker-library/official-images](https://github.com/docker-library/official-images).
