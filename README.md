# 10 Ways to Ruin Your Proxmox Setup - And How Not To

This repository contains the source code for the book **"10 Ways to Ruin Your Proxmox Setup - And How Not To"**.

## About the Book

Proxmox VE is a powerful virtualization platform, but common configuration mistakes can lead to performance issues, instability, or data loss. This guide explores ten critical mistakes and provides detailed advice on how to avoid them.

Topics covered include:
*   ZFS RAM planning and ECC memory myths
*   Storage topology (RAIDZ vs Mirrors) for VMs
*   Local-LVM vs ZFS
*   CPU type configuration
*   High Availability (HA) prerequisites
*   Backup strategies and Proxmox Backup Server
*   Docker on the host vs VMs
*   Monitoring
*   Service deployment best practices

## Format

The book is written in **AsciiDoc**.

*   `index.adoc`: Main entry point.
*   `chapters/`: Individual chapters.
*   `images/`: Figures and illustrations.

## Building

(Add build instructions here, e.g., using `asciidoctor-pdf`)
