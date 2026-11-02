# NVO987 Cryptographic & Digital Infrastructure

Independent cryptographic software applications and digital tools
maintained under the NVO987 namespace.

**Website:** https://software.nvo987.us/

**Maintainer:** Nicholas Van-Orton

**Copyright:** © 2026 Nicholas Van-Orton

## Overview

NVO987 Cryptographic & Digital Infrastructure is a collection of
web-based software applications and digital utilities accessible
through dedicated NVO987 subdomains.

The project brings together cryptographic hash utilities, data-format
tools, identifier generators, and other digital infrastructure tools.

## Applications

| Application | URL |
|---|---|
| Favicon | https://favicon.nvo987.us/ |
| Keccak-256 & Whirlpool | https://keccak.nvo987.us/ |
| BLAKE2 & BLAKE3 | https://blake.nvo987.us/ |
| SHA-1 | https://sha1.nvo987.us/ |
| SHA-512 | https://sha512.nvo987.us/ |
| SHA3-256 | https://sha3.nvo987.us/ |
| JSON & XML | https://json.nvo987.us/ |
| SHA-256 | https://sha256.nvo987.us/ |
| UUID Generator | https://uuid.nvo987.us/ |
| QR Code Generator | https://qr.nvo987.us/ |
| SHA Suite | https://sha.nvo987.us/ |

## Technology

The supplied website uses:

- HTML5
- CSS3
- Responsive layout techniques
- DM Sans typography
- Semantic HTML elements
- JSON-LD structured data
- Open Graph metadata
- Search engine discovery directives
- Dedicated application subdomains

The main landing page is designed to provide a responsive directory
of applications and digital tools.

The technologies used by individual applications may differ.

## Cryptographic Considerations

Cryptographic hash functions and related utilities serve different
purposes and provide different security properties.

SHA-1 is considered unsuitable for applications requiring collision
resistance against modern attacks.

SHA-256, SHA-512, SHA3-256, Keccak, BLAKE2, and BLAKE3 have different
designs and application characteristics.

Keccak-256 and SHA3-256 are related but are not interchangeable
without considering their different domain-separation rules.

Whirlpool is a cryptographic hash function, not an encryption algorithm.

A hash function does not encrypt data and cannot generally be reversed
to recover the original input.

A generated UUID or QR code should not automatically be considered
a secure authentication credential.

Users should independently verify the behavior and security properties
of each application before using it for security-sensitive operations.

## Privacy and Data Handling

The landing-page HTML alone does not establish whether the individual
applications process data locally or transmit information to a server.

Consult each application's implementation and privacy documentation
before submitting confidential or sensitive information.

## Search Engine and Machine-Readable Files

The following files may be published at the website root:

- `/robots.txt`
- `/sitemap.xml`
- `/rss.xml`
- `/atom.xml`
- `/ai.txt`
- `/llms.txt`
- `/humans.txt`
- `/foaf.xml`
- `/security.txt`

These files serve different discovery, documentation, and metadata
purposes.

Their presence does not guarantee search engine indexing or adoption
by AI crawlers.

## Contact

Email: nvo@nvo987.us

Website: https://software.nvo987.us/

Main NVO987 website: https://nvo987.us/

Identity infrastructure: https://identity.nvo987.us/

## License

Unless an explicit license states otherwise, the original source code,
design, and documentation are not automatically licensed for reuse.

Third-party components remain subject to their respective licenses.

See the `LICENSE` file for the project's copyright notice. 
