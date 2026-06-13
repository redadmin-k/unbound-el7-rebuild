# unbound-el7-rebuild

Unofficial CentOS 7 rebuild of Unbound RPMs based on the AlmaLinux 8 SRPM.

## Purpose

This repository is intended for technical verification, rebuild testing, and compatibility investigation on CentOS 7 compatible environments.

It is not intended to replace official vendor support, commercial extended support, or migration to a supported operating system.

## Status

This is an unofficial rebuild.

The RPMs built from this repository are not official packages from Red Hat, CentOS, AlmaLinux, NLnet Labs, or any other upstream vendor.

## Important Notice

Use at your own risk.

No warranty is provided. The author does not guarantee security, compatibility, stability, correctness, or fitness for production use.

CentOS 7 has reached end of life. Even if this package can be rebuilt, it does not mean that the entire operating system is secure, maintained, or supported.

Production use is strongly discouraged unless the package is independently reviewed, tested, and approved by the organization responsible for the target system.

## Scope

This repository may include:

* RPM spec file changes
* Build notes
* mock build logs
* Rebuild instructions
* Verification notes
* RPM dependency investigation results

This repository does not provide full CentOS 7 lifecycle support.

## Copyright and License

Unbound itself, upstream source code, and original packaging materials remain under their respective upstream copyrights and licenses.

This repository may contain modifications for rebuild and verification purposes. Only the original changes authored in this repository are copyright of the repository author, unless otherwise stated.

No ownership is claimed over Unbound, AlmaLinux, Red Hat, CentOS, NLnet Labs, or any third-party project.

All trademarks and product names belong to their respective owners.

## Disclaimer

This repository is provided for research, verification, and educational purposes.

The author is not responsible for any damage, data loss, service outage, security incident, compliance issue, or operational problem caused by using this repository or packages built from it.

Before using any generated RPM, review the spec file, verify dependencies, check signatures or checksums if applicable, and test in an isolated environment.

## Recommended Use

Recommended usage:

* Build in a clean mock environment
* Test only in a lab or staging environment
* Compare dependencies with the target CentOS 7 environment
* Review all spec file changes
* Do not assume security support
* Plan migration to a supported OS

## Repository Name

`unbound-el7-rebuild`

This name indicates that the repository is an unofficial rebuild targeting EL7 compatible environments.

