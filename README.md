# forever-benchmark-moby

Moby's development image (moby/moby's Dockerfile, its default target) built
at a given upstream commit, as [Depot's benchmark](https://github.com/depot/benchmark-moby)
builds it: with Docker's BuildKit on the runner (its cache in GitHub's), and
with Forever's image builder (the runner its client, through a bridge that
speaks BuildKit's API). Depot's times for the same commits are in its runs.

A temporary repository: it goes once the comparison is made.
