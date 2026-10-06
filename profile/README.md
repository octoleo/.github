<h1 align="center">OctoLeo</h1>

<p align="center"><strong>Powerful tools. Practical automation.</strong></p>
<p align="center">Build Joomla environments, automate releases, and take command of your infrastructure.</p>

<p align="center">
  <a href="https://git.vdm.dev/octoleo"><img src="https://img.shields.io/badge/Bash-Automation-4EAA25?style=for-the-badge&amp;logo=gnubash&amp;logoColor=white" alt="Bash automation"></a>
  <a href="https://git.vdm.dev/octoleo/octojoom"><img src="https://img.shields.io/badge/Docker-Environments-2496ED?style=for-the-badge&amp;logo=docker&amp;logoColor=white" alt="Docker environments"></a>
  <a href="https://git.vdm.dev/octoleo/octojpack"><img src="https://img.shields.io/badge/Joomla-Tooling-5091CD?style=for-the-badge&amp;logo=joomla&amp;logoColor=white" alt="Joomla tooling"></a>
  <a href="https://git.vdm.dev/octoleo/git-user"><img src="https://img.shields.io/badge/Git-Native_workflows-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Native Git workflows"></a>
</p>

<p align="center">
  <a href="https://git.vdm.dev/octoleo/octojoom"><strong>Discover OctoJoom</strong></a>
  &nbsp;·&nbsp;
  <a href="https://git.vdm.dev/octoleo"><strong>Explore the projects</strong></a>
</p>

---

OctoLeo creates tools that turn demanding development and operations tasks into repeatable workflows. From a focused Bash utility to a complete Joomla Docker environment, each project gives you practical control over a specific part of your work: deploying services, building packages, preparing Git, managing infrastructure, or measuring your machine.

The **Octo family** is the heart of the toolkit. **OctoJoom** leads the way, supported by tools you can use independently or combine into larger workflows. **JoomEngine** supplies Joomla Component Builder Docker images, while **Git-User** prepares the native Git environment that release automation depends on.

## OctoJoom — the flagship

<p align="center">
  <a href="https://git.vdm.dev/octoleo/octojoom"><img src="https://git.vdm.dev/octoleo/octojoom/raw/branch/master/graphics/OctoJoomAlt.png" alt="OctoJoom — Easy Joomla Docker Deployment" width="180"></a>
</p>

### Your Joomla development environment, under your control

