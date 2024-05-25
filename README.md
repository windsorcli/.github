# Windsor Blueprints

Welcome to the Windsor Blueprints project! We’re here to help you accelerate your Cloud Native journey. This is a grassroots, community-first project. Do you care about open source, privacy, security, and digital liberty? Help us build this!

## What are blueprints?

Conceptually, you can think of blueprints as the patterns and tools you need to effortlessly build and operate your own private cloud, on your own terms.

Technically, a blueprint is a turn-key collection of Terraform modules, Kubernetes manifests, and Helm charts. They work in harmony with Flux controllers for “GitOps” style management, helping you quickly stand up feature-rich, easy-to-use compute clusters on the cloud, bare metal, or both. This project leverages Sidero Labs’ Talos operating system as its base OS, and we encourage checking out (and paying for) their Omni service.

We believe you don’t have to be a computer genius to build with blueprints. We’re also happy to help you on your journey, so come join the community!

## Who is this for?

There are two audiences for blueprints. If you’re a tinkerer or hobbyist working on a home lab, we think this project is for you! You can stand up a secure, reliable cluster of NUCs, Raspberry Pis, or Jetson Nanos, including a fully-integrated observability suite and other cloud services, on a Saturday morning. Then, you can spend the rest of your weekend figuring out how to control your lights, automate your garden, or keep your family safe with your own home security system.

We also think this would be a great place to start if you’re trying to get a good idea off the ground. We see blueprints as a viable alternative to jumping directly to cloud providers. Much of what you can do on Amazon Web Services (AWS), along with a multitude of third-party SaaS providers, you can do on your own hardware with the right blueprints. You can start small with affordable on-prem hardware, “burst” to the cloud as your employee or customer base grows, and later shift some or all of your recurring cloud costs back to capital hardware expenditure. We believe this could have a big impact on the economics of how you run your business, but we encourage you to check our math.

## What’s in the box?

We like the monorepo ethos. The blueprints repository contains:

- Ansible roles for setting up a local development environment on macOS or Linux
- A CLI tool that facilitates a smooth multi-context developer & operator workflow
- A portfolio of Terraform modules and Kustomize components you will use to build your own blueprint
- The Blueprint Operator (Coming Soon)

Unless you’re contributing back to upstream, we don’t recommend that you fork or pull this repository. Instead, each important element of this project can be referenced from your own repository as versioned Ansible roles, Terraform modules, and Kustomize resources. By retaining common versions across each of these components, you can ensure a high degree of compatibility and upgradability across the toolchain.

To help you get started, we offer an initial Terraform module that will help you manage your blueprint repositories and source code.

## How can I help?

There are many ways to participate. The best place to start is by trying it out. Read through our docs, go through the initial setup, and let us know how it goes.

As with any open-source project, we welcome you to file issues and submit pull requests. We generally appreciate work to be done from our existing backlog, so if you have a good idea or feature you’d like to contribute, please begin by commenting on an existing issue or creating a new one!

Have you used blueprints to save on cloud spend or create something cool? We’d love your photos, stories, and whitepapers!
