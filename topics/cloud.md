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

## Cloud native

### Container

- [ncopa/su-exec](https://github.com/ncopa/su-exec): switch user and group id and exec
- [tianon/gosu](https://github.com/tianon/gosu): Simple Go-based setuid+setgid+setgroups+exec
- [krallin/tini](https://github.com/krallin/tini): A tiny but valid `init` for containers
- [Yelp/dumb-init](https://github.com/Yelp/dumb-init): A minimal init system for Linux containers <https://engineeringblog.yelp.com/2016/01/dumb-init-an-init-for-docker.html>
- [kata-containers/kata-containers](https://github.com/kata-containers/kata-containers): Kata Containers version 2.x repository. Kata Containers is an open source project and community working to build a standard implementation of lightweight Virtual Machines (VMs) that feel and perform like containers, but provide the workload isolation and security advantages of VMs. <https://katacontainers.io/ >
- [google/gvisor](https://github.com/google/gvisor): Application Kernel for Containers <https://gvisor.dev>
- 🌟 [google/cadvisor](https://github.com/google/cadvisor): Analyzes resource usage and performance characteristics of running containers.
- [GoogleContainerTools/distroless](https://github.com/GoogleContainerTools/distroless): 🥑 Language focused docker images, minus the operating system.
- [uber-go/automaxprocs](https://github.com/uber-go/automaxprocs): Automatically set GOMAXPROCS to match Linux container CPU quota. <https://godoc.org/go.uber.org/automaxprocs>
- [chainguard-images/images](https://github.com/chainguard-images/images): Public Chainguard Images <https://chainguard.dev/chainguard-images>
- [orsinium-labs/docked](https://github.com/orsinium-labs/docked): A friendly and safe alternative to Dockefile. Write Docker images using the full power of Python. <https://docked.orsinium.dev>
- [GoogleCloudPlatform/gcr-cleaner](https://github.com/GoogleCloudPlatform/gcr-cleaner): Delete untagged image refs in Google Container Registry or Artifact Registry
- [uber/kraken](https://github.com/uber/kraken): P2P Docker registry capable of distributing TBs of data in seconds
- 🌟 [FedericoPonzi/Horust](https://github.com/FedericoPonzi/Horust): Horust is a supervisor / init system written in rust and designed to run inside containers. <https://federicoponzi.github.io/Horust/>
- [nestybox/sysbox](https://github.com/nestybox/sysbox): An open-source, next-generation "runc" that empowers rootless containers to run workloads such as Systemd, Docker, Kubernetes, just like VMs.
- [sickcodes/Docker-OSX](https://github.com/sickcodes/Docker-OSX): Run macOS VM in a Docker! Run near native OSX-KVM in Docker! X11 Forwarding! CI/CD for OS X Security Research! Docker mac Containers. <https://hub.docker.com/r/sickcodes/docker-osx>
- [agoda-com/macOS-vz-kubelet](https://github.com/agoda-com/macOS-vz-kubelet): Run native macOS workloads on Kubernetes
  - [How We Integrated Native macOS Workloads with Kubernetes](https://medium.com/agoda-engineering/how-we-integrated-native-macos-workloads-with-kubernetes-b4d3c14881a0)
- 🌟 [slimtoolkit/slim](https://github.com/slimtoolkit/slim): Slim(toolkit): Don't change anything in your container image and minify it by up to 30x (and for compiled languages even more) making it secure too! (free and open source)
- 🌟 [jart/cosmopolitan](https://github.com/jart/cosmopolitan): build-once run-anywhere c library
  - alternative of musl for static libc runtime links
- [NilsIrl/dockerc](https://github.com/NilsIrl/dockerc): container image to single executable compiler
  - how big for the final binary?
- 🌟 [phusion/baseimage-docker](https://github.com/phusion/baseimage-docker): A minimal Ubuntu base image modified for Docker-friendliness <http://phusion.github.io/baseimage-docker/>
- [dockur/windows](https://github.com/dockur/windows): Windows inside a Docker container.
- [dockur/windows-arm](https://github.com/dockur/windows-arm): Windows for ARM in a Docker container.
- [dockur/macos](https://github.com/dockur/macos): macOS inside a Docker container.
- [jrz/container-shell](https://github.com/jrz/container-shell): Starts and attaches a sandboxed shell using docker with access to the current or project directory
- 🌟 [apple/container](https://github.com/apple/container): A tool for creating and running Linux containers using lightweight virtual machines on a Mac. It's written in Swift, and optimized for Apple silicon.
- [apple/containerization](https://github.com/apple/containerization): Containerization is a Swift package for running Linux containers on macOS.

#### Container ops

- [containrrr/watchtower](https://github.com/containrrr/watchtower): A process for automating Docker container base image updates. <https://containrrr.dev/watchtower>
- [containers/conmon](https://github.com/containers/conmon): An OCI container runtime monitor.
- [containers/skopeo](https://github.com/containers/skopeo): Work with remote images registries - retrieving information, images, signing content
- [wagoodman/dive](https://github.com/wagoodman/dive): A tool for exploring each layer in a docker image
- [jesseduffield/lazydocker](https://github.com/jesseduffield/lazydocker): The lazier way to manage everything docker
- [bcicen/ctop](https://github.com/bcicen/ctop): Top-like interface for container metrics <https://ctop.sh/>
- [containerd/stargz-snapshotter](https://github.com/containerd/stargz-snapshotter): Fast container image distribution plugin with lazy pulling <https://github.com/containerd/containerd/issues/3731>
- 🌟 [amir20/dozzle](https://github.com/amir20/dozzle): Realtime log viewer for docker containers. <https://dozzle.dev/>
- [louislam/dockge](https://github.com/louislam/dockge): A fancy, easy-to-use and reactive self-hosted docker compose.yaml stack-oriented manager <https://dockge.kuma.pet>
- [NilsIrl/dockerc](https://github.com/NilsIrl/dockerc): container image to single executable compiler
- [Joxit/docker-registry-ui](https://github.com/Joxit/docker-registry-ui): The simplest and most complete UI for your private registry <https://joxit.dev/docker-registry-ui/>
- 🌟 [klausmeyer/docker-registry-browser](https://github.com/klausmeyer/docker-registry-browser): 🐳 Web Interface for the Docker Registry HTTP API V2 written in Ruby on Rails. <https://hub.docker.com/r/klausmeyer/docker-registry-browser/>
- [composecraft/composecraft](https://github.com/composecraft/composecraft): Compose craft is a tool to help you manage, edit and share docker compose files in a GUI way.
- 🌟 [docker/docker-py](https://github.com/docker/docker-py): A Python library for the Docker Engine API <https://docker-py.readthedocs.io/>
- [crazy-max/diun](https://github.com/crazy-max/diun): Receive notifications when an image is updated on a Docker registry <https://crazymax.dev/diun/>
- [getwud/wud](https://github.com/getwud/wud): Keep your containers up-to-date! <https://getwud.github.io/wud/>
- [spegel-org/spegel](https://github.com/spegel-org/spegel): Stateless cluster local OCI registry mirror. <https://spegel.dev>
- [GoogleContainerTools/kaniko](https://github.com/GoogleContainerTools/kaniko): Build Container Images In Kubernetes

### OS

- [oasislinux/oasis](https://github.com/oasislinux/oasis): a small statically-linked linux system
- 🌟 [canonical/cloud-init](https://github.com/canonical/cloud-init): Official upstream for the cloud-init: cloud instance initialization <instance>
- 🌟 [ostreedev/ostree](https://github.com/ostreedev/ostree): Operating system and container binary deployment and upgrades <https://ostreedev.github.io/ostree/>
- 🌟 [systemd/mkosi](https://github.com/systemd/mkosi): 💽 Build Bespoke OS Images
- [uapi-group/specifications](https://github.com/uapi-group/specifications): UAPI Group Specifications <https://uapi-group.org/specifications/>
- [flatcar/coreos-cloudinit](https://github.com/flatcar/coreos-cloudinit): Simple configuration tool for Flatcar Container Linux <https://github.com/flatcar/flatcar/issues>

### Virtual Machines

- [canonical/multipass](https://github.com/canonical/multipass): Multipass orchestrates virtual Ubuntu instances <https://multipass.run>
- 🌟 [89luca89/distrobox](https://github.com/89luca89/distrobox): Use any linux distribution inside your terminal. Enable both backward and forward compatibility with software and freedom to use whatever distribution you’re more comfortable with. Mirror available at: https://gitlab.com/89luca89/distrobox <https://distrobox.it/>
  - [Arch Linux Wiki - Distrobox](https://wiki.archlinux.org/title/Distrobox)
- [hashicorp/vagrant](https://github.com/hashicorp/vagrant): Vagrant is a tool for building and distributing development environments. <https://www.vagrantup.com>
- [tteck/Proxmox](https://github.com/tteck/Proxmox): Proxmox VE Helper-Scripts <https://helper-scripts.com/>
- [hyperlight-dev/hyperlight](https://github.com/hyperlight-dev/hyperlight): Hyperlight is a lightweight Virtual Machine Manager (VMM) designed to be embedded within applications. It enables safe execution of untrusted code within micro virtual machines with very low latency and minimal overhead.
- [hyperlight-dev/hyperlight-wasm](https://github.com/hyperlight-dev/hyperlight-wasm): hyperlight-wasm is a rust library crate that enables Wasm Modules and components to be run inside lightweight Virtual Machine backed Sandbox. It is built on top of Hyperlight.
- [firecracker-microvm/firecracker-containerd](https://github.com/firecracker-microvm/firecracker-containerd): firecracker-containerd enables containerd to manage containers as Firecracker microVMs
- [harvester/harvester](https://github.com/harvester/harvester): Open source hyperconverged infrastructure (HCI) software <https://harvesterhci.io/>
  - developed from SUSE
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
- [cirruslabs/vetu](https://github.com/cirruslabs/vetu): Create, publish and virtualize ephemeral Linux VMs with ease
- [cirruslabs/tart](https://github.com/cirruslabs/tart): macOS and Linux VMs on Apple Silicon to use in CI and other automations <https://tart.run>
- [cirruslabs/orchard](https://github.com/cirruslabs/orchard): Orchestrator for running Tart Virtual Machines on a cluster of Apple Silicon devices

### Storage

- [kahing/goofys](https://github.com/kahing/goofys): a high-performance, POSIX-ish Amazon S3 file system written in Go
- [s3fs-fuse/s3fs-fuse](https://github.com/s3fs-fuse/s3fs-fuse): FUSE-based file system backed by Amazon S3
- [awslabs/mountpoint-s3](https://github.com/awslabs/mountpoint-s3): A simple, high-throughput file client for mounting an Amazon S3 bucket as a local file system.
- [drivendataorg/cloudpathlib](https://github.com/drivendataorg/cloudpathlib): Python pathlib-style classes for cloud storage services such as Amazon S3, Azure Blob Storage, and Google Cloud Storage. <https://cloudpathlib.drivendata.org>

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

### Tools

- [homeport/dyff](https://github.com/homeport/dyff): /ˈdʏf/ - diff tool for YAML files, and sometimes JSON
- [simonw/s3-credentials](https://github.com/simonw/s3-credentials): A tool for creating credentials for accessing S3 buckets <https://s3-credentials.readthedocs.io>

### Routing / Gateway

- [cristaloleg/awesome-load-balancing](https://github.com/cristaloleg/awesome-load-balancing): A curated list of awesome load balancers and proxies. Software, libraries, posts, talks.
- [gRPC Load Balancing | gRPC](https://grpc.io/blog/grpc-load-balancing): This post describes various load balancing scenarios seen when deploying gRPC. If you use gRPC with multiple backends, this document is for you.
- [traefik/traefik](https://github.com/traefik/traefik): The Cloud Native Application Proxy
- [metallb/metallb](https://github.com/metallb/metallb): A network load-balancer implementation for Kubernetes using standard routing protocols <https://metallb.universe.tf>
- Nginx
  - [NginxProxyManager/nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager): Docker container for managing Nginx proxy hosts with a simple, powerful interface <https://nginxproxymanager.com>
  - [digitalocean/nginxconfig.io](https://github.com/digitalocean/nginxconfig.io): ⚙️ NGINX config generator on steroids 💉 <https://do.co/nginxconfig>
  - [denji/nginx-tuning](https://github.com/denji/nginx-tuning): NGINX tuning for best performance <https://git.io/vSvsq>
  - [nginx/unit](https://github.com/nginx/unit): NGINX Unit - universal web app server - a lightweight and versatile open source server that simplifies the application stack by natively executing application code across eight different programming language runtimes. <https://unit.nginx.org>
  - [dvershinin/gixy](https://github.com/dvershinin/gixy): NGINX configuration static analyzer <https://gixy.getpagespeed.com>
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

### Cluster Management (or UIs)

- [lensapp/lens](https://github.com/lensapp/lens): Lens - The way the world runs Kubernetes <https://k8slens.dev>
- [pixie-io/pixie](https://github.com/pixie-io/pixie): Instant Kubernetes-Native Application Observability <https://px.dev>
- [derailed/k9s](https://github.com/derailed/k9s): 🐶 Kubernetes CLI To Manage Your Clusters In Style! <https://k9scli.io/>
- [aptakube/aptakube](https://github.com/aptakube/aptakube): Modern, lightweight and multi-cluster Kubernetes GUI. Available on Windows, macOS and Linux. <https://aptakube.com>
- [karmada-io/karmada](https://github.com/karmada-io/karmada): Open, Multi-Cloud, Multi-Cluster Kubernetes Orchestration <https://karmada.io>
- [komodorio/helm-dashboard](https://github.com/komodorio/helm-dashboard): The missing UI for Helm - visualize your releases
- [kubernetes/kubeadm](https://github.com/kubernetes/kubeadm): Aggregator for issues filed against kubeadm
- [vmware-tanzu/kubeapps](https://github.com/vmware-tanzu/kubeapps): A web-based UI for deploying and managing applications in Kubernetes clusters <https://kubeapps.dev>
- 🌟 [kubernetes-sigs/kubespray](https://github.com/kubernetes-sigs/kubespray): Deploy a Production Ready Kubernetes Cluster
- [KusionStack/karpor](https://github.com/KusionStack/karpor): Intelligence for Kubernetes. World's most promising Kubernetes Visualization Tool for Developer and Platform Engineering teams. <https://karpor-demo.kusionstack.io>

### CNI

- [cilium/hubble](https://github.com/cilium/hubble): Hubble - Network, Service & Security Observability for Kubernetes using eBPF
- [cilium/tetragon](https://github.com/cilium/tetragon): eBPF-based Security Observability and Runtime Enforcement <https://tetragon.io>

### Featured

- [kr8s-org/kr8s](https://github.com/kr8s-org/kr8s): A simple, extensible Python client library for Kubernetes that feels familiar for folks who already know how to use kubectl <https://kr8s.org>
- [kumahq/kuma](https://github.com/kumahq/kuma): 🐻 The multi-zone service mesh for containers, Kubernetes and VMs. Built with Envoy. CNCF Sandbox Project. <https://kuma.io/install>
- [kubernetes/autoscaler](https://github.com/kubernetes/autoscaler): Autoscaling components for Kubernetes
- [external-secrets/external-secrets](https://github.com/external-secrets/external-secrets): External Secrets Operator reads information from a third-party service like AWS Secrets Manager and automatically injects the values as Kubernetes Secrets. <https://external-secrets.io/main>
- [radius-project/radius](https://github.com/radius-project/radius): Radius is a cloud-native, portable application platform that makes app development easier for teams building cloud-native apps. <https://radapp.io>
- [openebs/lvm-localpv](https://github.com/openebs/lvm-localpv): CSI Driver for dynamic provisioning of Persistent Local Volumes for Kubernetes using LVM.
- [GoogleContainerTools/skaffold](https://github.com/GoogleContainerTools/skaffold): Easy and Repeatable Kubernetes Development <https://skaffold.dev/>
- [emberstack/kubernetes-reflector](https://github.com/emberstack/kubernetes-reflector): Custom Kubernetes controller that can be used to replicate secrets, configmaps and certificates.
- [knight42/krelay](https://github.com/knight42/krelay): A better alternative to `kubectl port-forward` that can forward TCP or UDP traffic to IP/Host which is accessible inside the cluster.
- [STRRL/cloudflare-tunnel-ingress-controller](https://github.com/STRRL/cloudflare-tunnel-ingress-controller): 🚀 Expose the website directly into the internet! The Kuberntes Ingress Controller based on Cloudflare Tunnel.
- [kyverno/kyverno](https://github.com/kyverno/kyverno): Kubernetes Native Policy Management <https://kyverno.io>
- [cloudtty/cloudtty](https://github.com/cloudtty/cloudtty): A Friendly Kubernetes CloudShell (Web Terminal) ! <https://cloudtty.github.io/cloudtty/>
- [Kubernetes WithOut Kubelet](https://kwok.sigs.k8s.io/): Kubernetes WithOut Kubelet. KWOK is a toolkit that enables setting up a cluster of thousands of Nodes in seconds. Under the scene, all Nodes are simulated to behave like real ones, so the overall approach employs a pretty low resource footprint that you can easily play around on your laptop.
- 🌟 [alibaba/kubeskoop](https://github.com/alibaba/kubeskoop): Network monitoring & diagnosis suite for Kubernetes <https://kubeskoop.io>
- [kubernetes-sigs/kustomize](https://github.com/kubernetes-sigs/kustomize): Customization of kubernetes YAML configurations
  - [dnaeon/kustomize-dot](https://github.com/dnaeon/kustomize-dot): CLI app and kustomize KRM Function plugin which renders a graph of Kubernetes resources and their origins
- [helmfile/helmfile](https://github.com/helmfile/helmfile): Declaratively deploy your Kubernetes manifests, Kustomize configs, and Charts as Helm releases. Generate all-in-one manifests for use with ArgoCD. <https://helmfile.readthedocs.io>
- 🌟 [kubernetes-sigs/krew](https://github.com/kubernetes-sigs/krew): 📦 Find and install kubectl plugins <https://krew.sigs.k8s.io>
- [squat/kilo](https://github.com/squat/kilo): Kilo is a multi-cloud network overlay built on WireGuard and designed for Kubernetes (k8s + wg = kg) <https://kilo.squat.ai>
- [k8gb-io/k8gb](https://github.com/k8gb-io/k8gb): A cloud native Kubernetes Global Balancer <https://www.k8gb.io>
- [kubewarden/kubewarden-controller](https://github.com/kubewarden/kubewarden-controller): Manage admission policies in your Kubernetes cluster with ease <https://kubewarden.io>
- [Kuadrant/kuadrant-operator](https://github.com/Kuadrant/kuadrant-operator): The Operator to install and manage the lifecycle of the Kuadrant components deployments. <https://kuadrant.io>
  - How to compare or combine with kong gateway?
  - [Kuadrant/authorino](https://github.com/Kuadrant/authorino): K8s-native AuthN/AuthZ service to protect your APIs.
- [kubewharf/godel-rescheduler](https://github.com/kubewharf/godel-rescheduler): Schedulers in large-scale Kubernetes (K8s) clusters, such as the Godel Scheduler, are often required to schedule a large number of Pods within a short period.

### Operators

- [The registry for Kubernetes Operators](https://operatorhub.io/)
- [flant/shell-operator](https://github.com/flant/shell-operator): Shell-operator is a tool for running event-driven scripts in a Kubernetes cluster <https://flant.github.io/shell-operator/>
- [nolar/kopf](https://github.com/nolar/kopf): A Python framework to write Kubernetes operators in just a few lines of code <https://kopf.readthedocs.io/>
- [inlets/inlets-operator](https://github.com/inlets/inlets-operator): Get public TCP LoadBalancers for local Kubernetes clusters <https://docs.inlets.dev/reference/inlets-operator>
- [operator-framework/operator-lifecycle-manager](https://github.com/operator-framework/operator-lifecycle-manager): A management framework for extending Kubernetes with Operators <https://olm.operatorframework.io>
- [prometheus-operator/kube-prometheus](https://github.com/prometheus-operator/kube-prometheus): Use Prometheus to monitor Kubernetes and applications running on Kubernetes <https://prometheus-operator.dev/>

### App framework

- [kedacore/keda](https://github.com/kedacore/keda): KEDA is a Kubernetes-based Event Driven Autoscaling component. It provides event driven scale for any container running in Kubernetes <https://keda.sh>
  - lead by Microsoft
- [knative/eventing](https://github.com/knative/eventing): Event-driven application platform for Kubernetes <https://knative.dev/docs/eventing>
  - lead by Google

### GPU

- [Project-HAMi/HAMi](https://github.com/Project-HAMi/HAMi): Heterogeneous AI Computing Virtualization Middleware <http://project-hami.io>
- [NVIDIA/KAI-Scheduler](https://github.com/NVIDIA/KAI-Scheduler): KAI Scheduler is an open source Kubernetes Native scheduler for AI workloads at large scale

### Utils

- [databus23/helm-diff](https://github.com/databus23/helm-diff): A helm plugin that shows a diff explaining what a helm upgrade would change
- [tommy351/kosko](https://github.com/tommy351/kosko): Organize Kubernetes manifests in JavaScript. <https://kosko.dev>
- [kubernetes/kompose](https://github.com/kubernetes/kompose): Convert Compose to Kubernetes <http://kompose.io>
- [yannh/kubeconform](https://github.com/yannh/kubeconform): A FAST Kubernetes manifests validator, with support for Custom Resources!
- [itaysk/kubectl-neat](https://github.com/itaysk/kubectl-neat): Clean up Kubernetes yaml and json output to make it readable
- [aquasecurity/trivy](https://github.com/aquasecurity/trivy): Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more <https://trivy.dev>
- [kubescape/kubescape](https://github.com/kubescape/kubescape): Kubescape is an open-source Kubernetes security platform for your IDE, CI/CD pipelines, and clusters. It includes risk analysis, security, compliance, and misconfiguration scanning, saving Kubernetes users and administrators precious time, effort, and resources. <https://kubescape.io>
- [FairwindsOps/polaris](https://github.com/FairwindsOps/polaris): Validation of best practices in your Kubernetes clusters <https://www.fairwinds.com/polaris>
- [openreports/reports-api](https://github.com/openreports/reports-api): OpenReports API (Kubernetes CRD) <https://openreports.io/>
- [anchore/syft](https://github.com/anchore/syft): CLI tool and library for generating a Software Bill of Materials from container images and filesystems

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

## Cloud Foundry

- [one2nc/cloudlens](https://github.com/one2nc/cloudlens): k9s like CLI for AWS <https://one2n.gitbook.io/docs/>
- [ubicloud/ubicloud](https://github.com/ubicloud/ubicloud): Open, free, and portable cloud. Elastic compute, block storage (non replicated), virtual networking, managed Postgres, and IAM services in public beta. <https://ubicloud.com>
- [Spot by NetApp](https://spot.io/)

## Infrastructure as Code

### Framework

- [pulumi/pulumi](https://github.com/pulumi/pulumi): Pulumi - Universal Infrastructure as Code. Your Cloud, Your Language, Your Way 🚀 <https://www.pulumi.com>
- [crossplane/crossplane](https://github.com/crossplane/crossplane): Cloud Native Control Planes <https://crossplane.io/>
- [Azure/bicep](https://github.com/Azure/bicep): Bicep is a declarative language for describing and deploying Azure resources
- Ansible
  - [ansible-community/awesome-ansible](https://github.com/ansible-community/awesome-ansible): Awesome Ansible List
  - 🌟 [ansible-community/ara](https://github.com/ansible-community/ara): ARA Records Ansible and makes it easier to understand and troubleshoot. <https://ara.recordsansible.org>
  - [prometheus-community/ansible](https://github.com/prometheus-community/ansible): Ansible Collection for Prometheus <https://prometheus-community.github.io/ansible/>
  - [ansible/ansible-navigator](https://github.com/ansible/ansible-navigator): A text-based user interface (TUI) for Ansible. <https://ansible.readthedocs.io/projects/navigator/>
  - [ansible/ansible-runner](https://github.com/ansible/ansible-runner): A tool and python library that helps when interfacing with Ansible directly or as part of another system whether that be through a container image interface, as a standalone tool, or as a Python module that can be imported. The goal is to provide a stable and consistent interface abstraction to Ansible.
  - [ansible/awx](https://github.com/ansible/awx): AWX provides a web-based user interface, REST API, and task engine built on top of Ansible. It is one of the upstream projects for Red Hat Ansible Automation Platform.
  - [haidaraM/ansible-playbook-grapher](https://github.com/haidaraM/ansible-playbook-grapher): A command line tool to create a graph representing your Ansible playbook tasks and roles
  - [willthames/ansible-inventory-grapher](https://github.com/willthames/ansible-inventory-grapher): No description, website, or topics provided.
  - 🌟 [semaphoreui/semaphore](https://github.com/semaphoreui/semaphore): Modern UI and powerful API for Ansible, Terraform, OpenTofu, PowerShell and other DevOps tools. <https://semaphoreui.com>
  - [sr.ht - ~cwt/ananta](https://sr.ht/~cwt/ananta/): command-line tool to execute commands on multiple remote hosts
  - [ansible/tox-ansible](https://github.com/ansible/tox-ansible): The tox-ansible plugin dynamically creates a full matrix of python interpreter and ansible-core version environments for running integration, sanity, and unit for an ansible collection both locally and in a Github action. tox virtual environments are leveraged for collection building, collection installation, dependency installation, and testing. <https://ansible.readthedocs.io/projects/tox-ansible/>
  - [ansible/test-playbooks](https://github.com/ansible/test-playbooks): playbook-tests
  - [ansible/pytest-ansible](https://github.com/ansible/pytest-ansible): A pytest plugin that enables the use of ansible in tests, enables the use of pytest as a collection unit test runner, and exposes molecule scenarios through a pytest fixture. <https://ansible.readthedocs.io/projects/pytest-ansible/>
  - [ansible/molecule](https://github.com/ansible/molecule): Molecule aids in the development and testing of Ansible content: collections, playbooks and roles <https://ansible.readthedocs.io/projects/molecule/>
  - [sky22333/ansible](https://github.com/sky22333/ansible): 轻量级，简单易用的 Ansible Web 管理面板，提供批量主机管理、命令执行、文件传输和 Web 终端等功能。
  - [lablabs/ansible-role-rke2](https://github.com/lablabs/ansible-role-rke2): Ansible Role to install RKE2 Kubernetes. <https://galaxy.ansible.com/ui/standalone/roles/lablabs/rke2/>
  - [serversideup/docker-ansible](https://github.com/serversideup/docker-ansible): ⚡️ Run Ansible anywhere with a lightweight and powerful Docker image. <https://hub.docker.com/r/serversideup/ansible>

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

## Utils

- [skyplane-project/skyplane](https://github.com/skyplane-project/skyplane): 🔥 Blazing fast bulk data transfers between any cloud 🔥 <https://skyplane.org>
- 🌟 [octodns/octodns](https://github.com/octodns/octodns): Tools for managing DNS across multiple providers
- [libdns/libdns](https://github.com/libdns/libdns): Core interfaces for universal DNS record manipulation across providers
- [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns): Configure external DNS servers (AWS Route53, Google CloudDNS and others) for Kubernetes Ingresses and Services
- [go-acme/lego](https://github.com/go-acme/lego): Let's Encrypt/ACME client and library written in Go <https://go-acme.github.io/lego/>
- [rclone/rclone](https://github.com/rclone/rclone): "rsync for cloud storage" - Google Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Wasabi, Google Cloud Storage, Yandex Files <https://rclone.org>
- [apache/libcloud](https://github.com/apache/libcloud): Apache Libcloud is a Python library which hides differences between different cloud provider APIs and allows you to manage different cloud resources through a unified and easy to use API. <https://libcloud.apache.org>
