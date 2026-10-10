# kuberoot

kuberoot builds Kubernetes distributions the way Buildroot builds embedded Linux. You describe a distribution in a profile, and the toolkit turns it into a bootable image with its own Linux kernel, an init that brings Kubernetes up, and nodes managed through the Kubernetes API itself. Everything above the base arrives as a package.

| Repository | |
|---|---|
| [kuberoot](https://github.com/kuberoot-dev/kuberoot) | the toolkit, and the distributions built with it: edge, router, hypervisor, ai, rt, iot, observability, workstation |
| [kubepkg](https://github.com/kuberoot-dev/kubepkg) | a package manager for any Kubernetes cluster, made for those who build platforms and distributions |
| [kubepkg-recipes](https://github.com/kuberoot-dev/kubepkg-recipes) | the package archive: recipes, a signed index, and each distribution's meta package |

The project is experimental and open to everyone who wants to build it with us: read [how to contribute](https://github.com/kuberoot-dev/.github/blob/main/CONTRIBUTING.md) and [how the project is run](https://github.com/kuberoot-dev/.github/blob/main/GOVERNANCE.md). Everything here is licensed under the Apache License 2.0.
