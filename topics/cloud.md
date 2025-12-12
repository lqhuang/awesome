# Cloud

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?theme=dark&i=docker,kubernetes,cloudflare,aws,workers">
  <img alt="docker,kubernetes,cloudflare,aws,workers" src="https://skillicons.dev/icons?theme=light&i=docker,kubernetes,cloudflare,aws,workers">
</picture>

## Resources

- [lonegunmanb/introduction-terraform](https://github.com/lonegunmanb/introduction-terraform): Introduction to terraform <https://lonegunmanb.github.io/introduction-terraform>
- [shuaibiyy/awesome-terraform](https://github.com/shuaibiyy/awesome-terraform): Curated list of resources on HashiCorp's Terraform
- [huataihuang/cloud-atlas](https://github.com/huataihuang/cloud-atlas): 云计算指南 <https://cloud-atlas.readthedocs.io>
- [veggiemonk/awesome-docker](https://github.com/veggiemonk/awesome-docker): 🐳 A curated list of Docker resources and projects <https://awesome-docker.netlify.app>
- [ramitsurana/awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes): A curated list for awesome kubernetes sources 🚢🎉 <https://ramitsurana.github.io/awesome-kubernetes>
- [yeasy/docker_practice](https://github.com/yeasy/docker_practice): Learn and understand Docker&Container technologies, with real DevOps practice! (in Chinese)
- [castrojo/awesome-immutable](https://github.com/castrojo/awesome-immutable): A list of resources for people who want to investigate image-based Linux desktops <https://castrojo.github.io/awesome-immutable/>
- [cloudcommunity/Free-Certifications](https://github.com/cloudcommunity/Free-Certifications): A curated list of free courses & certifications. <https://cloudstudy.net>
- [cloudcommunity/Free-Hosting](https://github.com/cloudcommunity/Free-Hosting): Overview of free hosting offers, incl. compute hosting, app hosting, databases, serverless etc. <https://cloudstudy.net>
- [cloudcommunity/Cloud-Free-Tier-Comparison](https://github.com/cloudcommunity/Cloud-Free-Tier-Comparison): Comparing the free tier offers of the major cloud providers like AWS, Azure, GCP, Oracle etc. <https://cloudstudy.net>
- [learnk8s](https://learnk8s.io/): Kubernetes training for engineers. Develop the knowledge and skills to get the most out of Kubernetes with hands-on online courses and instructor-led classes.
- [virtual-kubelet/systemk](https://github.com/virtual-kubelet/systemk): Systemk is a systemd backend for the virtual-kubelet. Instead of starting containers, you start systemd units.
  - Interesting idea that manipulating systemd units like containers
- 🌟 [GetDeploying](https://getdeploying.com/): Compare cloud providers for your next project
- [Hypervisor in 1,000 Lines](https://1000hv.seiya.me/en/): Write your first hypervisor from scratch, in 1K LoC.
- [CDN Performance Analytics & Comparison](https://www.cdnperf.com/)

## Cloud native

### Container

#### Runtime

- [google/gvisor](https://github.com/google/gvisor): Application Kernel for Containers <https://gvisor.dev>
- [nestybox/sysbox](https://github.com/nestybox/sysbox): An open-source, next-generation "runc" that empowers rootless containers to run workloads such as Systemd, Docker, Kubernetes, just like VMs.
- [apple/container](https://github.com/apple/container): A tool for creating and running Linux containers using lightweight virtual machines on a Mac. It's written in Swift, and optimized for Apple silicon.
  - [apple/containerization](https://github.com/apple/containerization): Containerization is a Swift package for running Linux containers on macOS.
- 🌟 [passt](https://passt.top/passt/about/): Plug A Simple Socket Transport
  - passt and pasta unprivileged (rootless) user-mode networking for VMs and containers, replacement for slirp, slirp4netns, libslirp, integrates with qemu, libvirt, Podman, Kata Containers
- [containerd/nerdbox](https://github.com/containerd/nerdbox): containerd sandbox runtime using vms

#### Base images

- [GoogleContainerTools/distroless](https://github.com/GoogleContainerTools/distroless): 🥑 Language focused docker images, minus the operating system.
- [canonical/chisel](https://github.com/canonical/chisel): Chisel is a software tool for carving and cutting Debian packages!
  - Be able to distroless-like Ubuntu base image
- 🌟 [slimtoolkit/slim](https://github.com/slimtoolkit/slim): Slim(toolkit): Don't change anything in your container image and minify it by up to 30x (and for compiled languages even more) making it secure too! (free and open source)
- [chainguard-images/images](https://github.com/chainguard-images/images): Public Chainguard Images <https://chainguard.dev/chainguard-images>
- [bitnami/minideb](https://github.com/bitnami/minideb): A small image based on Debian designed for use in containers <https://bitnami.com>
- [phusion/baseimage-docker](https://github.com/phusion/baseimage-docker): A minimal Ubuntu base image modified for Docker-friendliness <http://phusion.github.io/baseimage-docker/>
- [phusion/passenger-docker](https://github.com/phusion/passenger-docker): Docker base images for Ruby, Python, Node.js and Meteor web apps
- [linuxserver/docker-baseimage-alpine](https://github.com/linuxserver/docker-baseimage-alpine): No description or website provided.
- [linuxserver/docker-baseimage-debian](https://github.com/linuxserver/docker-baseimage-debian): Debian Baseimages
- [linuxserver/docker-baseimage-ubuntu](https://github.com/linuxserver/docker-baseimage-ubuntu): No description or website provided.
- [debuerreotype/debuerreotype](https://github.com/debuerreotype/debuerreotype): reproducible, snapshot-based Debian rootfs builder
  - [debuerreotype/docker-debian-artifacts](https://github.com/debuerreotype/docker-debian-artifacts): Official builds of debuerreotype-generated Debian tarballs for use in Docker <https://docker.debian.net>
  - [ReproducibleInstalls - Debian Wiki](https://wiki.debian.org/ReproducibleInstalls)

#### Init systems

- [krallin/tini](https://github.com/krallin/tini): A tiny but valid `init` for containers
- [Yelp/dumb-init](https://github.com/Yelp/dumb-init): A minimal init system for Linux containers <https://engineeringblog.yelp.com/2016/01/dumb-init-an-init-for-docker.html>
- [openSUSE/catatonit](https://github.com/openSUSE/catatonit): A container init that is so simple it's effectively brain-dead.
- [g-pape/runit](https://github.com/g-pape/runit): a UNIX init scheme with service supervision <https://smarden.org/runit/>
- [skarnet/s6](https://github.com/skarnet/s6): The s6 supervision suite. <https://skarnet.org/software/s6/>
  - [skarnet/s6-rc](https://github.com/skarnet/s6-rc): A service manager for s6. <https://skarnet.org/software/s6-rc/>
  - [just-containers/s6-overlay](https://github.com/just-containers/s6-overlay): s6 overlay for containers (includes execline, s6-linux-utils & a custom init)
  - [just-containers/s6-overlay-helpers](https://github.com/just-containers/s6-overlay-helpers): Small binary utilities, specific to s6-overlay
- [FedericoPonzi/Horust](https://github.com/FedericoPonzi/Horust): Horust is a supervisor / init system written in rust and designed to run inside containers. <https://federicoponzi.github.io/Horust/>
- [bitbucket:tildeslash/monit](https://bitbucket.org/tildeslash/monit): Monit is an open source utility for managing and monitoring, processes, programs, files, directories and filesystems on a UNIX system.
  - [M/Monit Wiki | Configuration Examples](https://mmonit.com/wiki/Monit/ConfigurationExamples)
- [slicer69/sysvinit](https://github.com/slicer69/sysvinit): Classic init software for Linux

#### First class tools

- [ncopa/su-exec](https://github.com/ncopa/su-exec): switch user and group id and exec
- [tianon/gosu](https://github.com/tianon/gosu): Simple Go-based setuid+setgid+setgroups+exec
- [uber-go/automaxprocs](https://github.com/uber-go/automaxprocs): Automatically set GOMAXPROCS to match Linux container CPU quota. <https://godoc.org/go.uber.org/automaxprocs>
- [jrz/container-shell](https://github.com/jrz/container-shell): Starts and attaches a sandboxed shell using docker with access to the current or project directory
- [containrrr/watchtower](https://github.com/containrrr/watchtower): A process for automating Docker container base image updates. <https://containrrr.dev/watchtower>
- [simonw/alpine-edit](https://github.com/simonw/alpine-edit): Microsoft edit packaged as a Docker container to run on a Mac
  - `vim` is too big for striped container image, `edit` is a good alternative
- 🌟 [nicolaka/netshoot](https://github.com/nicolaka/netshoot): a Docker + Kubernetes network trouble-shooting swiss-army container

#### Registry

- [distribution/distribution](https://github.com/distribution/distribution): The toolkit to pack, ship, store, and deliver container content <https://distribution.github.io/distribution>
  - [registry | Docker Hub](https://hub.docker.com/_/registry): Distribution implementation for storing and distributing of container images and artifacts
- [uber/kraken](https://github.com/uber/kraken): P2P Docker registry capable of distributing TBs of data in seconds
- [spegel-org/spegel](https://github.com/spegel-org/spegel): Stateless cluster local OCI registry mirror. <https://spegel.dev>
- [dragonflyoss/dragonfly](https://github.com/dragonflyoss/dragonfly): Delivers efficient, stable, and secure data distribution and acceleration powered by P2P technology, with an optional content-addressable filesystem that accelerates OCI container launch. <https://d7y.io>
- [dragonflyoss/nydus](https://github.com/dragonflyoss/nydus): Nydus - the Dragonfly image service, providing fast, secure and easy access to container images. <https://nydus.dev/>
- [containers/skopeo](https://github.com/containers/skopeo): Work with remote images registries - retrieving information, images, signing content
- [quay/quay](https://github.com/quay/quay): Build, Store, and Distribute your Applications and Containers
- [rpardini/docker-registry-proxy](https://github.com/rpardini/docker-registry-proxy): An HTTPS Proxy for Docker providing centralized configuration and caching of any registry (quay.io, DockerHub, registry.k8s.io, ghcr.io)
- 🌟 [Joxit/docker-registry-ui](https://github.com/Joxit/docker-registry-ui): The simplest and most complete UI for your private registry <https://joxit.dev/docker-registry-ui/>
- 🌟 [klausmeyer/docker-registry-browser](https://github.com/klausmeyer/docker-registry-browser): 🐳 Web Interface for the Docker Registry HTTP API V2 written in Ruby on Rails. <https://hub.docker.com/r/klausmeyer/docker-registry-browser/>
- [Quiq/registry-ui](https://github.com/Quiq/registry-ui): Web UI for Docker Registry
- [klausmeyer/docker-registry-browser](https://github.com/klausmeyer/docker-registry-browser): 🐳 Web Interface for the Docker Registry HTTP API V2 written in Ruby on Rails. <https://hub.docker.com/r/klausmeyer/docker-registry-browser/>

#### Container ops

- 🌟 [google/cadvisor](https://github.com/google/cadvisor): Analyzes resource usage and performance characteristics of running containers.
- [containers/conmon](https://github.com/containers/conmon): An OCI container runtime monitor.
- [wagoodman/dive](https://github.com/wagoodman/dive): A tool for exploring each layer in a docker image
- [bcicen/ctop](https://github.com/bcicen/ctop): Top-like interface for container metrics <https://ctop.sh/>
- [GoogleContainerTools/kaniko](https://github.com/GoogleContainerTools/kaniko): Build Container Images In Kubernetes
- 🌟 [psviderski/unregistry](https://github.com/psviderski/unregistry): Push docker images directly to remote servers without an external registry <https://uncloud.run>
- [GoogleCloudPlatform/gcr-cleaner](https://github.com/GoogleCloudPlatform/gcr-cleaner): Delete untagged image refs in Google Container Registry or Artifact Registry
- 🌟 [containerd/stargz-snapshotter](https://github.com/containerd/stargz-snapshotter): Fast container image distribution plugin with lazy pulling <https://github.com/containerd/containerd/issues/3731>
- Podman
  - [containers/prometheus-podman-exporter](https://github.com/containers/prometheus-podman-exporter): Prometheus exporter for podman environments exposing containers, pods, images, volumes and networks information.
  - [containers/containerimage-py](https://github.com/containers/containerimage-py): A python library for interacting with container images and container image registries
  - [containers/podman-tui](https://github.com/containers/podman-tui): Podman Terminal UI
- [docker/docker-py](https://github.com/docker/docker-py): A Python library for the Docker Engine API <https://docker-py.readthedocs.io/>
- 🌟 [orsinium-labs/docked](https://github.com/orsinium-labs/docked): A friendly and safe alternative to Dockefile. Write Docker images using the full power of Python. <https://docked.orsinium.dev>
  - Great idea for operating container images with Python scripts.
  - So sad that the project is not maintained for a long time.
- [getwud/wud](https://github.com/getwud/wud): Keep your containers up-to-date! <https://getwud.github.io/wud/>
- [crazy-max/diun](https://github.com/crazy-max/diun): Receive notifications when an image is updated on a Docker registry <https://crazymax.dev/diun/>
- [mag37/dockcheck](https://github.com/mag37/dockcheck): CLI tool to automate docker image updates. Selective, notifications, autoprune, no pre-pulling. <https://mag37.org>
- [log-forge/logforge](https://github.com/log-forge/logforge): All in one UI, for Docker. Real-time logs, Interactive terminals, Custom alerts/notifications/Automations, File system access. <https://www.logforge.dev/>
- [shadow-maint/shadow](https://github.com/shadow-maint/shadow): Upstream shadow tree
- 🌟 [hadolint/hadolint](https://github.com/hadolint/hadolint): Dockerfile linter, validate inline bash, written in Haskell
- 🌟 [goodwithtech/dockle](https://github.com/goodwithtech/dockle): Container Image Linter for Security, Helping build the Best-Practice Docker Image, Easy to start <https://containers.goodwith.tech/>
- [google/go-containerregistry](https://github.com/google/go-containerregistry): Go library and CLIs for working with container registries
  - Provide: `crane`, `gcrane`, `krane`, etc.

#### Filesystem

- [composefs/composefs](https://github.com/composefs/composefs): The reliability of disk images, the flexibility of files
- [containers/composefs-rs](https://github.com/containers/composefs-rs): Rust library for the composefs filesystem
- [erofs/docs](https://github.com/erofs/docs): EROFS documentation repo for https://erofs.docs.kernel.org <https://erofs.docs.kernel.org>

#### Interesting images

- [sickcodes/Docker-OSX](https://github.com/sickcodes/Docker-OSX): Run macOS VM in a Docker! Run near native OSX-KVM in Docker! X11 Forwarding! CI/CD for OS X Security Research! Docker mac Containers. <https://hub.docker.com/r/sickcodes/docker-osx>
- [dockur/windows](https://github.com/dockur/windows): Windows inside a Docker container.
- [dockur/windows-arm](https://github.com/dockur/windows-arm): Windows for ARM in a Docker container.
- [dockur/macos](https://github.com/dockur/macos): macOS inside a Docker container.
- [mviereck/x11docker](https://github.com/mviereck/x11docker): Run GUI applications and desktops in docker and podman containers. Focus on security.
- [linuxserver/docker-webtop](https://github.com/linuxserver/docker-webtop): Ubuntu, Alpine, Arch, and Fedora based Webtop images, Linux in a web browser supporting popular desktop environments.

#### Container status / Dashboard

- [jesseduffield/lazydocker](https://github.com/jesseduffield/lazydocker): The lazier way to manage everything docker
- [amir20/dozzle](https://github.com/amir20/dozzle): Realtime log viewer for docker containers. <https://dozzle.dev/>
- [louislam/dockge](https://github.com/louislam/dockge): A fancy, easy-to-use and reactive self-hosted docker compose.yaml stack-oriented manager <https://dockge.kuma.pet>
- [composecraft/composecraft](https://github.com/composecraft/composecraft): Compose craft is a tool to help you manage, edit and share docker compose files in a GUI way.
- [ofkm/arcane](https://github.com/ofkm/arcane): Modern Docker Management, Designed for Everyone <https://arcane.ofkm.dev>
- [NilsIrl/dockerc](https://github.com/NilsIrl/dockerc): container image to single executable compiler
  - how big for the final binary?

### OS

- [oasislinux/oasis](https://github.com/oasislinux/oasis): a small statically-linked linux system
- 🌟 [canonical/cloud-init](https://github.com/canonical/cloud-init): Official upstream for the cloud-init: cloud instance initialization <instance>
- 🌟 [ostreedev/ostree](https://github.com/ostreedev/ostree): Operating system and container binary deployment and upgrades <https://ostreedev.github.io/ostree/>
- 🌟 [systemd/mkosi](https://github.com/systemd/mkosi): 💽 Build Bespoke OS Images
- [uapi-group/specifications](https://github.com/uapi-group/specifications): UAPI Group Specifications <https://uapi-group.org/specifications/>
- [flatcar/coreos-cloudinit](https://github.com/flatcar/coreos-cloudinit): Simple configuration tool for Flatcar Container Linux <https://github.com/flatcar/flatcar/issues>
- [rancher/elemental](https://github.com/rancher/elemental): Elemental is a software stack enabling centralized, full cloud-native OS management with Kubernetes. <https://elemental.docs.rancher.com/>
- [hashicorp/packer](https://github.com/hashicorp/packer): Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. <https://developer.hashicorp.com/packer>
- [cobbler/cobbler](https://github.com/cobbler/cobbler): Cobbler is a versatile Linux deployment server <https://cobbler.github.io>
- [bin456789/reinstall](https://github.com/bin456789/reinstall): 一键 DD/重装脚本 (One-click reinstall OS on VPS)
- 🌟 [fossable/goldboot](https://github.com/fossable/goldboot): Build golden images with CI <https://www.fossable.org/projects/goldboot>
- [velvet-os/imagebuilder](https://github.com/velvet-os/imagebuilder): velvet os - simple script framework to build debian 13 trixie (in older versions also 12/bookworm, 11/bullseye and some ubuntu) bootable usb / sd card images for some arm and intel devices - lots of prebuilt images as well <https://velvet-os.github.io/>
  - GPL-3.0
- [endlessm/eos-image-builder](https://github.com/endlessm/eos-image-builder): Endless image builder <https://support.endlessos.org/en/deployment/image-builder>
  - GPL-2.0
- [osbuild/osbuild](https://github.com/osbuild/osbuild): Build-Pipelines for Operating System Artifacts <https://www.osbuild.org>
  - [osbuild/osbuild-composer](https://github.com/osbuild/osbuild-composer): An HTTP service for building bootable OS images. <https://www.osbuild.org>

### Virtual Machines

- [canonical/multipass](https://github.com/canonical/multipass): Multipass orchestrates virtual Ubuntu instances <https://multipass.run>
- 🌟 [89luca89/distrobox](https://github.com/89luca89/distrobox): Use any linux distribution inside your terminal. Enable both backward and forward compatibility with software and freedom to use whatever distribution you’re more comfortable with. Mirror available at: https://gitlab.com/89luca89/distrobox <https://distrobox.it/>
  - [Arch Linux Wiki - Distrobox](https://wiki.archlinux.org/title/Distrobox)
- [hashicorp/vagrant](https://github.com/hashicorp/vagrant): Vagrant is a tool for building and distributing development environments. <https://www.vagrantup.com>
- [hyperlight-dev/hyperlight](https://github.com/hyperlight-dev/hyperlight): Hyperlight is a lightweight Virtual Machine Manager (VMM) designed to be embedded within applications. It enables safe execution of untrusted code within micro virtual machines with very low latency and minimal overhead.
- [hyperlight-dev/hyperlight-wasm](https://github.com/hyperlight-dev/hyperlight-wasm): hyperlight-wasm is a rust library crate that enables Wasm Modules and components to be run inside lightweight Virtual Machine backed Sandbox. It is built on top of Hyperlight.
- [firecracker-microvm/firecracker-containerd](https://github.com/firecracker-microvm/firecracker-containerd): firecracker-containerd enables containerd to manage containers as Firecracker microVMs
- [GitLab · labs/Kwakky](https://gitlab.nic.cz/labs/kwakky): Kwakky runs virtual machines and manages networks between them in a clean and well automatable way.
  - I like the idea of cli provided by the project
  - Create a cluster `flock-sim create <path>`
  - Start a machine `flock-sim start <path> <name> [<deffile>]`
  - Shell to a machine `flock-sim shell <path> <name>`
  - Run a command at a machine `flock-sim cmd <path> <name> <args>`
  - Create a dummy network device `flock-sim dummy <path> <machname> <ifname>`
  - Create a point-to-point link `flock-sim ptp <path> <machnameA> <ifnameA> <machnameB> <ifnameB>`
  - Does anyone know similar projects with more mature ecosystem?
- [cloud-hypervisor/cloud-hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor): A Virtual Machine Monitor for modern Cloud workloads. Features include CPU, memory and device hotplug, support for running Windows and Linux guests, device offload with vhost-user and a minimal compact footprint. Written in Rust with a strong focus on security. <https://www.cloudhypervisor.org>
- [kata-containers/kata-containers](https://github.com/kata-containers/kata-containers): Kata Containers version 2.x repository. Kata Containers is an open source project and community working to build a standard implementation of lightweight Virtual Machines (VMs) that feel and perform like containers, but provide the workload isolation and security advantages of VMs. <https://katacontainers.io/ >
- [cirruslabs/vetu](https://github.com/cirruslabs/vetu): Create, publish and virtualize ephemeral Linux VMs with ease
- [cirruslabs/tart](https://github.com/cirruslabs/tart): macOS and Linux VMs on Apple Silicon to use in CI and other automations <https://tart.run>
- [cirruslabs/orchard](https://github.com/cirruslabs/orchard): Orchestrator for running Tart Virtual Machines on a cluster of Apple Silicon devices
- [google/crosvm](https://github.com/google/crosvm): The Chrome OS Virtual Machine Monitor - Mirror of https://chromium.googlesource.com/crosvm/crosvm/ <https://crosvm.dev/book/>
- [libriscv/kvmserver](https://github.com/libriscv/kvmserver): Fast per-request isolation for Linux executables with TinyKVM
- [ublue-os/bluefin](https://github.com/ublue-os/bluefin): The next generation Linux workstation, designed for reliability, performance, and sustainability. <https://projectbluefin.io>
- [alvistack/vagrant-debian](https://github.com/alvistack/vagrant-debian): Vagrant Box Packaging for Debian
- [agoda-com/macOS-vz-kubelet](https://github.com/agoda-com/macOS-vz-kubelet): Run native macOS workloads on Kubernetes
  - [How We Integrated Native macOS Workloads with Kubernetes](https://medium.com/agoda-engineering/how-we-integrated-native-macos-workloads-with-kubernetes-b4d3c14881a0)

Type 1 hypervisors

- [tteck/Proxmox](https://github.com/tteck/Proxmox): Proxmox VE Helper-Scripts <https://helper-scripts.com/>
- [MacRimi/ProxMenux](https://github.com/MacRimi/ProxMenux): ProxMenux An Interactive Menu for Proxmox VE Management
- [harvester/harvester](https://github.com/harvester/harvester): Open source hyperconverged infrastructure (HCI) software <https://harvesterhci.io/>
  - developed by SUSE
  - acutally a Kubernetes distribution with KubeVirt
  - but looks great
- [xcp-ng/xcp](https://github.com/xcp-ng/xcp): Entry point for issues and wiki. Also contains some scripts and sources. <https://xcp-ng.org>
- [community-scripts/ProxmoxVE](https://github.com/community-scripts/ProxmoxVE): Proxmox VE Helper-Scripts (Community Edition) <https://Helper-Scripts.com>
- [ccheshirecat/flint](https://github.com/ccheshirecat/flint): Lightweight tool for managing linux virtual machines

### Storage

- [kahing/goofys](https://github.com/kahing/goofys): a high-performance, POSIX-ish Amazon S3 file system written in Go
- [s3fs-fuse/s3fs-fuse](https://github.com/s3fs-fuse/s3fs-fuse): FUSE-based file system backed by Amazon S3
- [awslabs/mountpoint-s3](https://github.com/awslabs/mountpoint-s3): A simple, high-throughput file client for mounting an Amazon S3 bucket as a local file system.
- [drivendataorg/cloudpathlib](https://github.com/drivendataorg/cloudpathlib): Python pathlib-style classes for cloud storage services such as Amazon S3, Azure Blob Storage, and Google Cloud Storage. <https://cloudpathlib.drivendata.org>
- [s3gw-tech/s3gw](https://github.com/s3gw-tech/s3gw): Container able to run on a Kubernetes cluster, providing S3-compatible endpoints to applications. <https://s3gw.tech>
- [ebogdum/callfs](https://github.com/ebogdum/callfs): CallFS is an ultra-lightweight, high-performance REST API filesystem that provides precise Linux filesystem semantics over various backends including local filesystem, Amazon S3, and distributed peer networks
- [nohajc/anylinuxfs](https://github.com/nohajc/anylinuxfs): macOS: mount any linux-supported filesystem read/write using NFS and a microVM
- [Barre/ZeroFS](https://github.com/Barre/ZeroFS): ZeroFS - The Filesystem That Makes S3 your Primary Storage. ZeroFS is 9P/NFS/NBD on top of S3. <https://www.zerofs.net>
- [XTXMarkets/ternfs](https://github.com/XTXMarkets/ternfs): A distributed file system
- [cxl-micron-reskit/famfs](https://github.com/cxl-micron-reskit/famfs): This is the user space repo for famfs, the fabric-attached memory file system
- [scality/Zenko](https://github.com/scality/Zenko): Zenko is the open source multi-cloud data controller: own and keep control of your data on any cloud. <https://www.zenko.io>
- [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs): SeaweedFS is a fast distributed storage system for blobs, objects, files, and data lake, for billions of files! Blob store has O(1) disk seek, cloud tiering. Filer supports Cloud Drive, xDC replication, Kubernetes, POSIX FUSE mount, S3 API, S3 Gateway, Hadoop, WebDAV, encryption, Erasure Coding. Enterprise version is at seaweedfs.com. <https://seaweedfs.com>
- [yandex-cloud/geesefs](https://github.com/yandex-cloud/geesefs): Finally, a good FUSE FS implementation over S3
- [tigrisdata/tigrisfs](https://github.com/tigrisdata/tigrisfs): High performance FUSE filesystem for AI workloads with S3 compatible backends

### Serverless

- [zappa/Zappa](https://github.com/zappa/Zappa): Serverless Python
- [lagonapp/lagon](https://github.com/lagonapp/lagon): Deploy Serverless Functions at the Edge. Current status: Alpha <https://lagon.app/>
- [robertcepa/toucan-js](https://github.com/robertcepa/toucan-js): Cloudflare Workers client for Sentry
- [cloudflare/miniflare](https://github.com/cloudflare/miniflare): 🔥 Fully-local simulator for Cloudflare Workers
- [cloudflare/workers-rs](https://github.com/cloudflare/workers-rs): Write Cloudflare Workers in 100% Rust via WebAssembly
- [Logflare/logflare](https://github.com/Logflare/logflare): Never get surprised by a logging bill again. Centralized structured logging for Cloudflare, Vercel, Elixir and Javascript. <https://logflare.app>
- [SukkaW/dashflare](https://github.com/SukkaW/dashflare): An unofficial Cloudflare dashboard built on top of Cloudflare API. <https://dashflare.skk.moe>
- [DBOS](https://www.dbos.dev/): DBOS is a serverless platform that radically simplifies backend development in Python and TypeScript. Build 10x faster and scale to millions with a single click.
- 🌟 [unikraft/unikraft](https://github.com/unikraft/unikraft): Unikraft is an automated system for building specialized OSes known as unikernels. Unikraft can be configured to be POSIX-compliant. <http://unikraft.org/>

### Durable Functions / FaaS

- [earendil-works/absurd](https://github.com/earendil-works/absurd): An experiment in durability
  - [Absurd Workflows: Durable Execution With Just Postgres | Armin Ronacher's Thoughts and Writings](https://lucumr.pocoo.org/2025/11/3/absurd-workflows/): Durable execution with just postgres.

### Tools

- [homeport/dyff](https://github.com/homeport/dyff): /ˈdʏf/ - diff tool for YAML files, and sometimes JSON
- [simonw/s3-credentials](https://github.com/simonw/s3-credentials): A tool for creating credentials for accessing S3 buckets <https://s3-credentials.readthedocs.io>

### Routing / Gateway

- [cristaloleg/awesome-load-balancing](https://github.com/cristaloleg/awesome-load-balancing): A curated list of awesome load balancers and proxies. Software, libraries, posts, talks.
- [gRPC Load Balancing | gRPC](https://grpc.io/blog/grpc-load-balancing): This post describes various load balancing scenarios seen when deploying gRPC. If you use gRPC with multiple backends, this document is for you.
- [traefik/traefik](https://github.com/traefik/traefik): The Cloud Native Application Proxy
- [metallb/metallb](https://github.com/metallb/metallb): A network load-balancer implementation for Kubernetes using standard routing protocols <https://metallb.universe.tf>
- Nginx
  - [denji/nginx-tuning](https://github.com/denji/nginx-tuning): NGINX tuning for best performance <https://git.io/vSvsq>
  - [trimstray/nginx-admins-handbook](https://github.com/trimstray/nginx-admins-handbook): How to improve NGINX performance, security, and other important things.
  - [NginxProxyManager/nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager): Docker container for managing Nginx proxy hosts with a simple, powerful interface <https://nginxproxymanager.com>
  - [digitalocean/nginxconfig.io](https://github.com/digitalocean/nginxconfig.io): ⚙️ NGINX config generator on steroids 💉 <https://do.co/nginxconfig>
  - [nginx/unit](https://github.com/nginx/unit): NGINX Unit - universal web app server - a lightweight and versatile open source server that simplifies the application stack by natively executing application code across eight different programming language runtimes. <https://unit.nginx.org>
  - [dvershinin/gixy](https://github.com/dvershinin/gixy): NGINX configuration static analyzer <https://gixy.getpagespeed.com>
  - [nginx/nginx-acme](https://github.com/nginx/nginx-acme): An NGINX module with the implementation of the automatic certificate management (ACMEv2) protocol <https://nginx.org>
    - [NGINX Introduces Native Support for ACME Protocol  – NGINX Community Blog](https://blog.nginx.org/blog/native-support-for-acme-protocol): no description found
  - [google/ngx_brotli](https://github.com/google/ngx_brotli): NGINX module for Brotli compression
  - [0xJacky/nginx-ui](https://github.com/0xJacky/nginx-ui): Yet another WebUI for Nginx <https://nginxui.com>
- [facebookincubator/katran](https://github.com/facebookincubator/katran): A high performance layer 4 load balancer
- [projectcontour/contour](https://github.com/projectcontour/contour): Contour is a Kubernetes ingress controller using Envoy proxy. <https://projectcontour.io>
- [megaease/easegress](https://github.com/megaease/easegress): A Cloud Native traffic orchestration system <https://megaease.com/easegress/>
  - [megaease/easegress-portal](https://github.com/megaease/easegress-portal): Easegress official portal.
- [fastly/pushpin](https://github.com/fastly/pushpin): Proxy server for adding push to your API <https://pushpin.org>
- [cloudflare/pingora](https://github.com/cloudflare/pingora): A library for building fast, reliable and evolvable network services.
- [memorysafety/river](https://github.com/memorysafety/river): This repository is the future home of the River reverse proxy application, based on the pingora library from Cloudflare.
- [google/seesaw](https://github.com/google/seesaw): Seesaw v2 is a Linux Virtual Server (LVS) based load balancing platform.
- 🌟 [modal-labs/vprox](https://github.com/modal-labs/vprox): High-availability network proxy / VPN server, powered by WireGuard
- 🌟 [kgateway-dev/kgateway](https://github.com/kgateway-dev/kgateway): The Cloud-Native API Gateway and AI Gateway <https://kgateway.dev>
- [github/glb-director](https://github.com/github/glb-director): GitHub Load Balancer Director and supporting tooling.
- [envoyproxy/envoy](https://github.com/envoyproxy/envoy): Cloud-native high-performance edge/middle/service proxy <https://www.envoyproxy.io>
  - [envoyproxy/gateway](https://github.com/envoyproxy/gateway): Manages Envoy Proxy as a Standalone or Kubernetes-based Application Gateway <https://gateway.envoyproxy.io>

## Lightweight Tech Stack

- [internetarchive/hind](https://github.com/internetarchive/hind): Hashistack-IN-Docker (single container with nomad + consul + caddy)
- [theztd/startup-infra-docker](https://github.com/theztd/startup-infra-docker): Easy managable infrastructure for small devops teams or startups (based on ansible, nomadproject, docker, prometheus)
- [yarlson/ftl](https://github.com/yarlson/ftl): 🚀 FTL is a powerful deployment tool that simplifies the process of setting up servers and deploying applications.
- [Wowu/docker-rollout](https://github.com/Wowu/docker-rollout): 🚀 Zero Downtime Deployment for Docker Compose <https://github.com/Wowu/docker-rollout>
- [ServiceWeaver/weaver](https://github.com/ServiceWeaver/weaver): Programming framework for writing and deploying cloud applications. <https://serviceweaver.dev>
- [mrsked/mrsk](https://github.com/mrsked/mrsk): Deploy web apps anywhere. <https://mrsk.dev/>
- [Dokploy/dokploy](https://github.com/Dokploy/dokploy): Open Source Alternative to Vercel, Netlify and Heroku. <https://dokploy.com/>
- [MightyMoud/sidekick](https://github.com/MightyMoud/sidekick): Bare metal to production ready in mins; your own fly server on your VPS. <https://www.sidekickdeploy.com>
- [basecamp/kamal](https://github.com/basecamp/kamal): Deploy web apps anywhere. <https://kamal-deploy.org>
- [dstackai/dstack](https://github.com/dstackai/dstack): dstack is a lightweight, open-source alternative to Kubernetes & Slurm, simplifying AI container orchestration with multi-cloud & on-prem support. It natively supports NVIDIA, AMD, & TPU. <https://dstack.ai/docs>
- [taubyte/tau](https://github.com/taubyte/tau): Open source distributed Platform as a Service (PaaS). A self-hosted Vercel / Netlify / Cloudflare alternative. <https://tau.how>
- [beam-cloud/beta9](https://github.com/beam-cloud/beta9): The open-source serverless GPU container runtime. <https://docs.beta9.beam.cloud>
- [piku/piku](https://github.com/piku/piku): The tiniest PaaS you've ever seen. Piku allows you to do git push deployments to your own servers. <http://piku.github.io>
- [sst/sst](https://github.com/sst/sst): Build full-stack apps on your own infrastructure. <https://sst.dev>
- [psviderski/uncloud](https://github.com/psviderski/uncloud): A lightweight tool for deploying and managing containerised applications across a network of Docker hosts. Bridging the gap between Docker and Kubernetes ✨ <https://uncloud.run>
- [hunvreus/devpush](https://github.com/hunvreus/devpush): Like Vercel, but open source and for all languages. <https://devpu.sh>
- [mrusme/planor](https://github.com/mrusme/planor): The Cloud Aviator: TUI client for cloud services (AWS, Vultr, Heroku, Render.com, Fleek, ...) <https://xn--gckvb8fzb.com>
- [dokku/dokku](https://github.com/dokku/dokku): A docker-powered PaaS that helps you build and manage the lifecycle of applications <https://dokku.com>

## K8S

### Resources

- [lars-solberg/kubesec-diagram](https://github.com/lars-solberg/kubesec-diagram): This is a digram made to better understand and get an overview of kubernetes security.
- [rootsongjc/kubernetes-handbook](https://github.com/rootsongjc/kubernetes-handbook): Kubernetes 中文指南/云原生应用架构实战手册 <https://jimmysong.io/kubernetes-handbook>

### Distribution

- [rancher/rancher](https://github.com/rancher/rancher): Complete container management platform <http://rancher.com>
- 🌟 [k3s-io/k3s](https://github.com/k3s-io/k3s): Lightweight Kubernetes <https://k3s.io>
  - [k3d-io/k3d](https://github.com/k3d-io/k3d): Little helper to run CNCF's k3s in Docker <https://k3d.io/>
- 🌟 [rancher/rke2](https://github.com/rancher/rke2): RKE2, also known as RKE Government, is Rancher's next-generation Kubernetes distribution. <https://docs.rke2.io/>
- [k0sproject/k0s](https://github.com/k0sproject/k0s): k0s - The Zero Friction Kubernetes <https://docs.k0sproject.io>
- [klueska/kind-with-gpus-examples](https://github.com/klueska/kind-with-gpus-examples): No description, website, or topics provided.
- [alexellis/k3sup](https://github.com/alexellis/k3sup): bootstrap K3s over SSH in < 60s 🚀 <https://github.com/sponsors/alexellis>
- 🌟 [kubernetes-sigs/kubespray](https://github.com/kubernetes-sigs/kubespray): Deploy a Production Ready Kubernetes Cluster
- [alvistack/ansible-collection-kubernetes](https://github.com/alvistack/ansible-collection-kubernetes): Ansible collection for deploying Kubernetes

### Cluster Management (or UIs)

- [lensapp/lens](https://github.com/lensapp/lens): Lens - The way the world runs Kubernetes <https://k8slens.dev>
- [pixie-io/pixie](https://github.com/pixie-io/pixie): Instant Kubernetes-Native Application Observability <https://px.dev>
- [derailed/k9s](https://github.com/derailed/k9s): 🐶 Kubernetes CLI To Manage Your Clusters In Style! <https://k9scli.io/>
- [aptakube/aptakube](https://github.com/aptakube/aptakube): Modern, lightweight and multi-cluster Kubernetes GUI. Available on Windows, macOS and Linux. <https://aptakube.com>
- [karmada-io/karmada](https://github.com/karmada-io/karmada): Open, Multi-Cloud, Multi-Cluster Kubernetes Orchestration <https://karmada.io>
- [komodorio/helm-dashboard](https://github.com/komodorio/helm-dashboard): The missing UI for Helm - visualize your releases
- [kubernetes/kubeadm](https://github.com/kubernetes/kubeadm): Aggregator for issues filed against kubeadm
- [vmware-tanzu/kubeapps](https://github.com/vmware-tanzu/kubeapps): A web-based UI for deploying and managing applications in Kubernetes clusters <https://kubeapps.dev>
- [KusionStack/karpor](https://github.com/KusionStack/karpor): Intelligence for Kubernetes. World's most promising Kubernetes Visualization Tool for Developer and Platform Engineering teams. <https://karpor-demo.kusionstack.io>
- [kubernetes-sigs/headlamp](https://github.com/kubernetes-sigs/headlamp): A Kubernetes web UI that is fully-featured, user-friendly and extensible <https://headlamp.dev>
- 🌟 [kubernetes/dashboard](https://github.com/kubernetes/dashboard): General-purpose web UI for Kubernetes clusters
  - [int128/kauthproxy](https://github.com/int128/kauthproxy): Local authentication proxy for Kubernetes Dashboard (kubectl auth-proxy)
- [zxh326/kite](https://github.com/zxh326/kite): 🪁 A modern, lightweight Kubernetes dashboard <https://kite-demo.zzde.me/>

### kubectl plugins

- [knight42/krelay](https://github.com/knight42/krelay): A better alternative to `kubectl port-forward` that can forward TCP or UDP traffic to IP/Host which is accessible inside the cluster.
- 🌟 [kubernetes-sigs/krew](https://github.com/kubernetes-sigs/krew): 📦 Find and install kubectl plugins <https://krew.sigs.k8s.io>
  - [Kubectl plugins available · Krew](https://krew.sigs.k8s.io/plugins/)
- [ahmetb/kubectl-tree](https://github.com/ahmetb/kubectl-tree): kubectl plugin to browse Kubernetes object hierarchies as a tree 🎄 (star the repo if you are using)
- [guessi/kubectl-grep](https://github.com/guessi/kubectl-grep): Filter Kubernetes resources by matching their names
- [kubepug/kubepug](https://github.com/kubepug/kubepug): Kubernetes PreUpGrade (Checker) <https://kubepug.xyz/>
- [keisku/kubectl-explore](https://github.com/keisku/kubectl-explore): A better kubectl explain with the fuzzy finder
- [iovisor/kubectl-trace](https://github.com/iovisor/kubectl-trace): Schedule bpftrace programs on your kubernetes cluster using the kubectl
- [inspektor-gadget/inspektor-gadget](https://github.com/inspektor-gadget/inspektor-gadget): Inspektor Gadget is a set of tools and framework for data collection and system inspection on Kubernetes clusters and Linux hosts using eBPF <https://www.inspektor-gadget.io>
- [NimbleArchitect/kubectl-ice](https://github.com/NimbleArchitect/kubectl-ice): Kubectl-ice is an open-source tool for Kubernetes users to monitor and optimize container resource usage. Features include usage breakdowns for pods and containers, making scaling and optimization easier. The tool is compatible with major cloud providers and is actively developed by a community of contributors
- [yonahd/kor](https://github.com/yonahd/kor): A Golang Tool to discover unused Kubernetes Resources
- [vladimirvivien/ktop](https://github.com/vladimirvivien/ktop): A top-like tool for your Kubernetes clusters
- [kubernetes-sigs/kubectl-validate](https://github.com/kubernetes-sigs/kubectl-validate): No description, website, or topics provided.
- [microsoft/retina](https://github.com/microsoft/retina): eBPF distributed networking observability tool for Kubernetes <https://retina.sh>
- [robscott/kube-capacity](https://github.com/robscott/kube-capacity): A simple CLI that provides an overview of the resource requests, limits, and utilization in a Kubernetes cluster
- [kubectl ray](https://docs.ray.io/en/latest/cluster/kubernetes/user-guides/kubectl-plugin.html#kubectl-plugin)
- [utkuozdemir/pv-migrate](https://github.com/utkuozdemir/pv-migrate): CLI tool to easily migrate Kubernetes persistent volumes
- [ahmetb/kubectx](https://github.com/ahmetb/kubectx): Faster way to switch between clusters and namespaces in kubectl <https://kubectx.dev>
- [kvaps/kubectl-node-shell](https://github.com/kvaps/kubectl-node-shell): Exec into node via kubectl
- [zegl/kube-score](https://github.com/zegl/kube-score): Kubernetes object analysis with recommendations for improved reliability and security. kube-score actively prevents downtime and bugs in your Kubernetes YAML and Charts. Static code analysis for Kubernetes. <https://kube-score.com>
  - `brew install kube-score`
  - `kubectl krew install score`

### CNI

- [cilium/hubble](https://github.com/cilium/hubble): Hubble - Network, Service & Security Observability for Kubernetes using eBPF
- [cilium/tetragon](https://github.com/cilium/tetragon): eBPF-based Security Observability and Runtime Enforcement <https://tetragon.io>

### CSI

- [openebs/lvm-localpv](https://github.com/openebs/lvm-localpv): CSI Driver for dynamic provisioning of Persistent Local Volumes for Kubernetes using LVM.

### Featured

- [kr8s-org/kr8s](https://github.com/kr8s-org/kr8s): A simple, extensible Python client library for Kubernetes that feels familiar for folks who already know how to use kubectl <https://kr8s.org>
- [kumahq/kuma](https://github.com/kumahq/kuma): 🐻 The multi-zone service mesh for containers, Kubernetes and VMs. Built with Envoy. CNCF Sandbox Project. <https://kuma.io/install>
- [kubernetes/autoscaler](https://github.com/kubernetes/autoscaler): Autoscaling components for Kubernetes
- [STRRL/cloudflare-tunnel-ingress-controller](https://github.com/STRRL/cloudflare-tunnel-ingress-controller): 🚀 Expose the website directly into the internet! The Kuberntes Ingress Controller based on Cloudflare Tunnel.
- [cloudtty/cloudtty](https://github.com/cloudtty/cloudtty): A Friendly Kubernetes CloudShell (Web Terminal) ! <https://cloudtty.github.io/cloudtty/>
- [Kubernetes WithOut Kubelet](https://kwok.sigs.k8s.io/): Kubernetes WithOut Kubelet. KWOK is a toolkit that enables setting up a cluster of thousands of Nodes in seconds. Under the scene, all Nodes are simulated to behave like real ones, so the overall approach employs a pretty low resource footprint that you can easily play around on your laptop.
- 🌟 [alibaba/kubeskoop](https://github.com/alibaba/kubeskoop): Network monitoring & diagnosis suite for Kubernetes <https://kubeskoop.io>
- [squat/kilo](https://github.com/squat/kilo): Kilo is a multi-cloud network overlay built on WireGuard and designed for Kubernetes (k8s + wg = kg) <https://kilo.squat.ai>
- [k8gb-io/k8gb](https://github.com/k8gb-io/k8gb): A cloud native Kubernetes Global Balancer <https://www.k8gb.io>
- [kubewharf/godel-rescheduler](https://github.com/kubewharf/godel-rescheduler): Schedulers in large-scale Kubernetes (K8s) clusters, such as the Godel Scheduler, are often required to schedule a large number of Pods within a short period.
- [kubecfg/kubecfg](https://github.com/kubecfg/kubecfg): A tool for managing complex enterprise Kubernetes environments as code.
- [acrlabs/simkube](https://github.com/acrlabs/simkube): Record-and-replay Kubernetes simulator based on KWOK <https://simkube.dev>
- [kubernetes-sigs/karpenter](https://github.com/kubernetes-sigs/karpenter): Karpenter is a Kubernetes Node Autoscaler built for flexibility, performance, and simplicity.

### Operators

- [The registry for Kubernetes Operators](https://operatorhub.io/)
- [Kuadrant/kuadrant-operator](https://github.com/Kuadrant/kuadrant-operator): The Operator to install and manage the lifecycle of the Kuadrant components deployments. <https://kuadrant.io>
  - How to compare or combine with kong gateway?
  - [Kuadrant/authorino](https://github.com/Kuadrant/authorino): K8s-native AuthN/AuthZ service to protect your APIs.
- [flant/shell-operator](https://github.com/flant/shell-operator): Shell-operator is a tool for running event-driven scripts in a Kubernetes cluster <https://flant.github.io/shell-operator/>
- [nolar/kopf](https://github.com/nolar/kopf): A Python framework to write Kubernetes operators in just a few lines of code <https://kopf.readthedocs.io/>
- [inlets/inlets-operator](https://github.com/inlets/inlets-operator): Get public TCP LoadBalancers for local Kubernetes clusters <https://docs.inlets.dev/reference/inlets-operator>
- [operator-framework/operator-lifecycle-manager](https://github.com/operator-framework/operator-lifecycle-manager): A management framework for extending Kubernetes with Operators <https://olm.operatorframework.io>
- [prometheus-operator/kube-prometheus](https://github.com/prometheus-operator/kube-prometheus): Use Prometheus to monitor Kubernetes and applications running on Kubernetes <https://prometheus-operator.dev/>
- [sgl-project/ome](https://github.com/sgl-project/ome): OME is a Kubernetes operator for enterprise-grade management and serving of Large Language Models (LLMs) <http://docs.sglang.ai/ome/>

### Templates

- [GoogleContainerTools/skaffold](https://github.com/GoogleContainerTools/skaffold): Easy and Repeatable Kubernetes Development <https://skaffold.dev/>
- [kubernetes/kompose](https://github.com/kubernetes/kompose): Convert Compose to Kubernetes <http://kompose.io>
- [kubernetes-sigs/kustomize](https://github.com/kubernetes-sigs/kustomize): Customization of kubernetes YAML configurations
  - [dnaeon/kustomize-dot](https://github.com/dnaeon/kustomize-dot): CLI app and kustomize KRM Function plugin which renders a graph of Kubernetes resources and their origins
- [helmfile/helmfile](https://github.com/helmfile/helmfile): Declaratively deploy your Kubernetes manifests, Kustomize configs, and Charts as Helm releases. Generate all-in-one manifests for use with ArgoCD. <https://helmfile.readthedocs.io>

### App framework

- [kedacore/keda](https://github.com/kedacore/keda): KEDA is a Kubernetes-based Event Driven Autoscaling component. It provides event driven scale for any container running in Kubernetes <https://keda.sh>
  - lead by Microsoft
- [knative/eventing](https://github.com/knative/eventing): Event-driven application platform for Kubernetes <https://knative.dev/docs/eventing>
  - lead by Google
- [kubevela/kubevela](https://github.com/kubevela/kubevela): The Modern Application Platform. <https://kubevela.io>

### GPU

- [Project-HAMi/HAMi](https://github.com/Project-HAMi/HAMi): Heterogeneous AI Computing Virtualization Middleware <http://project-hami.io>
- [NVIDIA/KAI-Scheduler](https://github.com/NVIDIA/KAI-Scheduler): KAI Scheduler is an open source Kubernetes Native scheduler for AI workloads at large scale

### RBAC / Secrets

- [external-secrets/external-secrets](https://github.com/external-secrets/external-secrets): External Secrets Operator reads information from a third-party service like AWS Secrets Manager and automatically injects the values as Kubernetes Secrets. <https://external-secrets.io/main>
- [emberstack/kubernetes-reflector](https://github.com/emberstack/kubernetes-reflector): Custom Kubernetes controller that can be used to replicate secrets, configmaps and certificates.
- [kyverno/kyverno](https://github.com/kyverno/kyverno): Kubernetes Native Policy Management <https://kyverno.io>
- [kubewarden/kubewarden-controller](https://github.com/kubewarden/kubewarden-controller): Manage admission policies in your Kubernetes cluster with ease <https://kubewarden.io>
- [projectcapsule/capsule](https://github.com/projectcapsule/capsule): Multi-tenancy and policy-based framework for Kubernetes. <https://projectcapsule.dev/>

### Utils

- [databus23/helm-diff](https://github.com/databus23/helm-diff): A helm plugin that shows a diff explaining what a helm upgrade would change
- [tommy351/kosko](https://github.com/tommy351/kosko): Organize Kubernetes manifests in JavaScript. <https://kosko.dev>
- [yannh/kubeconform](https://github.com/yannh/kubeconform): A FAST Kubernetes manifests validator, with support for Custom Resources!
- [itaysk/kubectl-neat](https://github.com/itaysk/kubectl-neat): Clean up Kubernetes yaml and json output to make it readable
- [FairwindsOps/polaris](https://github.com/FairwindsOps/polaris): Validation of best practices in your Kubernetes clusters <https://www.fairwinds.com/polaris>
- [openreports/reports-api](https://github.com/openreports/reports-api): OpenReports API (Kubernetes CRD) <https://openreports.io/>
- [anchore/syft](https://github.com/anchore/syft): CLI tool and library for generating a Software Bill of Materials from container images and filesystems
- [telepresenceio/telepresence](https://github.com/telepresenceio/telepresence): Local development against a remote Kubernetes or OpenShift cluster <https://www.telepresence.io>
- [educates/educates-training-platform](https://github.com/educates/educates-training-platform): A platform for hosting interactive workshop environments in Kubernetes, or on top of a local container runtime. <https://educates.dev>

## Hashicorp

- [hashicorp/nomad-autoscaler](https://github.com/hashicorp/nomad-autoscaler): Nomad Autoscaler brings autoscaling to your Nomad workloads.
- [cosmonic/netreap](https://github.com/cosmonic/netreap): A Cilium controller implementation for Nomad <https://netreap.io>
- [terraform-linters/tflint](https://github.com/terraform-linters/tflint): A Pluggable Terraform Linter
- [lonegunmanb/avmfix](https://github.com/lonegunmanb/avmfix): No description, website, or topics provided.
  - [introduction-terraform](https://lonegunmanb.github.io/introduction-terraform/)
  - [packer-handbook](https://lonegunmanb.github.io/packer-handbook/)
  - [essential-vault](https://lonegunmanb.github.io/essential-vault/)
- [bridgecrewio/checkov](https://github.com/bridgecrewio/checkov): Prevent cloud misconfigurations and find vulnerabilities during build-time in infrastructure as code, container images and open source packages with Checkov by Bridgecrew. <https://www.checkov.io/>
  - [bridgecrewio/checkov-action](https://github.com/bridgecrewio/checkov-action): This GitHub Action runs Checkov against infrastructure-as-code, open source packages, container images, and CI/CD configurations to identify misconfigurations, vulnerabilities, and license compliance issues.
- [cloudflare/terraform-provider-cloudflare](https://github.com/cloudflare/terraform-provider-cloudflare): Cloudflare Terraform Provider <https://registry.terraform.io/providers/cloudflare/cloudflare>
- [inkdrop-org/inkdrop-visualizer](https://github.com/inkdrop-org/inkdrop-visualizer): Visualizes your Terraform <https://inkdrop.ai/>
- 🌟 [GoogleCloudPlatform/terraformer](https://github.com/GoogleCloudPlatform/terraformer): CLI tool to generate terraform files from existing infrastructure (reverse Terraform). Infrastructure to Code
- [tenable/terrascan](https://github.com/tenable/terrascan): Detect compliance and security violations across Infrastructure as Code to mitigate risk before provisioning cloud native infrastructure. <https://runterrascan.io>
- [mr-karan/nomcfg](https://github.com/mr-karan/nomcfg): https://nomcfg.mrkaran.dev/

## Bare-metal Infra / OpenStack

- [openstack/bifrost](https://github.com/openstack/bifrost): Ansible roles and playbooks to enable a standalone Ironic install. Mirror of code maintained at opendev.org. <https://opendev.org/openstack/bifrost>
- [openstack/openstack-ansible](https://github.com/openstack/openstack-ansible): Ansible playbooks for deploying OpenStack. Mirror of code maintained at opendev.org. <https://opendev.org/openstack/openstack-ansible>
- [openstack/ironic](https://github.com/openstack/ironic): A service for managing and provisioning Bare Metal servers. Mirror of code maintained at opendev.org. <https://opendev.org/openstack/ironic>
- [kubernetes-sigs/cluster-api](https://github.com/kubernetes-sigs/cluster-api): Home for Cluster API, a subproject of sig-cluster-lifecycle <https://cluster-api.sigs.k8s.io>
- [Metal³ - Metal Kubed](https://metal3.io/): Metal3.io aims to build on baremetal host provisioning technologies to provide a Kubernetes native API for managing bare metal hosts via a provisioning stack that is also running on Kubernetes.
  - [metal3-io/baremetal-operator](https://github.com/metal3-io/baremetal-operator): Bare metal host provisioning integration for Kubernetes
- [99cloud/lab-openstack](https://github.com/99cloud/lab-openstack): lab for OpenStack
- [vexxhost/atmosphere](https://github.com/vexxhost/atmosphere): Simple & easy private cloud platform featuring VMs, Kubernetes & bare-metal
- [OpenNebula/one](https://github.com/OpenNebula/one): The open source Cloud & Edge Computing Platform bringing real freedom to your Enterprise Cloud 🚀 <http://opennebula.io>

## Infrastructure less

- [Fly](https://fly.io): Deploy app servers close to your users
- [Railway](https://railway.app):Render is a unified cloud to build and run all your apps and websites with free TLS certificates, a global CDN, DDoS protection, private networks, and auto deploys from Git.
- [Modal](https://modal.com/): End-to-end cloud compute. Model inference, batch jobs, task queues, web apps and more. All without your own infrastructure.
- [Render](https://render.com): Render is a unified cloud to build and run all your apps and websites with free TLS certificates, a global CDN, DDoS protection, private networks, and auto deploys from Git.
- [Replicate](https://replicate.com/): Machine learning doesn’t need to be so hard. Run models in the cloud at scale.
  - good looking landing page 😆
- [Mosaic ML](https://www.mosaicml.com/): Generative AI For All. Easily train and deploy generative AI models on your data, in your secure environment.
  - I love this landing page, too 😅
- [Octoml](https://octoml.ai/): OctoAI is world-class compute infrastructure for tuning and running models that wow your users.
- [zeabur/zeabur](https://github.com/zeabur/zeabur): A platform that helps you deploy services with one click. <https://zeabur.com>
- [Flightcontrol](https://www.flightcontrol.dev/): Developer-first AWS infrastructure. Designed for teams that want the benefits of AWS without hiring devops.
- [Koyeb](https://www.koyeb.com/): Koyeb is a developer-friendly serverless platform. No ops, servers, or infrastructure management.
- [radius-project/radius](https://github.com/radius-project/radius): Radius is a cloud-native, portable application platform that makes app development easier for teams building cloud-native apps. <https://radapp.io>
  - k8s in the backend
- [czhu12/canine](https://github.com/czhu12/canine): Power of Kubernetes, Simplicity of Heroku <https://canine.sh>
  - k8s in the backend

## Cloud Foundry

- [one2nc/cloudlens](https://github.com/one2nc/cloudlens): k9s like CLI for AWS <https://one2n.gitbook.io/docs/>
- [ubicloud/ubicloud](https://github.com/ubicloud/ubicloud): Open, free, and portable cloud. Elastic compute, block storage (non replicated), virtual networking, managed Postgres, and IAM services in public beta. <https://ubicloud.com>
- [Spot by NetApp](https://spot.io/)

## Infrastructure as Code

### Framework

- [pulumi/pulumi](https://github.com/pulumi/pulumi): Pulumi - Universal Infrastructure as Code. Your Cloud, Your Language, Your Way 🚀 <https://www.pulumi.com>
- [crossplane/crossplane](https://github.com/crossplane/crossplane): Cloud Native Control Planes <https://crossplane.io/>
- [Azure/bicep](https://github.com/Azure/bicep): Bicep is a declarative language for describing and deploying Azure resources
- [alchemy-run/alchemy](https://github.com/alchemy-run/alchemy): Infrastructure as TypeScript <https://alchemy.run>

### Services

- [Argonaut](https://www.argonaut.dev/): End to end deployments to AWS and GCP in minutes - Collaborate on software infra with a fully managed Kubernetes PaaS, automated CI, and terraform with prebuilt AWS and GCP modules.
- [Gruntwork.io](https://www.gruntwork.io/): Your entire infrastructure. Defined as code. In about a day. We get you running on AWS with Docker and you get 100% of the code.

### Utils

- [servian/aws-auto-cleanup](https://github.com/servian/aws-auto-cleanup): Programmatically delete AWS resources based on an allowlist and time to live (TTL) settings
- [localstack/localstack](https://github.com/localstack/localstack): 💻 A fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline!
- [gruntwork-io/terragrunt](https://github.com/gruntwork-io/terragrunt): Terragrunt is a thin wrapper for Terraform that provides extra tools for working with multiple Terraform modules.
- [snyk/driftctl](https://github.com/snyk/driftctl): Detect, track and alert on infrastructure drift <https://driftctl.com>
- [someengineering/resoto](https://github.com/someengineering/resoto): Resoto creates an inventory of your cloud, provides deep visibility, and reacts to changes in your infrastructure. ⚡️ <https://resoto.com>
- [camptocamp/terraboard](https://github.com/camptocamp/terraboard): 🌍 📋 A web dashboard to inspect Terraform States <https://terraboard.io>
- [cycloidio/terracognita](https://github.com/cycloidio/terracognita): Reads from existing public and private cloud providers (reverse Terraform) and generates your infrastructure as code on Terraform configuration
- [aquasecurity/tfsec](https://github.com/aquasecurity/tfsec): Security scanner for your Terraform code <https://aquasecurity.github.io/tfsec>
- [picatz/terraform-google-nomad](https://github.com/picatz/terraform-google-nomad): 📗 Terraform Module for Nomad clusters with Consul on GCP
- [turbot/steampipe](https://github.com/turbot/steampipe): Use SQL to instantly query your cloud services (AWS, Azure, GCP and more). Open source CLI. No DB required. <https://steampipe.io>
- [klothoplatform/klotho](https://github.com/klothoplatform/klotho): Klotho - a CLI tool that transforms plain code into cloud native code <https://klo.dev>
- [finos/compliant-financial-infrastructure](https://github.com/finos/compliant-financial-infrastructure): Compliant Financial Infrastructure accelerates the development, deployment and adoption of services provided for AWS, Azure and Google in a way that meets existing regulatory and internal security controls.
- [idoavrah/terraform-tui](https://github.com/idoavrah/terraform-tui): Terraform textual UI
- 🌟 [tobilg/aws-iam-data](https://github.com/tobilg/aws-iam-data): This repository contains the full dataset of AWS IAM data (services, actions, resource types and conditions keys). It's updated on a daily basis at 4AM UTC. <https://www.awsiamdata.com>

### Pricing

- [bytebase/dbcost](https://github.com/bytebase/dbcost): The simple pricing calculator and comparison tool for the cloud databases. <https://www.dbcost.com>
- [uselotus/lotus](https://github.com/uselotus/lotus): Open Source Pricing & Packaging Infrastructure <https://www.uselotus.io>
- [juspay/hyperswitch](https://github.com/juspay/hyperswitch): An Open Source Financial Switch to make Payments fast, reliable and affordable
- [The Duckbill Group](https://www.duckbillgroup.com/): If your AWS bill keeps rising — and your blood pressure is doing the same — then you should be working with our team of cloud cost management experts.
- [opencost/opencost](https://github.com/opencost/opencost): Cost monitoring for Kubernetes workloads and cloud costs <http://opencost.io>
- [Vantage](https://www.vantage.sh/): Understand cloud costs and automate savings. See how much Vantage can reduce your bill by connecting accounts.

## Infra Security and Audit

- [quay/clair](https://github.com/quay/clair): Vulnerability Static Analysis for Containers <https://quay.github.io/clair/>
  - [quay/container-security-operator](https://github.com/quay/container-security-operator): Identify image vulnerabilities in Kubernetes pods
- 🌟 [aquasecurity/trivy](https://github.com/aquasecurity/trivy): Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more <https://trivy.dev>
- [aquasecurity/tracee](https://github.com/aquasecurity/tracee): Linux Runtime Security and Forensics using eBPF <https://aquasecurity.github.io/tracee/latest>
- [Runtime-Radar/runtime-radar](https://github.com/Runtime-Radar/runtime-radar): Runtime Radar is an open-source solution for monitoring runtime security events and responding to incidents in containerized environments.
- [someengineering/fixinventory](https://github.com/someengineering/fixinventory): Fix Inventory helps you identify and remove the most critical risks in AWS, GCP, Azure and Kubernetes. <https://fixinventory.org>
- [Esonhugh/My-Cloud-Security](https://github.com/Esonhugh/My-Cloud-Security): [ALL IN ONE] Everything that I shared to public about Cloud Security is here.
- [falcosecurity/falco](https://github.com/falcosecurity/falco): Cloud Native Runtime Security <https://falco.org>
- 🌟 [FogSecurity/yes3-scanner](https://github.com/FogSecurity/yes3-scanner): YES3 Scanner: S3 Security Scanner for Access and Ransomware Protection <http://fogsecurity.io>
- 🌟 [Checkmarx/kics](https://github.com/Checkmarx/kics): Find security vulnerabilities, compliance issues, and infrastructure misconfigurations early in the development cycle of your infrastructure-as-code with KICS by Checkmarx. <https://kics.io>
- [kubescape/kubescape](https://github.com/kubescape/kubescape): Kubescape is an open-source Kubernetes security platform for your IDE, CI/CD pipelines, and clusters. It includes risk analysis, security, compliance, and misconfiguration scanning, saving Kubernetes users and administrators precious time, effort, and resources. <https://kubescape.io>
- [OperantAI/woodpecker](https://github.com/OperantAI/woodpecker): Red Teaming for AI and Cloud <https://operant.ai>
- [buildsec/frsca](https://github.com/buildsec/frsca): Factory for Repeatable Secure Creation of Artifacts (aka FRSCA pronounced Fresca) aims to help secure the supply chain by securing build pipelines. <https://buildsec.github.io/frsca>

## Utils

- [skyplane-project/skyplane](https://github.com/skyplane-project/skyplane): 🔥 Blazing fast bulk data transfers between any cloud 🔥 <https://skyplane.org>
- 🌟 [octodns/octodns](https://github.com/octodns/octodns): Tools for managing DNS across multiple providers
- [libdns/libdns](https://github.com/libdns/libdns): Core interfaces for universal DNS record manipulation across providers
- [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns): Configure external DNS servers (AWS Route53, Google CloudDNS and others) for Kubernetes Ingresses and Services
- [go-acme/lego](https://github.com/go-acme/lego): Let's Encrypt/ACME client and library written in Go <https://go-acme.github.io/lego/>
- [rclone/rclone](https://github.com/rclone/rclone): "rsync for cloud storage" - Google Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Wasabi, Google Cloud Storage, Yandex Files <https://rclone.org>
- [apache/libcloud](https://github.com/apache/libcloud): Apache Libcloud is a Python library which hides differences between different cloud provider APIs and allows you to manage different cloud resources through a unified and easy to use API. <https://libcloud.apache.org>
- [apache/openwhisk](https://github.com/apache/openwhisk): Apache OpenWhisk is an open source serverless cloud platform <https://openwhisk.apache.org/>
  - Scala project 🤔
- [awslabs/soci-snapshotter](https://github.com/awslabs/soci-snapshotter): A containerd snapshotter plugin which enables standard OCI images to be lazily loaded without requiring a build-time conversion step.

  - The stargz-snapshotter implements a lazy image fetcher based on the eStargz custom image format, and the soci-snapshotter provides one based on the OCI specification for those who can’t or don’t want to convert images to a new format to support lazy distribution.

- [meshery/meshery](https://github.com/meshery/meshery): Meshery, the cloud native manager <https://meshery.io>
