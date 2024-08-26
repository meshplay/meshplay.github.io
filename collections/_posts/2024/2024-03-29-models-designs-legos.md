---
title: Lego Bricks and Lego Instructions
subheading: Comparing Meshplay Models and Meshplay Designs
date: 2024-03-29
author_contributor: Lee Calcote
categories: 
  - Meshplay
permalink: /blog/lego-bricks-and-lego-instructions
featured-image: /assets/images/posts/2024-03-29-models-designs-legos/five-legos.png
---

In Meshplay, two key concepts play a pivotal role in managing infrastructure and deployments: Meshplay Models and Meshplay Designs. Understanding their difference and their similarities will greatly increase your benefit from these two powerful, systems management paradigms.

## Meshplay Models

<a href="https://meshplay.github.io/docs/concepts/logical/models" target="_blank">Meshplay Models</a> represent the fundamental building blocks of your infrastructure. Think of them as blueprints or templates that define the structure, components, and configurations of your deployments. These models encapsulate everything from network configurations to service definitions, making them essential for consistent and scalable deployments across environments.

## Meshplay Designs

On the other hand, <a href="https://meshplay.github.io/docs/concepts/logical/designs" target="_blank">Meshplay Designs</a> are the practical implementations based on Meshplay Models. They represent declarations of your infrastructure deployments, customized according to specific use cases, environments, and requirements. Meshplay Designs allow you to create, manage, and deploy complex architectures seamlessly, leveraging the power and flexibility of Meshplay Models as their foundation.


## Meshplay Models (similar to Lego bricks)

Meshplay Models are packages that contain infrastructure components with specific properties and functionalities. (e.g., standard bricks, window pieces, wheels). Models and their Components cannot be directly used to build something complete on their own, but are standardized and reused across different Lego sets (instructions).


- **Definition:** Building blocks for infrastructure definition.
- **Focus:** Describe how to manage specific infrastructure types and their interactions.
- **Content:** Define properties, capabilities, and relationships for infrastructure components.
- **Usability:** Not directly deployable, but used as building blocks within Designs.
- **Sharing:** Can be packaged and shared for others to use in their Designs.

<img alt="Meshplay Catalog" src="/assets/images/posts/2024-03-29-models-designs-legos/five-legos-nobg.png" width="100%" />
Meshplay Models are like the individual Lego bricks - they define the building blocks for infrastructure with specific characteristics.

## Meshplay Designs (similar to Lego instructions)

Meshplay Designs provide a collaborative blueprint for building a specific model using Lego bricks (Meshplay Models). Designs define the structure and placement of the bricks to achieve the desired outcome. Desan be shared, versioned, and used as reference for building the same model.
In essence:

- **Definition:** Collaborative documents for infrastructure and application deployment.
- **Focus:** Describe the desired state of infrastructure for a specific deployment.
- **Content:** Use components (based on Models) and relationships to define your infrastructure.
- **Usability:** Designs are the deployable unit in Meshplay.
- **Sharing:** Can be exported, versioned, shared, and published for reuse by others.


<img alt="Meshplay Catalog" src="/assets/images/posts/2024-03-29-models-designs-legos/five-instructions.png" style="border: 0px; width: 179px; height: 300px; margin: 0px; float: right;" />
Meshplay Designs are like the Lego instructions - they use Models (like bricks) to lay out the specific infrastructure deployment plan.

**Analogy:** Think of Models as Lego bricks (defining types of pieces) and Designs as Lego instructions (defining how to build something specific). In summary, Meshplay Models serve as the theoretical frameworks, while Meshplay Designs translate these frameworks into tangible deployments, enabling you to design, deploy, and manage your infrastructure efficiently within the cloud and cloud native ecosystem.