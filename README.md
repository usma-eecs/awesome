# Awesome EECS

This is an awesome list of awesome things curated by the USMA EECS community. [Explore more awesome lists on GitHub.](https://github.com/topics/awesome)

## Useful Classroom Tools

- [ClassTime](https://classtime.bhatia.dev/) - A helpful classroom timer
- [CircuitPython Code Editor](https://code.circuitpython.org/) - IDE to work with microcontrollers like [Circuit Playground Bluefruit](https://www.adafruit.com/product/4333)

## Python

- [uv](https://docs.astral.sh/uv/) - Python package and project manager

#### Install uv - one-liner

```sh
winget install astral-sh.uv # on Windows
dnf install uv # on Fedora Linux
brew install uv # on MacOS or Linux with Homebrew
```

#### Run a Python script

`uv` reads `pyproject.toml` from the local directory to automatically create a Python virtual environment with the correct version of Python with all project dependencies and then runs the script as expected. Use the following command-

```sh
uv run script.py # automatically detects or installs Python
```

## Agentic Software Engineering

### Coding Harnesses

- [OpenCode](https://opencode.ai/) - model-agnostic agentic coding environment
- [pi.dev](https://pi.dev/) - minimal agent harness
- [RayChat](https://github.com/raychatllm/raychat) - Pure-Python coding chat harness with plugin-based tools, providers and sub-agents using only the standard library
- [omp.sh](https://omp.sh/) - coding agent with IDE wired in, built on a native Rust core for reliable agentic workflows

### Studies, Talks, Benchmarks

- [An Empirical Study of Harness Design for Coding Agents](https://arxiv.org/abs/2609.20804) - arXiv study of how planning, action space and context management affect coding agent performance on SWE-Bench and Terminal-Bench
- [Agentic Software Engineering talk](https://bhatia.dev/talks/agentic-software-engineering) - moving from vibe coding to disciplined, artifact-driven agentic systems engineering
- [Pelican riding a bicycle](https://simonwillison.net/tags/pelican-riding-a-bicycle/) - Simon Willison's LLM benchmark archive tracking SVG generation of a pelican on a bicycle across models

## Military Resources

### Publications

- [Army Publishing Directorate](https://armypubs.army.mil/) - Official Army publications, regulations and manuals
- [Center for Army Lessons Learned](https://www.army.mil/CALL) - Excellent, largely public CALL publications
- [DoD Cyber Exchange](https://public.cyber.mil/) - DoD cybersecurity resources and tools
- [Army University Press](https://www.armyupress.army.mil/) - Professional military education articles, podcasts and CSA recommendations
- [Cyber Defense Review](https://cyberdefensereview.army.mil/) - professional journal on cyber operations

### AI Providers

- [GenAI.mil](https://genai.mil/) - Enterprise generative AI platform
- [code.genai.mil](https://code.genai.mil/) - GenAI coding environment
- [CodeAI](https://www.codeai.mil/) - CodeAI portal for agentic development

## Cyber, Security, and Privacy

### Linux

- [Project Bluefin](https://projectbluefin.io/) - Lightweight atomic image-based Linux distro for reliability and security
- [Fedora IoT](https://fedoraproject.org/iot/) - Container-based host optimized for SBCs and IoT devices like Raspberry Pi
- [Fish Shell](https://fishshell.com/) - User-friendly shell with syntax highlighting, autosuggestions and tab completions
- [Linux Notes for Professionals](https://goalkicker.com/LinuxBook/LinuxNotesForProfessionals.pdf) - Comprehensive Linux reference book

### Learning Resources

- [Privacy Guides](https://www.privacyguides.org/) - Curated privacy-focused tools and recommendations
- [MITRE ATT&CK](https://attack.mitre.org/) - Knowledge base for adversary tactics and techniques
- [Kali](https://www.kali.org/) - Penetration testing Linux distribution with a massive security tool collection

###  Tracker, Ad-blockers, Malware Protection

- [Cloudflare for Families](https://blog.cloudflare.com/introducing-1-1-1-1-for-families/) - DNS-based malware protection
- [Pi-hole](https://pi-hole.net/) - network-wide DNS-based ad blocker
- [OPNsense](https://opnsense.org/) - open-source firewall
- [NextDNS](https://nextdns.io/) - DNS-based tracker blocker

### Self-hosted services

- [Tailscale](https://tailscale.com/) - Mesh networking / personal VPN for devices
- [Syncthing](https://syncthing.net/) - file synchronization across devices
- [Bitwarden](https://bitwarden.com/) - Password manager; [can be self-hosted](https://github.com/dani-garcia/vaultwarden)

### Messaging & Privacy

- [Signal Messenger](https://signal.org/) - Non-profit encrypted messaging, voice and video calls
- [ProtonMail](https://protonmail.com/) - Encrypted email service

## Computing and Technology

- [Hackaday](https://hackaday.com/) - Community site for hardware hacks and DIY projects
- [DevDocs.io](https://devdocs.io/) - Fast, offline-capable documentation browser for APIs
- [Visual Studio Code](https://code.visualstudio.com/) - Popular extensible code editor for developers
- [Marimo](https://marimo.app/) - Reactive Python notebook for interactive computing
- [GitHub Pages](https://pages.github.com/) - Free hosting for static websites and JavaScript apps

## Learning and Productivity

- [Zettelkasten](https://zettelkasten.de/) - Integrated thinking method for note-taking
- [About, Ideas, Now](https://aboutideasnow.com/) - Resource for learning and productivity ideas

## More Awesome Stuff

- [Track Awesome List](https://www.trackawesomelist.com/) - Discover and track awesome lists across GitHub
- Another curated awesome list: [bhatia.dev/awesome](https://bhatia.dev/awesome)
