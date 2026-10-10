# kuberoot

kuberoot builds Kubernetes distributions the way Buildroot builds embedded Linux: a distribution is described in a profile, and the toolkit builds a bootable image with its own Linux kernel, an init that brings up Kubernetes, and a node managed through the Kubernetes API itself. Everything above the base is a package.

| Repository | What it is |
|---|---|
| [kuberoot](https://github.com/kuberoot-dev/kuberoot) | the toolkit and the distributions built with it: edge, router, hypervisor, ai, rt, iot |
| [kubepkg](https://github.com/kuberoot-dev/kubepkg) | a package manager for any Kubernetes cluster, built for people who make platforms and distributions |
| [kubepkg-recipes](https://github.com/kuberoot-dev/kubepkg-recipes) | the package archive: recipes, signed index, and the distributions' meta packages |

The project is experimental and open to contributors: see [how to contribute](https://github.com/kuberoot-dev/.github/blob/main/CONTRIBUTING.md) and [how the project is run](https://github.com/kuberoot-dev/.github/blob/main/GOVERNANCE.md). Everything is licensed under the Apache License 2.0.
