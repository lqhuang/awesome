# Cryptograph

## Readings

- [Choosing a hash function for 2030 and beyond: SHA-2 vs SHA-3 vs BLAKE3](https://kerkour.com/fast-secure-hash-function-sha256-sha512-sha3-blake3)
- [gh:f5devcentral/openssl-pqc-stepbystep-lab](https://github.com/f5devcentral/openssl-pqc-stepbystep-lab): A hands-on lab guide for building a quantum-resistant Certificate Authority (CA) infrastructure using OpenSSL 3.0+ with learning paths for NIST FIPS 203/204/205, NSA CNSA 2.0, and alternate oqsprovider supported algorithms (currently HQC, FrodoKEM, BIKE)
- [gh:IETF-Hackathon/pqc-certificates](https://github.com/IETF-Hackathon/pqc-certificates): Post-quantum cryptography certificates
- 🌟 [gh:salrashid123/pqc_scratchpad](https://github.com/salrashid123/pqc_scratchpad): Post-Quantum Cryptography (PQC) scratchpad

## Services

- [keys.openpgp.org](https://keys.openpgp.org/)
- [pkic/pqccm](https://github.com/pkic/pqccm): PQC Capabilities Matrix (PQCCM)
- [Post-Quantum signatures zoo](https://pqshield.github.io/nist-sigs-zoo/index.html)

## Tools

- [gh:life4/enc](https://github.com/life4/enc): 🔑🔒 A modern and friendly CLI alternative to GnuPG: generate and download keys, encrypt, decrypt, and sign text and files, and more.
- [gh:gchq/CyberChef](https://github.com/gchq/CyberChef): The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis <https://gchq.github.io/CyberChef>
- [gh:openxpki/openxpki](https://github.com/openxpki/openxpki): OpenXPKI Code <http://www.openxpki.org>
- [gh:openca/libpki](https://github.com/openca/libpki): Easy-to-use high-level library for PKI-enabled applications
- 🌟 [gh:jedisct1/minisign](https://github.com/jedisct1/minisign): A dead simple tool to sign files and verify digital signatures. <https://jedisct1.github.io/minisign/>
- [gh:anchordotdev/cli](https://github.com/anchordotdev/cli): `anchor` provides a command line interface for the Anchor.dev certificate management platform.
- [gh:FiloSottile/age](https://github.com/FiloSottile/age): A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. <https://age-encryption.org>
- [gh:jedisct1/encpipe](https://github.com/jedisct1/encpipe): The dum^H^H^Hsimplest encryption tool in the world.
- 🌟 [gh:python-trio/trustme](https://github.com/python-trio/trustme): #1 quality TLS certs while you wait, for the discerning tester <https://trustme.rtfd.io>

## Libraries

### Crypto Primitives

- [gh:wbond/oscrypto](https://github.com/wbond/oscrypto): Compiler-free Python crypto library backed by the OS, supporting CPython and PyPy
- [gh:wbond/asn1crypto](https://github.com/wbond/asn1crypto): Python ASN.1 library with a focus on performance and a pythonic API
- [gh:BLAKE3-team/BLAKE3](https://github.com/BLAKE3-team/BLAKE3): the official Rust and C implementations of the BLAKE3 cryptographic hash function
- [gh:pyca/cryptography](https://github.com/pyca/cryptography): cryptography is a package designed to expose cryptographic primitives and recipes to Python developers. <https://cryptography.io>
- [gh:aws/aws-lc](https://github.com/aws/aws-lc): AWS-LC is a general-purpose cryptographic library maintained by the AWS Cryptography team for AWS and their customers. It іs based on code from the Google BoringSSL project and the OpenSSL project.
- [gh:aegis-aead/libaegis](https://github.com/aegis-aead/libaegis): Portable C implementations of the AEGIS family of high-performance authenticated encryption algorithms. <https://datatracker.ietf.org/doc/draft-irtf-cfrg-aegis-aead/>
- [gh:ogxd/gxhash](https://github.com/ogxd/gxhash): The fastest hashing algorithm 📈 <https://docs.rs/gxhash>
- [gh:besser82/libxcrypt](https://github.com/besser82/libxcrypt): Extended crypt library for descrypt, md5crypt, bcrypt, and others
  - support obsolete crypt API for glibc compatibility with musl libc
- [gh:randombit/botan](https://github.com/randombit/botan): Cryptography Toolkit <https://botan.randombit.net>
- [gh:jedisct1/libsodium](https://github.com/jedisct1/libsodium): A modern, portable, easy to use crypto library. <https://libsodium.org>
- [gh:open-quantum-safe/liboqs](https://github.com/open-quantum-safe/liboqs): C library for prototyping and experimenting with quantum-resistant cryptography <https://openquantumsafe.org/>
- [gh:open-quantum-safe/oqs-provider](https://github.com/open-quantum-safe/oqs-provider): OpenSSL 3 provider containing post-quantum algorithms <https://openquantumsafe.org>
- [gh:mupq/pqm4](https://github.com/mupq/pqm4): Post-quantum crypto library for the ARM Cortex-M4
- [gh:pq-code-package/mlkem-native](https://github.com/pq-code-package/mlkem-native): Secure, fast, and portable C90 implementation of ML-KEM / FIPS 203 <https://pq-code-package.github.io/mlkem-native/dev/bench/>
- [gh:pq-code-package/mldsa-native](https://github.com/pq-code-package/mldsa-native): Secure, fast, and portable C90 implementation of ML-DSA / FIPS 204 <https://pq-code-package.github.io/mldsa-native/dev/bench/>
  - used in AWS-LC
- [gh:dajiaji/crystals-kyber-js](https://github.com/dajiaji/crystals-kyber-js): The fastest pure TypeScript ML-KEM (NIST FIPS 203) implementation <https://dajiaji.github.io/crystals-kyber-js/docs/main>
- [gh:dajiaji/hpke-js](https://github.com/dajiaji/hpke-js): A Hybrid Public Key Encryption (HPKE) module built on top of Web Cryptography API. <https://dajiaji.github.io/hpke-js/docs>

### TLS

- [djc/pyrtls](https://github.com/djc/pyrtls): rustls-based modern TLS for Python
- [aws/s2n-tls](https://github.com/aws/s2n-tls): An implementation of the TLS/SSL protocols <https://aws.github.io/s2n-tls/usage-guide/>
- [quictls/quictls](https://github.com/quictls/quictls): The official repository for the QuicTLS project.
- [google/boringssl](https://github.com/google/boringssl): Mirror of BoringSSL <https://boringssl.googlesource.com/boringssl>
  - [cloudflare/boring](https://github.com/cloudflare/boring): BoringSSL bindings for the Rust programming language.
  - [apple/swift-crypto](https://github.com/apple/swift-crypto): Open-source implementation of a substantial portion of the API of Apple CryptoKit suitable for use on Linux platforms. <https://apple.github.io/swift-crypto>
  - [google/mundane](https://github.com/google/mundane): Mundane is a Rust cryptography library backed by BoringSSL that is difficult to misuse, ergonomic, and performant (in that order).
  - [aegis-aead/boringssl](https://github.com/aegis-aead/boringssl): BoringSSL, with support for the AEGIS cipher suites.
- [openssl/openssl](https://github.com/openssl/openssl): TLS/SSL and crypto library <https://www.openssl.org>
  - [rust-openssl/rust-openssl](https://github.com/rust-openssl/rust-openssl): OpenSSL bindings for Rust
  - [pyca/pyopenssl](https://github.com/pyca/pyopenssl): A Python wrapper around the OpenSSL library <https://pyopenssl.org/>
- [gh:digicert/trustcore](https://github.com/digicert/trustcore): TrustCore SDK
- [gh:h2o/picotls](https://github.com/h2o/picotls): TLS 1.3 implementation in C (master supports RFC8446 as well as draft-26, -27, -28)
- [gh:h2o/quicly](https://github.com/h2o/quicly): A modular QUIC stack designed primarily for H2O

### OpenPGP / GPG

- [gh:rnpgp/rnp](https://github.com/rnpgp/rnp): RNP: high performance C++ OpenPGP library used by Mozilla Thunderbird <https://www.rnpgp.org>
  - [gh:rnpgp/py-rnp](https://github.com/rnpgp/py-rnp): Python bindings for librnp <https://www.rnpgp.org>
- [gh:gpg/gnupg](https://github.com/gpg/gnupg): The GNU Privacy Guard.
  - [gh:gpg/gpgme](https://github.com/gpg/gpgme): GnuPG Made Easy.
- [LibrePGP](https://librepgp.org/)
- [gitlab:sequoia-pgp/sequoia](https://gitlab.com/sequoia-pgp/sequoia): Sequoia is a complete implementation of OpenPGP as defined by RFC 9580 as well as the deprecated OpenPGP as defined by RFC 4880, and various related standards.
- [gh:spwhitton/git-remote-gcrypt](https://github.com/spwhitton/git-remote-gcrypt): PGP-encrypted git remotes <https://spwhitton.name/tech/code/git-remote-gcrypt/>

### Misc

- [wbond/certbuilder](https://github.com/wbond/certbuilder): Python library for generating and signing X.509 certificates

## Certificate Management / PKI

- [gh:smallstep/certificates](https://github.com/smallstep/certificates): 🛡️ A private certificate authority (X.509 & SSH) & ACME server for secure automated certificate management, so you can use TLS everywhere & SSO for SSH. <https://smallstep.com/certificates>
- [gh:smallstep/cli](https://github.com/smallstep/cli): 🧰 A zero trust swiss army knife for working with X509, OAuth, JWT, OATH OTP, etc. <https://smallstep.com/cli>
- [Keyfactor](https://www.keyfactor.com/): Find, control, and automate every machine identity with Keyfactor, the leader in crypto-agility and PKI as-a-Service.
  - [gh:Keyfactor/ejbca-ce](https://github.com/Keyfactor/ejbca-ce): EJBCA® – Open-source public key infrastructure (PKI) and certificate authority (CA) software. <https://www.ejbca.org/>
  - [gh:Keyfactor/signserver-ce](https://github.com/Keyfactor/signserver-ce): SignServer – Open source, PKI-based signing software to sign code, documents, timestamps and more. <https://www.signserver.org>
- [Sectigo certificate manager](https://sectigo.com/enterprise-solutions/certificate-manager): Automated Certificate Lifecycle Management for the Modern Enterprise
- [hyperledger/fabric-ca](https://github.com/hyperledger/fabric-ca): a` Certificate Authority for Hyperledger Fabric. zh-cn: <https://hyperledgercn.github.io/hyperledgerDocs/ca-setup_zh>
- 🌟 [FiloSottile/mkcert](https://github.com/FiloSottile/mkcert): A simple zero-config tool to make locally trusted development certificates with any names you'd like. <https://mkcert.dev>
- [soulteary/certs-maker](https://github.com/soulteary/certs-maker): Tiny, easy SSL self-signed tools, ~3MB Size. Generate a self-hosted/dev certificate through configuration. <https://soulteary.com/2021/02/06/how-to-make-and-use-a-self-signed-certificate.html>
- [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager): Automatically provision and manage TLS certificates in Kubernetes <https://cert-manager.io>
- [usual2970/certimate](https://github.com/usual2970/certimate): 开源的 SSL 证书管理工具，可以帮助你自动申请、部署 SSL 证书，并在证书即将过期时自动续期。An open-source SSL certificate management tool that helps you automatically apply for and deploy SSL certificates, as well as automatically renew them when they are about to expire. <https://docs.certimate.me>
- [gh:square/certstrap](https://github.com/square/certstrap): Tools to bootstrap CAs, certificate requests, and signed certificates.
- [stacksjs/tlsx](https://github.com/stacksjs/tlsx): 🔐 A TLS library with automation. HTTPS by default through a light-weight library. Similar to mkcert. <https://tlsx.sh>
- [OpenVPN/easy-rsa](https://github.com/OpenVPN/easy-rsa): easy-rsa - Simple shell based CA utility
- 🪦📝 [airbnb/ottr](https://github.com/airbnb/ottr): Serverless Public Key Infrastructure Framework
  - Though it is not maintained anymore, It is still a good idea and I hope to learn from it.
  - [Meet Ottr: A Serverless Public Key Infrastructure Framework](https://medium.com/airbnb-engineering/meet-ottr-a-serverless-public-key-infrastructure-framework-f6580010ae0c): Ottr is a serverless Public Key Infrastructure framework that handles end-to-end certificate rotations without the use of an agent.
- [gh:spiffe/spiffe](https://github.com/spiffe/spiffe): The SPIFFE Project <http://spiffe.io>
- [gh:cloudflare/cfssl](https://github.com/cloudflare/cfssl): CFSSL: Cloudflare's PKI and TLS toolkit <https://cfssl.org/>
  - [gh:cloudflare/cfssl_trust](https://github.com/cloudflare/cfssl_trust): CFSSL's CA trust store repository
- [gh:cloudflare/circl](https://github.com/cloudflare/circl): CIRCL: Cloudflare Interoperable Reusable Cryptographic Library <http://blog.cloudflare.com/introducing-circl>
- [gh:chris2511/xca](https://github.com/chris2511/xca): X Certificate and Key management <http://xca.hohnstaedt.de>
