# LoRA Studio — free technical preview

A local browser interface for preparing image datasets, editing captions, and managing LoRA training with an existing AI Toolkit installation.

## Download and try

[Download the application ZIP](https://github.com/TigerFan69/lora-studio-preview/raw/refs/heads/main/lora-studio-preview.zip). No paid membership is required.

1. Extract the ZIP into a new directory on your Linux NVIDIA training host.
2. Read `docs/PREREQUISITES.md` and `docs/INSTALL.md` inside it. You need an existing compatible AI Toolkit environment, Python 3.12, and separately obtained licensed model files. This package does not install the training stack or include models.
3. Follow the installation guide, run the startup command it prints, and open http://127.0.0.1:8765 on the host. Keep the service local/private; it has no login.
4. Start with a small dataset and a short run after confirming the selected model profile. Share redacted setup issues and feedback in this repository's Issues.

Current development focuses on Krea 2 training for 12 GB VRAM cards, with 8 GB as an eventual goal. These are development targets, not established compatibility. The recorded development baseline is Linux with an RTX 4080 16 GB; the existing runtime has local memory changes. A clean-machine install is not verified.

All 36 software tests passed in an isolated copy using the existing training environment. They do not validate GPU memory fit or model quality. Read `docs/VALIDATION.md` in the ZIP for exact limits.

## Seven-day preview

This is a seven-day public preview download window. The public download window closes October 29, 2026 at 11:59 p.m. America/Chicago (CDT). Downloaded MIT-licensed copies remain usable and redistributable; there is no software expiry or remote disable mechanism. Public forks or copies may remain available afterward.

## License and checksum

Studio code is MIT licensed; upstream software and models have separate terms. No datasets, model weights, personal adapters, or credentials are included.

ZIP SHA-256: `3c8dac63985b1d54df03a51464f0424f53280262efed81d2c12719ae4e5937a0`