[**OctoJoom**](https://git.vdm.dev/octoleo/octojoom) brings Joomla Docker environments into one terminal workflow. Set up Joomla, MariaDB, and phpMyAdmin; add OpenSSH workspaces; and manage routing and HTTPS with Traefik. Interactive menus and direct CLI task flags make initial setup and everyday container management easier.

| Capability | What it brings to your workflow |
| --- | --- |
| **Complete Joomla stacks** | Deploy Joomla with its database and database administration tools. |
| **OpenSSH workspaces** | Give developers SSH access to containerized workspaces. |
| **Routing and HTTPS** | Use Traefik for service routing and Let's Encrypt certificates, including optional Cloudflare DNS challenges. |
| **Flexible image sources** | Choose Joomla, JoomEngine, or custom images to suit the environment you are building. |
| **Persistent settings and data** | Retain configuration between runs and manage persistent Joomla volumes. |
| **Management at scale** | Use bulk deployment and container lifecycle operations, with Portainer available for visual management. |

Start with OctoJoom when you need repeatable Joomla environments for extension development, Joomla Component Builder, or a shared development server.

**[Explore OctoJoom and its setup guide →](https://git.vdm.dev/octoleo/octojoom)**

## The Octo toolkit

### Package, publish, and synchronize

Move from source repositories to distributable packages, then keep your release metadata and shared files in step.

| Project | What it does | Best for |
| --- | --- | --- |
| [**OctoJpack**](https://git.vdm.dev/octoleo/octojpack) | Builds installable Joomla packages from multiple extensions using JSON configuration and environment variables, with package XML, checksums, and a build manifest. | Repeatable releases that combine several extension repositories. |
| [**OctoShoom**](https://git.vdm.dev/octoleo/octoshoom) | Downloads ZIPs referenced by Joomla update XML, calculates SHA-512 hashes, updates the XML, and commits the changes. | Joomla update servers that need current archive checksums. |
| [**OctoPower**](https://git.vdm.dev/octoleo/octopower) | Packages reusable Joomla Component Builder Powers into Composer PHP packages through declarative configuration. | Distributing and consuming JCB Power classes through Composer. |
| [**OctoZipo**](https://git.vdm.dev/octoleo/octozipo) | Turns ZIP packages into repositories, updates existing repositories, and creates version tags using configurable destination mappings. | Build archives that need to become browsable, versioned repositories. |
| [**OctoSync**](https://git.vdm.dev/octoleo/octosync) | Synchronizes selected files and folders across GitHub repositories, with pull-request or direct-merge operation. | Shared assets and configuration maintained across several repositories. |

### Provision and operate infrastructure

Bring remote machines, edge configuration, and shared automation resources into your terminal workflows.

| Project | What it does | Best for |
| --- | --- | --- |
| [**OctoSail**](https://git.vdm.dev/octoleo/octosail) | Provisions Amazon Lightsail instances, runs remote workloads, transfers files and results, and automates cleanup. | Jobs that need a temporary remote machine for their complete lifecycle. |
| [**OctoFlare**](https://git.vdm.dev/octoleo/octoflare) | Automates Cloudflare DNS, redirects, cache, TLS, Workers, Pages, and tunnels through CLI and workflow commands. | Repeatable infrastructure and edge configuration. |
| [**Octodinator**](https://git.vdm.dev/octoleo/octodinator) | Coordinates shared initialization and cleanup across overlapping automation scripts. | Concurrent jobs whose shared resources must outlive any one script. |
| [**OctoLanding**](https://git.vdm.dev/octoleo/octolanding) | Serves a lightweight static landing page from a BusyBox Docker image, with an optional mounted document root. | Infrastructure entry points, proxy fallbacks, and maintenance endpoints. |

### Diagnose systems and process recordings

Use focused tools to collect useful measurements, troubleshoot services, and turn long recordings into working text.

| Project | What it does | Best for |
| --- | --- | --- |
| [**OctoBench**](https://git.vdm.dev/octoleo/octobench) | Measures CPU, memory, storage, USB, and folder-transfer performance on Ubuntu/Debian with one command and a Desktop JSON report. | Practical measurements of a workstation and its storage. |
| [**OctoMailTest**](https://git.vdm.dev/octoleo/octomailtest) | Diagnoses mail DNS, SMTP, IMAP, TLS, authentication, and deliverability, with text, JSON, and Markdown reports. | Systematic mail checks and reports for people and workflows. |
| [**OctoScribe**](https://git.vdm.dev/octoleo/octoscribe) | Transcribes long recordings from Telegram or local folders, writes comparison reports, and tracks progress in a persistent manifest. | Repeatable transcription of long recordings with reviewable results. |

## JoomEngine — Joomla Component Builder, ready in Docker

[**JoomEngine**](https://git.vdm.dev/octoleo/joomengine) builds the official Joomla Component Builder Docker images. A fresh deployment installs Joomla and JCB automatically, giving you a prepared development environment with optional extension installation and Joomla CLI automation.

Choose Apache, FPM, or FPM-Alpine variants for supported Joomla and PHP combinations. Use the images directly or select JoomEngine as your image source in OctoJoom to bring that environment into the same deployment and management workflow.

**[Explore JoomEngine →](https://git.vdm.dev/octoleo/joomengine)**

## Git-User — native Git, ready for automation

[**Git-User**](https://git.vdm.dev/octoleo/git-user) prepares Git author identity, GPG signing, and SSH authentication on Ubuntu workflow runners. Once the environment is configured, your workflow can use ordinary `git clone`, `git commit`, `git tag`, and `git push` commands with the supplied identity and credentials.

- **Consistent authorship:** set the Git name and email used by automated commits.
- **Commit and tag signing:** configure the supplied GPG key for signed Git operations.
- **SSH authentication:** validate the supplied key pair and configure the selected SSH host, including a custom forge host.
- **Repeatable setup:** recognize an existing matching setup and support explicit reconfiguration when the user changes.

Use it alongside OctoJpack, OctoShoom, OctoZipo, or your own scripts whenever the workflow needs a prepared Git environment.

**[Explore Git-User and its workflow examples →](https://git.vdm.dev/octoleo/git-user)**

## Build a workflow around your work

The tools handle different stages; you choose how they fit together.

| Goal | A practical combination |
| --- | --- |
| **Develop Joomla extensions** | Use [OctoJoom](https://git.vdm.dev/octoleo/octojoom) to manage the environment and [JoomEngine](https://git.vdm.dev/octoleo/joomengine) when you need JCB prepared inside it. |
| **Automate a Joomla release** | Prepare Git with [Git-User](https://git.vdm.dev/octoleo/git-user), build packages with [OctoJpack](https://git.vdm.dev/octoleo/octojpack), then publish the archives before refreshing your update XML hashes with [OctoShoom](https://git.vdm.dev/octoleo/octoshoom). |
| **Run a remote workload** | Use [OctoSail](https://git.vdm.dev/octoleo/octosail) for the machine lifecycle and [OctoFlare](https://git.vdm.dev/octoleo/octoflare) for any Cloudflare configuration the workload needs. |

Each project provides its own setup instructions, configuration options, and usage examples. Open the project that matches your next task and start there.

---

<p align="center"><strong>From one useful command to a complete development workflow.</strong></p>
<p align="center"><a href="https://git.vdm.dev/octoleo"><strong>Explore OctoLeo →</strong></a></p>
