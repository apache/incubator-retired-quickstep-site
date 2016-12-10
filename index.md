---
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
# Introduction
Quickstep is a next-generation data processing platform that starts with an underlying relational kernel core. The key design philosophy is to ensure that these kernels - and compositions of these kernels - can exploit the full potential of the underlying hardware. Often this design principle is called running at 'bare-metal' speeds.

The general idea is to build into the DNA of the platform methods that fully exploit the common hardware that is available today,
including large main memories, fast on-die CPU caches, highly parallel multi-core CPUs, and NVRAM storage technologies.

For the hardware available in the future, we aim to co-design hardware and software primitives that will allow the data processing
kernels to work on increasing amounts of data economically - both from the raw performance perspective, and from the perspective of
the energy consumed by the data processing kernels and the applications running on the platform.

The current roadmap is to produce a platform that can run relational database applications using SQL as the interface. The longer-term roadmap is to cover a broader class of analytics.

# Interested?
Quickstep currently runs on a single node and supports a SQL front-end. Quickstep aims to deliver high-performance and requires
no tuning and seamless setup. To get started, follow the [quickstart guide](https://github.com/apache/incubator-quickstep/blob/master/README.md)
