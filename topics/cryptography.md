# Cryptograph

## Readings

- [Choosing a hash function for 2030 and beyond: SHA-2 vs SHA-3 vs BLAKE3](https://kerkour.com/fast-secure-hash-function-sha256-sha512-sha3-blake3)

## Tools

- [life4/enc](https://github.com/life4/enc): 🔑🔒 A modern and friendly CLI alternative to GnuPG: generate and download keys, encrypt, decrypt, and sign text and files, and more.
- [gchq/CyberChef](https://github.com/gchq/CyberChef): The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis <https://gchq.github.io/CyberChef>
- [openxpki/openxpki](https://github.com/openxpki/openxpki): OpenXPKI Code <http://www.openxpki.org>
- [openca/libpki](https://github.com/openca/libpki): Easy-to-use high-level library for PKI-enabled applications
- [jedisct1/minisign](https://github.com/jedisct1/minisign): A dead simple tool to sign files and verify digital signatures. <https://jedisct1.github.io/minisign/>

## Libraries

- [wbond/oscrypto](https://github.com/wbond/oscrypto): Compiler-free Python crypto library backed by the OS, supporting CPython and PyPy
- [wbond/certbuilder](https://github.com/wbond/certbuilder): Python library for generating and signing X.509 certificates
- [wbond/asn1crypto](https://github.com/wbond/asn1crypto): Python ASN.1 library with a focus on performance and a pythonic API
- [BLAKE3-team/BLAKE3](https://github.com/BLAKE3-team/BLAKE3): the official Rust and C implementations of the BLAKE3 cryptographic hash function
- [pyca/cryptography](https://github.com/pyca/cryptography): cryptography is a package designed to expose cryptographic primitives and recipes to Python developers. <https://cryptography.io>
- [djc/pyrtls](https://github.com/djc/pyrtls): rustls-based modern TLS for Python
- [aws/s2n-tls](https://github.com/aws/s2n-tls): An implementation of the TLS/SSL protocols <https://aws.github.io/s2n-tls/usage-guide/>
- [aegis-aead/libaegis](https://github.com/aegis-aead/libaegis): Portable C implementations of the AEGIS family of high-performance authenticated encryption algorithms. <https://datatracker.ietf.org/doc/draft-irtf-cfrg-aegis-aead/>
- [ogxd/gxhash](https://github.com/ogxd/gxhash): The fastest hashing algorithm 📈 <https://docs.rs/gxhash>
- [besser82/libxcrypt](https://github.com/besser82/libxcrypt): Extended crypt library for descrypt, md5crypt, bcrypt, and others
  - support obsolete crypt API for glibc compatibility with musl libc

## Certificate Management

- 🌟 [smallstep/certificates](https://github.com/smallstep/certificates): 🛡️ A private certificate authority (X.509 & SSH) & ACME server for secure automated certificate management, so you can use TLS everywhere & SSO for SSH. <https://smallstep.com/certificates>
- 🌟 [smallstep/cli](https://github.com/smallstep/cli): 🧰 A zero trust swiss army knife for working with X509, OAuth, JWT, OATH OTP, etc. <https://smallstep.com/cli>
- [Sectigo certificate manager](https://sectigo.com/enterprise-solutions/certificate-manager): Automated Certificate Lifecycle Management for the Modern Enterprise
- [Keyfactor](https://www.keyfactor.com/): Find, control, and automate every machine identity with Keyfactor, the leader in crypto-agility and PKI as-a-Service.
- [hyperledger/fabric-ca](https://github.com/hyperledger/fabric-ca): a` Certificate Authority for Hyperledger Fabric. zh-cn: <https://hyperledgercn.github.io/hyperledgerDocs/ca-setup_zh>
- 🌟 [FiloSottile/mkcert](https://github.com/FiloSottile/mkcert): A simple zero-config tool to make locally trusted development certificates with any names you'd like. <https://mkcert.dev>
- [soulteary/certs-maker](https://github.com/soulteary/certs-maker): Tiny, easy SSL self-signed tools, ~3MB Size. Generate a self-hosted/dev certificate through configuration. <https://soulteary.com/2021/02/06/how-to-make-and-use-a-self-signed-certificate.html>
- [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager): Automatically provision and manage TLS certificates in Kubernetes <https://cert-manager.io>
- [usual2970/certimate](https://github.com/usual2970/certimate): 开源的 SSL 证书管理工具，可以帮助你自动申请、部署 SSL 证书，并在证书即将过期时自动续期。An open-source SSL certificate management tool that helps you automatically apply for and deploy SSL certificates, as well as automatically renew them when they are about to expire. <https://docs.certimate.me>
- [square/certstrap](https://github.com/square/certstrap): Tools to bootstrap CAs, certificate requests, and signed certificates.
- [stacksjs/tlsx](https://github.com/stacksjs/tlsx): 🔐 A TLS library with automation. HTTPS by default through a light-weight library. Similar to mkcert. <https://tlsx.sh>
- [OpenVPN/easy-rsa](https://github.com/OpenVPN/easy-rsa): easy-rsa - Simple shell based CA utility
- 🪦📝 [airbnb/ottr](https://github.com/airbnb/ottr): Serverless Public Key Infrastructure Framework
  - Though it is not maintained anymore, It is still a good idea and I hope to learn from it.
  - [Meet Ottr: A Serverless Public Key Infrastructure Framework](https://medium.com/airbnb-engineering/meet-ottr-a-serverless-public-key-infrastructure-framework-f6580010ae0c): Ottr is a serverless Public Key Infrastructure framework that handles end-to-end certificate rotations without the use of an agent.
