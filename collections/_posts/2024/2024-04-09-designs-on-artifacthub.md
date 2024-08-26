---
title: 📢 Meshplay Designs Now Supported on Artifact Hub!
subheading: Working with Meshplay Designs is easier than ever  
date: 2024-04-24
author_contributor: Chris Carrier, Lee Calcote
categories: 
  - Meshplay
  - OpenSource
permalink: /blog/designs-on-artifact-hub
featured-image: /assets/images/posts/2024-04-09-designs-on-artifacthub/meshplay-designs-on-artifact-hub-featured.png
---

As a proud contributor to the Meshplay project, I’m thrilled to announce that Artifact Hub has officially recognized Meshplay Designs as a native artifact kind. 🎉 Meshplay Designs allow you to create, manage, and deploy complex architectures seamlessly, which make them a great addition to the growing collection of Artifact Hub artifacts such as Helm charts, Argo templates, and <a href="https://artifacthub.io/docs/topics/repositories/" target="_blank">many more</a>.

<a href="https://artifacthub.io" target="_blank"><img alt="Artifact Hub Kinds" src="/assets/images/posts/2024-04-09-designs-on-artifacthub/meshplay-designs-on-artifact-hub.png" width="50%" align="right" /></a>

## Artifact Hub's first Meshplay Designs

[Meshplay Catalog](/catalog) is the first repository to have it's Meshplay Designs listed on Artifact Hub. Meshplay Catalog functions much like a cloud marketplace, providing a user-friendly interface for browsing, discovering, and sharing configurations and patterns for cloud native infrastructure.

Learn more about [Meshplay Catalog](https://meshplay.github.io/docs/concepts/catalog).

You can now browse Meshplay Designs in the [Artifact Hub search](https://artifacthub.io/packages/search?kind=24&sort=relevance&page=1).

## What Are Meshplay Designs?

Meshplay Designs provide a powerful way to represent and visualize cloud-native infrastructure. They offer a topological layout of Helm Charts, making it easier for contributors like us to understand the components within a chart and their relationships. Whether you’re a seasoned Kubernetes enthusiast or just diving into the containerized world, Meshplay Designs bring clarity and insight.

For more information on how Designs work in Meshplay visit the most recent <a href="/blog/lego-bricks-and-lego-instructions" target="_blank">blog post on the topic</a>.

## Getting Started

Ready to add your own Meshplay Designs on Artifact Hub? Add your Meshplay Designs repository to Artifact Hub by following the [repository setup guide](https://artifacthub.io/docs/topics/repositories/meshplay-designs/). At a high-level, you will need:

1. **Repository Hosting**: Meshplay Designs repositories should be hosted on GitHub, GitLab, or Bitbucket. The repository URL format is straightforward—just the path to your packages. No git hosting platform-specific parts needed!
2. **Repository Metadata**: A `artifacthub-repo.yml` file that describes the repository and its packages.
3. **Metadata Files**: Each Meshplay design file needs an adjoining `artifacthub-pkg.yml` metadata file to fully characterize your Meshplay design in a way in which Artifact Hub can understand.
4. **Official Documentation** See the [official Artifact Hub documentation](https://artifacthub.io/docs/topics/repositories/meshplay-designs/) for further details.

Once you’ve set up your repository, new versions and packages will be automatically indexed and listed in Artifact Hub.

### Roadmap

Our collaboration with Artifact Hub doesn’t stop here. There is a proposed integration of Meshplay Snapshots on the horizon. What does this mean? For every Helm Chart hosted on Artifact Hub, Meshplay will create a visual snapshot — a visual diagram that captures the essence of the Helm Chart’s components. Exciting, right?

Follow the progress of this set of features on GitHub:

- Expand Meshplay's Integration with Artifact Hub [#9966](https://github.com/meshplay/meshplay/issues/9966)

Making Meshplay Designs available through Artifact Hub is an important milestone and was only possible through excellent support from the Artifact Hub team. We hope that you enjoy using Artifact Hub even more now that Meshplay Designs are now available on Artifact Hub as a new artifact kind!