# Mateus Pim Santos

**Software Engineer · Backend & Platform** · Python · distributed systems · Linux

By day I build backend systems in Python: APIs, queues and multi-tenant
platforms on PostgreSQL and Kubernetes. After hours I build practical tools for
Linux desktops, self-hosted systems and local AI. Lately that means the Oma* family:
Omarchy plugins and terminal apps that turn everyday hardware, gaming, and
workflow problems into simple controls.

## Oma* projects

| Project | What it does |
| --- | --- |
| [OmaMods](https://github.com/mateuspim/omamods) | Terminal mod manager for Linux game libraries: finds Steam and Heroic games, stages Nexus Mods and AyakaMods downloads, and installs with per-file records so every mod can be reverted. |
| [OmaDroid](https://github.com/mateuspim/omadroid) | Android on Omarchy: discover ADB devices, then mirror and control them with scrcpy from the bar, with audio and webcam sessions. |
| [OmaTrophy](https://github.com/mateuspim/omatrophy) | Steam achievement unlocks as bronze-to-platinum trophy toasts over your games, with a trophy cabinet in the bar. No API key, works with a private profile. |
| [OmaReach](https://github.com/mateuspim/omareach) | Blacks out monitor edges you can't reach and keeps the bar and tiled windows in the rest; the edges can show a clock, the logo, or a btop-style dashboard. |
| [Volta for Omarchy](https://github.com/mateuspim/omarchy-volta) | Independent left and right output volume and stereo balance on the Omarchy bar. |
| [Mosaic for Omarchy](https://github.com/mateuspim/omarchy-mosaic) | Tiles web apps like Twitch, Kick, and YouTube on Hyprland, keeping each video's fullscreen inside its tile. |

Install every Omarchy plugin at once with `curl -fsSL pymdev.com/install | bash`,
or pick some: `curl -fsSL pymdev.com/install | bash -s -- omatrophy volta`.

## More tools

- [Kvasir](https://github.com/mateuspim/kvasir): local, OpenAI-compatible endpoint for coding agents that runs a 125B mixture-of-experts model (Qwen3.8 Flash-Next) on a 16 GB graphics card; 113-131 tok/s on an RTX 4080 and 100/100 on a hard multi-turn opencode test.
- [tela](https://github.com/mateuspim/tela): Android app for browsing Wallhaven and setting wallpapers, with no backend, accounts or tracking. [Download the APK](https://github.com/mateuspim/tela/releases/latest).
- [scrcpy-connect](https://github.com/mateuspim/scrcpy-connect): standalone Python CLI for wireless ADB and scrcpy; OmaDroid is its Omarchy successor.
- [homelab](https://github.com/mateuspim/homelab): two Proxmox nodes, one for the house's media, photos, files, passwords and git, one for AI agent and dev workspaces, reachable through Tailscale and backed up encrypted off-site.

## Forks I maintain

- [distrobox-gaming](https://github.com/mateuspim/distrobox-gaming), from akitaonrails: reproducible Arch-based gaming and emulation Distrobox built with Ansible.
- [aitrepreneur-docker](https://github.com/mateuspim/aitrepreneur-docker), from akitaonrails: selected AI tools in Docker with pinned versions and persistent data.

## What I can do

- **Backend & platform builds**: APIs, queues and multi-tenant platforms in Python, from the first commit to a running deployment.
- **Performance & database tuning**: N+1 queries, slow PostgreSQL and heavy background jobs, measured before and after.
- **Tests & API contracts**: typed clients generated from OpenAPI, contract-drift checks in CI, and test suites a team can trust.
- **CRM, contact center & WhatsApp**: WhatsApp Business API, chatbots, queues and operator backoffices.
- **Cloud, CI/CD & Kubernetes**: container builds, pipelines and rollouts on OCI or AWS, with secrets, access and TLS set up properly.
- **Linux tools & automation**: CLIs, desktop tools and automation that remove manual steps from a workflow.

Start a project: [mateus@pymdev.com](mailto:mateus@pymdev.com), or `curl pymdev.com/services`.

## Find me

- [pymdev.com](https://pymdev.com), or `curl pymdev.com` from a terminal
- [LinkedIn](https://www.linkedin.com/in/mateuspimsantos/)
- [X](https://x.com/mateus_pym)
