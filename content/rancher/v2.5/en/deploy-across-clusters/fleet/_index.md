---
title: Fleet - GitOps at Scale
weight: 1
aliases:
  - /rancher/v2.x/en/deploy-across-clusters/fleet/
---

_Available as of Rancher v2.5_

Fleet is GitOps at scale. Fleet is designed to manage up to a million clusters. It's also lightweight enough that it works great for a [single cluster](https://fleet.rancher.io/single-cluster-install/) too, but it really shines when you get to a [large scale.](https://fleet.rancher.io/multi-cluster-install/) By large scale we mean either a lot of clusters, a lot of deployments, or a lot of teams in a single organization.

Fleet is a separate project from Rancher, and can be installed on any Kubernetes cluster with Helm.

- [Architecture](#architecture)
- [Accessing Fleet in the Rancher UI](#accessing-fleet-in-the-rancher-ui)
- [Windows Support](#windows-support)
- [GitHub Repository](#github-repository)
- [Using Fleet Behind a Proxy](#using-fleet-behind-a-proxy)
- [Documentation](#documentation)

# Architecture

For information about how Fleet works, see [this page.](./architecture)

# Accessing Fleet in the Rancher UI

Fleet comes preinstalled in Rancher v2.5. To access it, go to the **Cluster Explorer** in the Rancher UI. In the top left dropdown menu, click **Cluster Explorer > Continuous Delivery.** On this page, you can edit Kubernetes resources and cluster groups managed by Fleet.

# Windows Support

_Available as of v2.5.6_

For details on support for clusters with Windows nodes, see [this page.](./windows)


# GitHub Repository

The Fleet Helm charts are available [here.](https://github.com/rancher/fleet/releases/latest)


# Using Fleet Behind a Proxy

_Available as of v2.5.8_

For details on using Fleet behind a proxy, see [this page.](./proxy)

# Documentation

The Fleet documentation is at [https://fleet.rancher.io/.](https://fleet.rancher.io/)
