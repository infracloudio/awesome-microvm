# awesome-microvm

🎉 A curated list of awesome things related to Micro-VMs


# micro-vm: What & Why?
- [Micro VM Introduction](https://searchsecurity.techtarget.com/definition/micro-VM-micro-virtual-machine)

# Projects

- [Alioth](https://github.com/google/alioth)
- [Cloud Hypervisor](https://www.cloudhypervisor.org/)
	- [Virtainer guest agent](https://github.com/virtainer/virtainer-guest-agent) is a modern guest agent for x86_64 Linux and Windows virtual machines that speaks the QEMU Guest Agent protocol over vsock
- [Cocoon](https://github.com/cocoonstack/cocoon) is a lightweight MicroVM engine built on Cloud Hypervisor and Firecracker, with OCI/cloud-image support, snapshots and clones, CNI networking, and a Docker-like CLI
	- [Cocoon Sandbox](https://github.com/cocoonstack/sandbox) builds fast MicroVM sandboxes for AI agents on top of Cocoon, with warm pools, golden snapshot clones, and vsock-only no-network mode
- [Kata Containers](https://github.com/kata-containers/kata-containers)
- [Firecracker](https://github.com/firecracker-microvm/firecracker) allows running and managing micro VMs
	- [Deep dive on Firecracker](https://lwn.net/Articles/775736/)
	- [ContainerD managed MicroVMs](https://github.com/firecracker-microvm/firecracker-containerd)
- [Flintlock](https://github.com/liquidmetal-dev/flintlock) is a streamlined service to manage the lifecycle of micro VMs
- [go-microvm](https://github.com/stacklok/go-microvm) Go framework for running OCI images as microVMs via [libkrun](https://github.com/containers/libkrun), with embedded runtime, rootfs management, and guest networking
- [NixOS microVMs](https://github.com/astro/microvm.nix)
- [Slim](https://github.com/ottomatica/slim/) allows using Dockerfiles to create micro VMs
	- [Slim tutorial](https://dev.to/chrisparnin/slim-create-a-micro-vm-from-a-dockerfile-21od)
- [Stratovirt](https://github.com/openeuler-mirror/stratovirt)
- [Hyperlight](https://github.com/hyperlight-dev/hyperlight) is a lightweight Virtual Machine Manager designed to be embedded within applications
- [Mitos](https://github.com/mitos-run/mitos) is a Kubernetes-native runtime that live copy-on-write forks a running Firecracker microVM into N isolated, self-hostable sandboxes for AI agents
- [smolvm](https://github.com/smol-machines/smolvm) is a portable microVM manager built on [libkrun](https://github.com/containers/libkrun) that runs OCI images as VMs on Linux (KVM) and macOS (HVF), and can copy-on-write fork a running VM (memory + disk) in ~150ms for AI-agent sandboxes

# Posts

- [Kubernetes and Virtual Machines](https://tech.paulcz.net/blog/future-of-kubernetes-is-virtual-machines/)
- [Exploring why containers and MivroVMs together in context of orchestration](https://www.infoq.com/articles/containers-hypervisors-2019/)

# Demos

- [Using Virtual Kubelet and Ignite together](https://github.com/chanwit/vkignite)

- [A chef cookbok which uses Ignite to launch MicroVMs](https://github.com/begleybrothers/ignite.chef)

# Talks/Videos

- [Introduction and hands on demo of Firecracker](https://www.youtube.com/watch?v=JU-zp1dTC58)
- [GoTo 2019 - Secure and Fast microVM](https://www.youtube.com/watch?v=oKKOBsqQndY)
