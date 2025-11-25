# Homelab Infrastructure

This repository contains a production-style homelab environment designed to simulate real-world infrastructure operations and failure scenarios.

## Environment Overview
- Operating System: Ubuntu Server (LTS)
- Remote Access: SSH from Windows client
- Storage: Logical Volume Manager (LVM) with dynamic volume expansion
- Hardware: Repurposed laptop acting as a dedicated server node

## Objectives
- Practice real-world Linux server operations
- Simulate and handle infrastructure failure scenarios
- Design and test backup, recovery, and rollback strategies

## Deployed Services
- Nextcloud (self-hosted collaboration platform)
- NGINX (reverse proxy and web server)
- OpenSSH

## Incident Reports
- Failed Nextcloud upgrade leading to service outage – resolved via full data and database restoration
