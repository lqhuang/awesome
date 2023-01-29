# Network

## Resources

### Books

- [Uncurled](https://un.curl.dev/): everything I know and learned about running
  and maintaining Open Source projects for three decades.
- [bagder/http3-explained](https://github.com/bagder/http3-explained): A
  document describing the HTTP/3 and QUIC protocols
  <https://http3-explained.haxx.se>
- [beejjorgensen/bgnet](https://github.com/beejjorgensen/bgnet): Beej's Guide to
  Network Programming source <https://beej.us/guide/bgnet/html/>
  <https://beej-zhtw-gitbook.netdpi.net/>

### Readings

- [syncsynchalt/illustrated-quic](https://github.com/syncsynchalt/illustrated-quic):
  The Illustrated QUIC Connection: Every byte explained
  <https://quic.xargs.org/>
- [https-dev/docs](https://github.com/https-dev/docs/blob/master/list-of-acme-servers.md):
  List of ACME Servers

## Libraries

- [cloudflare/boringtun](https://github.com/cloudflare/boringtun): Userspace
  WireGuard® Implementation in Rust
- [the-tcpdump-group/libpcap](https://github.com/the-tcpdump-group/libpcap): the
  LIBpcap interface to various kernel packet capture mechanism
  <https://www.tcpdump.org/>

## Tools

- [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy): An interactive
  TLS-capable intercepting HTTP proxy for penetration testers and software
  developers. <https://mitmproxy.org/>
- [ehids/ecapture](https://github.com/ehids/ecapture): capture SSL/TLS text
  content without CA cert using eBPF. supports Linux x86_64/Aarch64,
  Android(GKI) Aarch64.
- [bettercap/bettercap](https://github.com/bettercap/bettercap): The Swiss Army
  knife for 802.11, BLE, IPv4 and IPv6 networks reconnaissance and MITM attacks.
  <https://www.bettercap.org/>
- [fullstorydev/grpcurl](https://github.com/fullstorydev/grpcurl): Like cURL,
  but for gRPC: Command-line tool for interacting with gRPC servers
- [Orange-OpenSource/hurl](https://github.com/Orange-OpenSource/hurl): Hurl, run
  and test HTTP requests with plain text. <https://hurl.dev/>
- [secdev/scapy](https://github.com/secdev/scapy): Scapy: the Python-based
  interactive packet manipulation program & library. Supports Python 2 &
  Python 3. <https://scapy.net/>
- [beyondcode/expose](https://github.com/beyondcode/expose): A beautiful, fully
  open-source, tunneling service - written in pure PHP <https://expose.dev/>
- [wg-meshconf](https://github.com/k4yt3x/wg-meshconf): WireGuard full mesh
  configuration generator.
- [traviscross/mtr](https://github.com/traviscross/mtr): Official repository for
  mtr, a network diagnostic tool <http://www.bitwizard.nl/mtr/>
- [GyulyVGC/sniffnet](https://github.com/GyulyVGC/sniffnet): Cross-platform
  application to monitor your network traffic with ease
- [netsniff-ng/netsniff-ng](https://github.com/netsniff-ng/netsniff-ng): A Swiss
  army knife for your daily Linux network plumbing. <http://netsniff-ng.org/>
- [the-tcpdump-group/tcpdump](https://github.com/the-tcpdump-group/tcpdump): the
  TCPdump network dissector <https://www.tcpdump.org/>
- [droe/sslsplit](https://github.com/droe/sslsplit): Transparent SSL/TLS
  interception <https://www.roe.ch/SSLsplit>
- [ktbyers/netmiko](https://github.com/ktbyers/netmiko): Multi-vendor library to
  simplify Paramiko SSH connections to network devices
- [paramiko/paramiko](https://github.com/paramiko/paramiko): The leading native
  Python SSHv2 protocol library. <http://paramiko.org/>

### Analysis

- [nfstream/nfstream](https://github.com/nfstream/nfstream): NFStream: a
  Flexible Network Data Analysis Framework. <https://www.nfstream.org/>

### Observability

- [netenglabs/suzieq](https://github.com/netenglabs/suzieq): Using network
  observability to operate and design healthier networks
  <https://www.stardustsystems.net/suzieq/>
- [batfish/batfish](https://github.com/batfish/batfish): Batfish is a network
  configuration analysis tool that can find bugs and guarantee the correctness
  of (planned or current) network configurations. It enables network engineers
  to rapidly and safely evolve their network, without fear of outages or
  security breaches. <http://www.batfish.org/>
- [ivre/ivre](https://github.com/ivre/ivre): Network recon framework. Build your
  own, self-hosted and fully-controlled alternatives to Shodan / ZoomEye /
  Censys and GreyNoise, run your Passive DNS service, collect and analyse
  network intelligence from your sensors, and much more! <>
- [ntop/ntopng](https://github.com/ntop/ntopng): Web-based Traffic and Security
  Network Traffic Monitoring <http://www.ntop.org/>
- [akvorado/akvorado](https://github.com/akvorado/akvorado): Flow collector,
  enricher and visualizer <https://demo.akvorado.net/>

### RouterOS Automation?

- [napalm-automation/napalm](https://github.com/napalm-automation/napalm):
  Network Automation and Programmability Abstraction Layer with Multivendor
  support <https://napalm.readthedocs.io/>
- [nornir-automation/nornir](https://github.com/nornir-automation/nornir):
  Pluggable multi-threaded framework with inventory management to help operate
  collections of devices <https://nornir.readthedocs.io/>

## DNS

- [serverless-dns/serverless-dns](https://github.com/serverless-dns/serverless-dns):
  The RethinkDNS resolver that deploys to Cloudflare Workers, Deno Deploy, and
  Fly.io <https://rethinkdns.com/configure>
- [bluejekyll/trust-dns](https://github.com/bluejekyll/trust-dns): A Rust based
  DNS client, server, and resolver
- [exentriquesolutions/nip.io](https://github.com/exentriquesolutions/nip.io):
  Dead simple wildcard DNS for any IP Address. <https://nip.io>
- <https://sslip.io>: `sslip.io` is a DNS service that, when queried with a
  hostname with an embedded IP address, returns that IP address.
- <https://local.gd>: The easiest way to serve localhost. DNS that always
  resolves to 127.0.0.1.
- [Corollarium/localtls](https://github.com/Corollarium/localtls): DNS server
  for providing TLS to webservices on local addresses
- [ogham/dog](https://github.com/ogham/dog): A command-line DNS client.
  <https://dns.lookup.dog/>

## Tunnel

- [dndx/phantun](https://github.com/dndx/phantun): Transforms UDP stream into
  (fake) TCP streams that can go through Layer 3 & Layer 4 (NAPT)
  firewalls/NATs. https://github.com/meh/rust-tun
- [cjdelisle/cjdns](https://github.com/cjdelisle/cjdns): An encrypted IPv6
  network using public-key cryptography for address allocation and a distributed
  hash table for routing.
- [yggdrasil-network/yggdrasil-go](https://github.com/yggdrasil-network/yggdrasil-go):
  An experiment in scalable routing as an encrypted IPv6 overlay network
  <https://yggdrasil-network.github.io/>
- [googleforgames/quilkin](https://github.com/googleforgames/quilkin): Quilkin
  is a non-transparent UDP proxy specifically designed for use with large scale
  multiplayer dedicated game server deployments, to ensure security, access
  control, telemetry data, metrics and more.
- [ekzhang/bore](https://github.com/ekzhang/bore): 🕳 bore is a simple CLI tool
  for making tunnels to localhost <http://bore.pub/>

### Mesh network

- [ntop/n2n](https://github.com/ntop/n2n): Peer-to-peer VPN
- [omniedgeio/omniedge](https://github.com/omniedgeio/omniedge): OmniEdge is an
  Open source p2p layer 2 mesh VPN infrastructure, a traditional VPN, AWS VPC,
  Ngrok, DDNS alternative. No central server, easy to scale with less
  maintenance. What happens in intranet, stays in in intranet.
  <https://omniedge.io/>
- [slackhq/nebula](https://github.com/slackhq/nebula): A scalable overlay
  networking tool with a focus on performance, simplicity and security
- [netbirdio/netbird](https://github.com/netbirdio/netbird): Connect your
  devices into a single secure private WireGuard®-based mesh network with
  SSO/MFA and simple access controls. <https://netbird.io/>
- [tailscale/tailscale](https://github.com/tailscale/tailscale): The easiest,
  most secure way to use WireGuard and 2FA. <https://tailscale.com/>
- [tailscale/golink](https://github.com/tailscale/golink): A private shortlink
  service for tailnets
- [gravitl/netmaker](https://github.com/gravitl/netmaker): Netmaker makes
  networks with WireGuard. Netmaker automates fast, secure, and distributed
  virtual networks. <https://netmaker.io/>
- [juanfont/headscale](https://github.com/juanfont/headscale): An open source,
  self-hosted implementation of the Tailscale control server
- [tonarino/innernet](https://github.com/tonarino/innernet): A private network
  system that uses WireGuard under the hood.
  <https://blog.tonari.no/introducing-innernet>
- [firezone/firezone](https://github.com/firezone/firezone): WireGuard®-based
  VPN server and firewall <https://firezone.dev/>
- https://www.tinc-vpn.org/
