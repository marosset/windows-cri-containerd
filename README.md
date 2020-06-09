
# Windows-CRI-ContainerD

![Nightly](https://github.com/marosset/windows-cri-containerd/workflows/Nightly/badge.svg?branch=master)

## Overview

This project uses GitHub actions to build nightly packages of [contianerd](https://github.com/containerd/containerd) and other required binaries from source for testing containerd on Windows with [aks-engine](https://github.com/Azure/aks-engine).

https://github.com/marosset/windows-cri-containerd/releases/download/nightly/windows-cri-containerd.zip is updated nightly and containers the following binaries:

- containerd.exe
- containerd-shim-runhcs-v1.exe
- ctr.exe
