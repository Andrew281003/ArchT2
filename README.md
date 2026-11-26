# ArchT2

ArchT2 is an experimental project exploring a documented, reproducible Arch Linux software stack for Apple computers equipped with the T2 security chip. The initial target is the Apple MacBookPro16,1 model identifier.

> **Status: Experimental — Phase 0.** This repository is being initialized. Hardware compatibility has not been verified, and no installation or support claims are made. Do not use this project as an installation guide for a working computer.

## Goals

- Record the target hardware and evidence about its interfaces and constraints.
- Develop a maintainable, auditable path toward an Arch Linux environment for the target.
- Keep project-authored code under GPL-3.0 while retaining the original licenses of third-party work.
- Avoid distributing Apple firmware or other proprietary material unless redistribution rights are verified.

## Primary target

The initial target is **MacBookPro16,1**. This is a target identifier, not a compatibility statement. Hardware behavior, required components, and installation steps remain under investigation. See [`docs/hardware/`](docs/hardware/) for the planned documentation area; validated findings will be recorded with evidence before they are treated as supported.

## Development status

The project is in **Phase 0: project and research groundwork**. No drivers, firmware, install image, or hardware support are promised by this initial repository. See [ROADMAP.md](ROADMAP.md) for phase exit criteria.

## Repository map

- `docs/` — architecture, hardware, research, and benchmark notes
- `kernel/`, `drivers/`, `firmware/` — future kernel, driver, and firmware-related work
- `packages/`, `iso/`, `installer/` — future packaging and installation work
- `profiles/MacBookPro16,1/` — target-specific profile work
- `scripts/`, `diagnostics/`, `tests/`, `configs/` — tooling and configuration, when justified

Empty directories are retained with `.gitkeep` placeholders. No speculative drivers or configurations are included.

## Licensing

Original project code is licensed under GNU GPL version 3.0; see [LICENSE](LICENSE). Third-party components retain their respective licenses and notices. Do not assume that firmware or other vendor materials may be redistributed.

## Contributing and security

Read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing changes. Please report suspected vulnerabilities privately through GitHub Security Advisories for this repository if private reporting is enabled. If it is unavailable, contact a repository owner privately; do not post exploit details in a public issue. See [SECURITY.md](SECURITY.md).
