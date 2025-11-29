Odoo 15 Core (Minimal Clean Version)

This repository contains a clean, minimal, production-ready core version of Odoo 15, extracted and optimized specifically for Docker and high-performance deployments.
It includes only the essential files required to run Odoo, without documentation, tests, packaging files, or development extras — resulting in a smaller, faster, and cleaner base.

🚀 Features
Minimal Odoo 15 Core
Only essential files required to launch Odoo:

odoo/ (framework, core)
odoo-bin
requirements.txt
setup.py
LICENSE
COPYRIGHT

Removed unnecessary directories
(doc/, .github/, .tx/, debian/, tests, etc.)

Lightweight and optimized
Perfect base for Odoo SaaS, multi-tenant platforms, and custom builds
It does not work without the addons folder located here:
https://github.com/autocme/odoo-core-addons
