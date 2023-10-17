# Network

## Resources

### Books

- [Uncurled](https://un.curl.dev): everything I know and learned about running
  and maintaining Open Source projects for three decades.
- 🌟 [bagder/http3-explained](https://github.com/bagder/http3-explained): A
  document describing the HTTP/3 and QUIC protocols
  <https://http3-explained.haxx.se>
- [beejjorgensen/bgnet](https://github.com/beejjorgensen/bgnet): Beej's Guide to
  Network Programming source <https://beej.us/guide/bgnet/html>
  <https://beej-zhtw-gitbook.netdpi.net>

### Readings

- [syncsynchalt/illustrated-quic](https://github.com/syncsynchalt/illustrated-quic):
  The Illustrated QUIC Connection: Every byte explained <https://quic.xargs.org>
  - [cangSDARM/illustrate](https://github.com/cangSDARM/illustrate): illustrate
    QUIC, TLS 1.2, TLS 1.3, DTLS 中文翻译
    <https://cangsdarm.github.io/illustrate/>
- [https-dev/docs](https://github.com/https-dev/docs/blob/master/list-of-acme-servers.md):
  List of ACME Servers
- [clowwindy/Awesome-Networking](https://github.com/clowwindy/Awesome-Networking):
  A curated list of awesome networking libraries, resources and shiny things
- [See this page fetch itself, byte by byte, over TLS](https://subtls.pages.dev/)
- [riba2534/TCP-IP-NetworkNote](https://github.com/riba2534/TCP-IP-NetworkNote):
  📘《TCP/IP 网络编程》(韩-尹圣雨)学习笔记

## Libraries

- [cloudflare/boringtun](https://github.com/cloudflare/boringtun): Userspace
  WireGuard® Implementation in Rust
- 🌟 [the-tcpdump-group/libpcap](https://github.com/the-tcpdump-group/libpcap):
  the LIBpcap interface to various kernel packet capture mechanism
  <https://www.tcpdump.org>
- [microsoft/snocat](https://github.com/microsoft/snocat): Streaming Network
  Overlay Connection Arbitration Tunnel
- [libpnet/libpnet](https://github.com/libpnet/libpnet): Cross-platform, low
  level networking using the Rust programming language.
- [DPDK/dpdk](https://github.com/DPDK/dpdk): Data Plane Development Kit
- [real-logic/aeron](https://github.com/real-logic/aeron): Efficient reliable
  UDP unicast, UDP multicast, and IPC message transport
- 🌟 [quinn-rs/quinn](https://github.com/quinn-rs/quinn): Async-friendly QUIC
  implementation in Rust
- [cloudflare/quiche](https://github.com/cloudflare/quiche): 🥧 Savoury
  implementation of the QUIC transport protocol and HTTP/3
  <https://docs.quic.tech/quiche/>
- [google/quiche](https://github.com/google/quiche): QUICHE stands for QUIC,
  Http, Etc. It is Google's production-ready implementation of QUIC, HTTP/2,
  HTTP/3, and related protocols and tools. It powers Google's servers, Chromium,
  Envoy, and other projects. It is actively developed and maintained.

## Tools

- 🌟 [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy): An
  interactive TLS-capable intercepting HTTP proxy for penetration testers and
  software developers. <https://mitmproxy.org>
- 🌟 [gojue/ecapture](https://github.com/gojue/ecapture): capture SSL/TLS text
  content without CA cert using eBPF. supports Linux/Android x86_64/Aarch64.
  <https://ecapture.cc>
- [bettercap/bettercap](https://github.com/bettercap/bettercap): The Swiss Army
  knife for 802.11, BLE, IPv4 and IPv6 networks reconnaissance and MITM attacks.
  <https://www.bettercap.org>
- [fullstorydev/grpcurl](https://github.com/fullstorydev/grpcurl): Like cURL,
  but for gRPC: Command-line tool for interacting with gRPC servers
- [Orange-OpenSource/hurl](https://github.com/Orange-OpenSource/hurl): Hurl, run
  and test HTTP requests with plain text. <https://hurl.dev>
- [secdev/scapy](https://github.com/secdev/scapy): Scapy: the Python-based
  interactive packet manipulation program & library. Supports Python 2 &
  Python 3. <https://scapy.net>
- [beyondcode/expose](https://github.com/beyondcode/expose): A beautiful, fully
  open-source, tunneling service - written in pure PHP <https://expose.dev>
- [traviscross/mtr](https://github.com/traviscross/mtr): Official repository for
  mtr, a network diagnostic tool <http://www.bitwizard.nl/mtr>
- [GyulyVGC/sniffnet](https://github.com/GyulyVGC/sniffnet): Cross-platform
  application to monitor your network traffic with ease
- 🌟 [netsniff-ng/netsniff-ng](https://github.com/netsniff-ng/netsniff-ng): A
  Swiss army knife for your daily Linux network plumbing.
  <http://netsniff-ng.org>
- 🌟 [the-tcpdump-group/tcpdump](https://github.com/the-tcpdump-group/tcpdump):
  the TCPdump network dissector <https://www.tcpdump.org>
- [droe/sslsplit](https://github.com/droe/sslsplit): Transparent SSL/TLS
  interception <https://www.roe.ch/SSLsplit>
- [ktbyers/netmiko](https://github.com/ktbyers/netmiko): Multi-vendor library to
  simplify Paramiko SSH connections to network devices
- [paramiko/paramiko](https://github.com/paramiko/paramiko): The leading native
  Python SSHv2 protocol library. <http://paramiko.org>
- [vergoh/vnstat](https://github.com/vergoh/vnstat): vnStat - a network traffic
  monitor for Linux and BSD
- [Zoxc/crusader](https://github.com/Zoxc/crusader): A network bandwidth and
  latency tester.
- [Mellanox/sockperf](https://github.com/Mellanox/sockperf): Network
  Benchmarking Utility

### Analysis

- [nfstream/nfstream](https://github.com/nfstream/nfstream): NFStream: a
  Flexible Network Data Analysis Framework. <https://www.nfstream.org>

### Observability

- [netenglabs/suzieq](https://github.com/netenglabs/suzieq): Using network
  observability to operate and design healthier networks
  <https://www.stardustsystems.net/suzieq>
- [batfish/batfish](https://github.com/batfish/batfish): Batfish is a network
  configuration analysis tool that can find bugs and guarantee the correctness
  of (planned or current) network configurations. It enables network engineers
  to rapidly and safely evolve their network, without fear of outages or
  security breaches. <http://www.batfish.org>
- [ivre/ivre](https://github.com/ivre/ivre): Network recon framework. Build your
  own, self-hosted and fully-controlled alternatives to Shodan / ZoomEye /
  Censys and GreyNoise, run your Passive DNS service, collect and analyse
  network intelligence from your sensors, and much more! <>
- [ntop/ntopng](https://github.com/ntop/ntopng): Web-based Traffic and Security
  Network Traffic Monitoring <http://www.ntop.org>
- 🌟 [akvorado/akvorado](https://github.com/akvorado/akvorado): Flow collector,
  enricher and visualizer <https://demo.akvorado.net>

### RouterOS Automation?

- [napalm-automation/napalm](https://github.com/napalm-automation/napalm):
  Network Automation and Programmability Abstraction Layer with Multivendor
  support <https://napalm.readthedocs.io>
- [nornir-automation/nornir](https://github.com/nornir-automation/nornir):
  Pluggable multi-threaded framework with inventory management to help operate
  collections of devices <https://nornir.readthedocs.io>

## Proxy

- [macronut/phantomsocks](https://github.com/macronut/phantomsocks): A
  cross-platform proxy client/server for Linux/Windows/macOS
- [enfein/mieru](https://github.com/enfein/mieru): 見える是一款 socks5 网络代理
  工具。Mieru is a socks5 proxy to bypass censorship.
- [eycorsican/leaf](https://github.com/eycorsican/leaf): A versatile and
  efficient proxy framework with nice features suitable for various use cases.
- [mingcheng/socks5lb](https://github.com/mingcheng/socks5lb): A simple socks5
  proxy load balance and transparent proxy
- [dndx/phantun](https://github.com/dndx/phantun): Transforms UDP stream into
  (fake) TCP streams that can go through Layer 3 & Layer 4 (NAPT)
  firewalls/NATs. https://github.com/meh/rust-tun
- [wangyu-/udp2raw](https://github.com/wangyu-/udp2raw): A Tunnel which Turns
  UDP Traffic into Encrypted UDP/FakeTCP/ICMP Traffic by using Raw Socket,helps
  you Bypass UDP FireWalls(or Unstable UDP Environment)
- [googleforgames/quilkin](https://github.com/googleforgames/quilkin): Quilkin
  is a non-transparent UDP proxy specifically designed for use with large scale
  multiplayer dedicated game server deployments, to ensure security, access
  control, telemetry data, metrics and more.
- [SukkaW/Surge](https://github.com/SukkaW/Surge): 由 Sukka 搜集、整理、维护的、
  个人自用的、仅适用于 Surge 的 Rule Snippet <https://ruleset.skk.moe>
- [nadoo/glider](https://github.com/nadoo/glider): glider is a forward proxy
  with multiple protocols support, and also a dns/dhcp server with ipset
  management features(like dnsmasq).
- [apernet/hysteria](https://github.com/apernet/hysteria): Hysteria is a
  feature-packed proxy & relay tool optimized for lossy, unstable connections
  (e.g. satellite networks, congested public Wi-Fi, connecting to foreign
  servers from China) <https://hysteria.network/>
- [XIU2/CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest): 🌩「自
  选优选 IP」测试 Cloudflare CDN 延迟和速度，获取最快 IP (IPv4 / IPv6)！另外也支
  持其他 CDN / 网站 IP ~
- [gwen001/cloudflare-origin-ip](https://github.com/gwen001/cloudflare-origin-ip):
  Try to find the origin IP of a webapp protected by Cloudflare.
- [OwO-Network/nexttrace-enhanced](https://github.com/OwO-Network/nexttrace-enhanced):
  An open source visual route tracking CLI tool (Enhanced Edition)
- [sjlleo/nexttrace](https://github.com/sjlleo/nexttrace): An open source visual
  route tracking CLI tool <https://trace.ac>
- [iw4p/OpenConnect-Cisco-AnyConnect-VPN-Server-OneKey-ocserv](https://github.com/iw4p/OpenConnect-Cisco-AnyConnect-VPN-Server-OneKey-ocserv):
  [Script and Docker 🐳] OpenConnect (Cisco AnyConnect) VPN Server (OCServ)
  script one key easy configurator and installer
- [hq450/fancyss](https://github.com/hq450/fancyss): fancyss is a project
  providing tools to across the GFW on asuswrt/merlin based router.
- [ihciah/shadow-tls](https://github.com/ihciah/shadow-tls): A proxy to expose
  real tls handshake to the firewall
  <https://www.ihcblog.com/a-better-tls-obfs-proxy>
- [zfl9/chinadns-ng](https://github.com/zfl9/chinadns-ng): chinadns 重构增强版，
  支持黑白名单，ipset/nftset
- [zfl9/ss-tproxy](https://github.com/zfl9/ss-tproxy): 搭建
  SS/SSR/V2Ray/Trojan/Socks5 透明代理的 Shell 脚本
- [nadoo/glider](https://github.com/nadoo/glider): glider is a forward proxy
  with multiple protocols support, and also a dns/dhcp server with ipset
  management features(like dnsmasq).
- [patte/fly-tailscale-exit](https://github.com/patte/fly-tailscale-exit): Run a
  VPN with global exit nodes with fly.io, tailscale and github!
  <https://news.ycombinator.com/item?id=36064305>
- [juewuy/ShellClash](https://github.com/juewuy/ShellClash): One-click
  deployment and management of Clash services using Shell scripts in Linux
  environment
- [misakaio/chnroutes2](https://github.com/misakaio/chnroutes2): Better
  aggregated chnroutes
- [cppla/ServerStatus](https://github.com/cppla/ServerStatus): 云探针、多服务器
  探针、云监控、多服务器云监控，演示： <https://tz.cloudcpp.com>
- [zdz/ServerStatus-Rust](https://github.com/zdz/ServerStatus-Rust): ✨ Rust 版
  ServerStatus 探针、威力加强版 <https://ssr.rs/>
- [felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list):
  Chinese-specific configuration to improve your favorite DNS server. Best
  partner for chnroutes.
- [daeuniverse/dae](https://github.com/daeuniverse/dae): A Linux
  high-performance transparent proxy solution based on eBPF.

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
  <https://dns.lookup.dog>
- [zu1k/nali](https://github.com/zu1k/nali): An offline tool for querying IP
  geographic information and CDN provider. 一个查询 IP 地理信息和 CDN 服务提供商
  的离线终端工具. <https://github.com/zu1k/nali>
- [devanshbatham/DNSleuth](https://github.com/devanshbatham/DNSleuth): DNSleuth
  sniffs DNS packets, i.e, allowing you to spy on the DNS queries your machine
  is making
- [pymumu/smartdns](https://github.com/pymumu/smartdns): A local DNS server to
  obtain the fastest website IP for the best Internet experience，一个本地 DNS
  服务器，获取最快的网站 IP，获得最佳上网体验。
- [IrineSistiana/mosdns](https://github.com/IrineSistiana/mosdns): 一个 DNS 转发
  器
- [errantmind/faf-dns-proxy](https://github.com/errantmind/faf-dns-proxy): A
  DNS-over-TLS (DoT) Proxy, Engineered for Speed

## Tunnel

- [cjdelisle/cjdns](https://github.com/cjdelisle/cjdns): An encrypted IPv6
  network using public-key cryptography for address allocation and a distributed
  hash table for routing.
- [yggdrasil-network/yggdrasil-go](https://github.com/yggdrasil-network/yggdrasil-go):
  An experiment in scalable routing as an encrypted IPv6 overlay network
  <https://yggdrasil-network.github.io>
- [openziti/zrok](https://github.com/openziti/zrok): Geo-scale, next-generation
  sharing platform built on top of OpenZiti. <https://zrok.io>
- [ekzhang/bore](https://github.com/ekzhang/bore): 🕳 bore is a simple CLI tool
  for making tunnels to localhost <http://bore.pub>
- [pgrok/pgrok](https://github.com/pgrok/pgrok): Poor man's ngrok - a
  multi-tenant HTTP reverse tunnel solution through SSH remote port forwarding
- [rapiz1/rathole](https://github.com/rapiz1/rathole): A lightweight and
  high-performance reverse proxy for NAT traversal, written in Rust. An
  alternative to frp and ngrok.
- [anderspitman/awesome-tunneling](https://github.com/anderspitman/awesome-tunneling):
  List of ngrok alternatives and other ngrok-like tunneling software and
  services. Focus on self-hosting.
- [openconnect/ocserv](https://gitlab.com/openconnect/ocserv): Engine for secure
  and scalable VPN infrastructure https://ocserv.gitlab.io/www/
- [rosenpass/rosenpass](https://github.com/rosenpass/rosenpass): Rosenpass is a
  formally verified, post-quantum secure VPN that uses WireGuard to transport
  the actual data. <https://rosenpass.eu/>
- [unjs/untun](https://github.com/unjs/untun): 🚇 Tunnel your local HTTP(s)
  server to the world! powered by Cloudflare Quick Tunnels.

### Mesh network

- [ntop/n2n](https://github.com/ntop/n2n): Peer-to-peer VPN
- [omniedgeio/omniedge](https://github.com/omniedgeio/omniedge): OmniEdge is an
  Open source p2p layer 2 mesh VPN infrastructure, a traditional VPN, AWS VPC,
  Ngrok, DDNS alternative. No central server, easy to scale with less
  maintenance. What happens in intranet, stays in in intranet.
  <https://omniedge.io>
- [slackhq/nebula](https://github.com/slackhq/nebula): A scalable overlay
  networking tool with a focus on performance, simplicity and security
- 🌟 [tailscale/tailscale](https://github.com/tailscale/tailscale): The easiest,
  most secure way to use WireGuard and 2FA. <https://tailscale.com>
- [tailscale/golink](https://github.com/tailscale/golink): A private shortlink
  service for tailnets
- 🌟 [gravitl/netmaker](https://github.com/gravitl/netmaker): Netmaker makes
  networks with WireGuard. Netmaker automates fast, secure, and distributed
  virtual networks. <https://netmaker.io>
- [madacluster/netmaker-terraform-provider](https://github.com/madacluster/netmaker-terraform-provider):
  Terraform Provider Netmaker
- [juanfont/headscale](https://github.com/juanfont/headscale): An open source,
  self-hosted implementation of the Tailscale control server
- [gurucomputing/headscale-ui](https://github.com/gurucomputing/headscale-ui): A
  web frontend for the headscale Tailscale-compatible coordination server
- 🌟 [firezone/firezone](https://github.com/firezone/firezone): WireGuard®-based
  VPN server and firewall <https://firezone.dev>
- [k4yt3x/wg-meshconf](https://github.com/k4yt3x/wg-meshconf): WireGuard full
  mesh configuration generator.
- Seems good, but they use a custom client cli, which wouldn't be my choice, at
  least.
  - [netbirdio/netbird](https://github.com/netbirdio/netbird): Connect your
    devices into a single secure private WireGuard®-based mesh network with
    SSO/MFA and simple access controls. <https://netbird.io>
  - [tonarino/innernet](https://github.com/tonarino/innernet): A private network
    system that uses WireGuard under the hood.
    <https://blog.tonari.no/introducing-innernet>

## Online tools / Services

- [Censys](https://search.censys.io)
- [ipinfo.io](https://ipinfo.io)
- [Is using HTTP3?](https://http3.is)
- [HTTP/3 Check](https://http3check.net)
- [IPLeak.net](https://ipleak.net)
- [DSN leak test](https://www.dnsleaktest.com/):
- [Globalping](https://www.jsdelivr.com/globalping)
- [Web Check](https://web-check.xyz/)
- [KeyCDN tools](https://tools.keycdn.com)
- [Tabserve](https://tabserve.dev/): A secure & fast HTTPS URL for localhost
  using your browser as a reverse proxy.
- [domain.glass](https://domain.glass/): DNS / WHOIS Lookup
