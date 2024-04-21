# Cloud

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

## OS

- [oasislinux/oasis](https://github.com/oasislinux/oasis): a small statically-linked linux system
- [unikraft/unikraft](https://github.com/unikraft/unikraft): Unikraft is an automated system for building specialized OSes known as unikernels. Unikraft can be configured to be POSIX-compliant. <http://unikraft.org/>
- 🌟 [canonical/cloud-init](https://github.com/canonical/cloud-init): Official upstream for the cloud-init: cloud instance initialization <instance>
- 🌟 [ostreedev/ostree](https://github.com/ostreedev/ostree): Operating system and container binary deployment and upgrades <https://ostreedev.github.io/ostree/>
- 🌟 [systemd/mkosi](https://github.com/systemd/mkosi): 💽 Build Bespoke OS Images
- [uapi-group/specifications](https://github.com/uapi-group/specifications): UAPI Group Specifications <https://uapi-group.org/specifications/>
- [flatcar/coreos-cloudinit](https://github.com/flatcar/coreos-cloudinit): Simple configuration tool for Flatcar Container Linux <https://github.com/flatcar/flatcar/issues>

## Virtual Machines

- [canonical/multipass](https://github.com/canonical/multipass): Multipass orchestrates virtual Ubuntu instances <https://multipass.run>
- 🌟 [89luca89/distrobox](https://github.com/89luca89/distrobox): Use any linux distribution inside your terminal. Enable both backward and forward compatibility with software and freedom to use whatever distribution you’re more comfortable with. Mirror available at: https://gitlab.com/89luca89/distrobox <https://distrobox.it/>
  - [Arch Linux Wiki - Distrobox](https://wiki.archlinux.org/title/Distrobox)
- [hashicorp/vagrant](https://github.com/hashicorp/vagrant): Vagrant is a tool for building and distributing development environments. <https://www.vagrantup.com>
- [tteck/Proxmox](https://github.com/tteck/Proxmox): Proxmox VE Helper-Scripts <https://helper-scripts.com/>

## Container

- [ncopa/su-exec](https://github.com/ncopa/su-exec): switch user and group id and exec
- [tianon/gosu](https://github.com/tianon/gosu): Simple Go-based setuid+setgid+setgroups+exec
- [krallin/tini](https://github.com/krallin/tini): A tiny but valid `init` for containers
- [Yelp/dumb-init](https://github.com/Yelp/dumb-init): A minimal init system for Linux containers <https://engineeringblog.yelp.com/2016/01/dumb-init-an-init-for-docker.html>
- [containrrr/watchtower](https://github.com/containrrr/watchtower): A process for automating Docker container base image updates. <https://containrrr.dev/watchtower>
- [kata-containers/kata-containers](https://github.com/kata-containers/kata-containers): Kata Containers version 2.x repository. Kata Containers is an open source project and community working to build a standard implementation of lightweight Virtual Machines (VMs) that feel and perform like containers, but provide the workload isolation and security advantages of VMs. <https://katacontainers.io/ >
- [railwayapp/nixpacks](https://github.com/railwayapp/nixpacks): App source + Nix packages + Docker = Image <https://nixpacks.com>
- [google/gvisor](https://github.com/google/gvisor): Application Kernel for Containers <https://gvisor.dev>
- [google/cadvisor](https://github.com/google/cadvisor): Analyzes resource usage and performance characteristics of running containers.
- [GoogleContainerTools/distroless](https://github.com/GoogleContainerTools/distroless): 🥑 Language focused docker images, minus the operating system.
- [uber-go/automaxprocs](https://github.com/uber-go/automaxprocs): Automatically set GOMAXPROCS to match Linux container CPU quota. <https://godoc.org/go.uber.org/automaxprocs>
- [chainguard-images/images](https://github.com/chainguard-images/images): Public Chainguard Images <https://chainguard.dev/chainguard-images>
- [containers/conmon](https://github.com/containers/conmon): An OCI container runtime monitor.
- [orsinium-labs/docked](https://github.com/orsinium-labs/docked): A friendly and safe alternative to Dockefile. Write Docker images using the full power of Python. <https://docked.orsinium.dev>
- [GoogleCloudPlatform/gcr-cleaner](https://github.com/GoogleCloudPlatform/gcr-cleaner): Delete untagged image refs in Google Container Registry or Artifact Registry
- [uber/kraken](https://github.com/uber/kraken): P2P Docker registry capable of distributing TBs of data in seconds
- 🌟 [FedericoPonzi/Horust](https://github.com/FedericoPonzi/Horust): Horust is a supervisor / init system written in rust and designed to run inside containers. <https://federicoponzi.github.io/Horust/>
- [nestybox/sysbox](https://github.com/nestybox/sysbox): An open-source, next-generation "runc" that empowers rootless containers to run workloads such as Systemd, Docker, Kubernetes, just like VMs.
- [Wowu/docker-rollout](https://github.com/Wowu/docker-rollout): 🚀 Zero Downtime Deployment for Docker Compose <https://github.com/Wowu/docker-rollout>

### CLI

- [containers/skopeo](https://github.com/containers/skopeo): Work with remote images registries - retrieving information, images, signing content
- [jesseduffield/lazydocker](https://github.com/jesseduffield/lazydocker): The lazier way to manage everything docker
- [bcicen/ctop](https://github.com/bcicen/ctop): Top-like interface for container metrics <https://ctop.sh/>

## Routing

- [traefik/traefik](https://github.com/traefik/traefik): The Cloud Native Application Proxy
- [metallb/metallb](https://github.com/metallb/metallb): A network load-balancer implementation for Kubernetes using standard routing protocols <https://metallb.universe.tf>
- Nginx
  - [NginxProxyManager/nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager): Docker container for managing Nginx proxy hosts with a simple, powerful interface <https://nginxproxymanager.com>
  - [digitalocean/nginxconfig.io](https://github.com/digitalocean/nginxconfig.io): ⚙️ NGINX config generator on steroids 💉 <https://do.co/nginxconfig>
  - [denji/nginx-tuning](https://github.com/denji/nginx-tuning): NGINX tuning for best performance <https://git.io/vSvsq>
  - [nginx/unit](https://github.com/nginx/unit): NGINX Unit - universal web app server - a lightweight and versatile open source server that simplifies the application stack by natively executing application code across eight different programming language runtimes. <https://unit.nginx.org>
- [facebookincubator/katran](https://github.com/facebookincubator/katran): A high performance layer 4 load balancer
- [projectcontour/contour](https://github.com/projectcontour/contour): Contour is a Kubernetes ingress controller using Envoy proxy. <https://projectcontour.io>
- [megaease/easegress](https://github.com/megaease/easegress): A Cloud Native traffic orchestration system <https://megaease.com/easegress/>
  - [megaease/easegress-portal](https://github.com/megaease/easegress-portal): Easegress official portal.
- [fastly/pushpin](https://github.com/fastly/pushpin): Proxy server for adding push to your API <https://pushpin.org>
- [cloudflare/pingora](https://github.com/cloudflare/pingora): A library for building fast, reliable and evolvable network services.
- [memorysafety/river](https://github.com/memorysafety/river): This repository is the future home of the River reverse proxy application, based on the pingora library from Cloudflare.
- [google/seesaw](https://github.com/google/seesaw): Seesaw v2 is a Linux Virtual Server (LVS) based load balancing platform.

## Cloud native

- [cloudflare/miniflare](https://github.com/cloudflare/miniflare): 🔥 Fully-local simulator for Cloudflare Workers
- [drivendataorg/cloudpathlib](https://github.com/drivendataorg/cloudpathlib): Python pathlib-style classes for cloud storage services such as Amazon S3, Azure Blob Storage, and Google Cloud Storage. <https://cloudpathlib.drivendata.org>
- [zappa/Zappa](https://github.com/zappa/Zappa): Serverless Python
- [lagonapp/lagon](https://github.com/lagonapp/lagon): Deploy Serverless Functions at the Edge. Current status: Alpha <https://lagon.app/>
- [ServiceWeaver/weaver](https://github.com/ServiceWeaver/weaver): Programming framework for writing and deploying cloud applications. <https://serviceweaver.dev>
- [mrsked/mrsk](https://github.com/mrsked/mrsk): Deploy web apps anywhere. <https://mrsk.dev/>
- [s3fs-fuse/s3fs-fuse](https://github.com/s3fs-fuse/s3fs-fuse): FUSE-based file system backed by Amazon S3
- [buildpacks/pack](https://github.com/buildpacks/pack): CLI for building apps using Cloud Native Buildpacks <https://buildpacks.io>
- [pivotal/kpack](https://github.com/pivotal/kpack): Kubernetes Native Container Build Service
- [awslabs/mountpoint-s3](https://github.com/awslabs/mountpoint-s3): A simple, high-throughput file client for mounting an Amazon S3 bucket as a local file system.

## K8S

### Resources

- [rootsongjc/kubernetes-handbook](https://github.com/rootsongjc/kubernetes-handbook): Kubernetes 中文指南/云原生应用架构实战手册 <https://jimmysong.io/kubernetes-handbook>

### Distribution

- [rancher/rancher](https://github.com/rancher/rancher): Complete container management platform <http://rancher.com>
- 🌟 [k3s-io/k3s](https://github.com/k3s-io/k3s): Lightweight Kubernetes <https://k3s.io>
- 🌟 [rancher/rke2](https://github.com/rancher/rke2): RKE2, also known as RKE Government, is Rancher's next-generation Kubernetes distribution. <https://docs.rke2.io/>
- [k0sproject/k0s](https://github.com/k0sproject/k0s): k0s - The Zero Friction Kubernetes <https://docs.k0sproject.io>
- [klueska/kind-with-gpus-examples](https://github.com/klueska/kind-with-gpus-examples): No description, website, or topics provided.

### Cluster Management (or UIs)

- [lensapp/lens](https://github.com/lensapp/lens): Lens - The way the world runs Kubernetes <https://k8slens.dev>
- [pixie-io/pixie](https://github.com/pixie-io/pixie): Instant Kubernetes-Native Application Observability <https://px.dev>
- [derailed/k9s](https://github.com/derailed/k9s): 🐶 Kubernetes CLI To Manage Your Clusters In Style! <https://k9scli.io/>
- [aptakube/aptakube](https://github.com/aptakube/aptakube): Modern, lightweight and multi-cluster Kubernetes GUI. Available on Windows, macOS and Linux. <https://aptakube.com>
- [karmada-io/karmada](https://github.com/karmada-io/karmada): Open, Multi-Cloud, Multi-Cluster Kubernetes Orchestration <https://karmada.io>
- [komodorio/helm-dashboard](https://github.com/komodorio/helm-dashboard): The missing UI for Helm - visualize your releases

### Plugins

- [kr8s-org/kr8s](https://github.com/kr8s-org/kr8s): A simple, extensible Python client library for Kubernetes that feels familiar for folks who already know how to use kubectl <https://kr8s.org>
- [kumahq/kuma](https://github.com/kumahq/kuma): 🐻 The multi-zone service mesh for containers, Kubernetes and VMs. Built with Envoy. CNCF Sandbox Project. <https://kuma.io/install>
- [kubernetes/autoscaler](https://github.com/kubernetes/autoscaler): Autoscaling components for Kubernetes
- [kubernetes/kubeadm](https://github.com/kubernetes/kubeadm): Aggregator for issues filed against kubeadm
- [external-secrets/external-secrets](https://github.com/external-secrets/external-secrets): External Secrets Operator reads information from a third-party service like AWS Secrets Manager and automatically injects the values as Kubernetes Secrets. <https://external-secrets.io/main>
- [radius-project/radius](https://github.com/radius-project/radius): Radius is a cloud-native, portable application platform that makes app development easier for teams building cloud-native apps. <https://radapp.io>
- [openebs/lvm-localpv](https://github.com/openebs/lvm-localpv): CSI Driver for dynamic provisioning of Persistent Local Volumes for Kubernetes using LVM.
- [GoogleContainerTools/skaffold](https://github.com/GoogleContainerTools/skaffold): Easy and Repeatable Kubernetes Development <https://skaffold.dev/>
- [databus23/helm-diff](https://github.com/databus23/helm-diff): A helm plugin that shows a diff explaining what a helm upgrade would change
- [emberstack/kubernetes-reflector](https://github.com/emberstack/kubernetes-reflector): Custom Kubernetes controller that can be used to replicate secrets, configmaps and certificates.
- [knight42/krelay](https://github.com/knight42/krelay): A better alternative to `kubectl port-forward` that can forward TCP or UDP traffic to IP/Host which is accessible inside the cluster.
- [STRRL/cloudflare-tunnel-ingress-controller](https://github.com/STRRL/cloudflare-tunnel-ingress-controller): 🚀 Expose the website directly into the internet! The Kuberntes Ingress Controller based on Cloudflare Tunnel.
- [kyverno/kyverno](https://github.com/kyverno/kyverno): Kubernetes Native Policy Management <https://kyverno.io>

### App framework

- [kedacore/keda](https://github.com/kedacore/keda): KEDA is a Kubernetes-based Event Driven Autoscaling component. It provides event driven scale for any container running in Kubernetes <https://keda.sh>
  - lead by Microsoft
- [knative/eventing](https://github.com/knative/eventing): Event-driven application platform for Kubernetes <https://knative.dev/docs/eventing>
  - lead by Google

### Utils

- [tommy351/kosko](https://github.com/tommy351/kosko): Organize Kubernetes manifests in JavaScript. <https://kosko.dev>

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

## Cloud Foundry

- [one2nc/cloudlens](https://github.com/one2nc/cloudlens): k9s like CLI for AWS <https://one2n.gitbook.io/docs/>
- [ubicloud/ubicloud](https://github.com/ubicloud/ubicloud): Open, free, and portable cloud. Elastic compute, block storage (non replicated), virtual networking, managed Postgres, and IAM services in public beta. <https://ubicloud.com>
- [Spot by NetApp](https://spot.io/)

## Infrastructure as Code

### Framework

- [pulumi/pulumi](https://github.com/pulumi/pulumi): Pulumi - Universal Infrastructure as Code. Your Cloud, Your Language, Your Way 🚀 <https://www.pulumi.com>
- [crossplane/crossplane](https://github.com/crossplane/crossplane): Cloud Native Control Planes <https://crossplane.io/>
- [Azure/bicep](https://github.com/Azure/bicep): Bicep is a declarative language for describing and deploying Azure resources

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

### Pricing

- [bytebase/dbcost](https://github.com/bytebase/dbcost): The simple pricing calculator and comparison tool for the cloud databases. <https://www.dbcost.com>
- [uselotus/lotus](https://github.com/uselotus/lotus): Open Source Pricing & Packaging Infrastructure <https://www.uselotus.io>
- [juspay/hyperswitch](https://github.com/juspay/hyperswitch): An Open Source Financial Switch to make Payments fast, reliable and affordable
- [The Duckbill Group](https://www.duckbillgroup.com/): If your AWS bill keeps rising — and your blood pressure is doing the same — then you should be working with our team of cloud cost management experts.
- [opencost/opencost](https://github.com/opencost/opencost): Cost monitoring for Kubernetes workloads and cloud costs <http://opencost.io>
- [Vantage](https://www.vantage.sh/): Understand cloud costs and automate savings. See how much Vantage can reduce your bill by connecting accounts.

### Tech Stack

- [internetarchive/hind](https://github.com/internetarchive/hind): Hashistack-IN-Docker (single container with nomad + consul + caddy)
- [theztd/startup-infra-docker](https://github.com/theztd/startup-infra-docker): Easy managable infrastructure for small devops teams or startups (based on ansible, nomadproject, docker, prometheus)

## Utils

- [skyplane-project/skyplane](https://github.com/skyplane-project/skyplane): 🔥 Blazing fast bulk data transfers between any cloud 🔥 <https://skyplane.org>
- 🌟 [octodns/octodns](https://github.com/octodns/octodns): Tools for managing DNS across multiple providers
- [libdns/libdns](https://github.com/libdns/libdns): Core interfaces for universal DNS record manipulation across providers
- [go-acme/lego](https://github.com/go-acme/lego): Let's Encrypt/ACME client and library written in Go <https://go-acme.github.io/lego/>
- [rclone/rclone](https://github.com/rclone/rclone): "rsync for cloud storage" - Google Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Wasabi, Google Cloud Storage, Yandex Files <https://rclone.org>

## Serverless

- [robertcepa/toucan-js](https://github.com/robertcepa/toucan-js): Cloudflare Workers client for Sentry
- [Logflare/logflare](https://github.com/Logflare/logflare): Never get surprised by a logging bill again. Centralized structured logging for Cloudflare, Vercel, Elixir and Javascript. <https://logflare.app>
- [cloudflare/workers-rs](https://github.com/cloudflare/workers-rs): Write Cloudflare Workers in 100% Rust via WebAssembly
- [SukkaW/dashflare](https://github.com/SukkaW/dashflare): An unofficial Cloudflare dashboard built on top of Cloudflare API. <https://dashflare.skk.moe>
