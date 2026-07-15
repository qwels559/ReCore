<p align="center">
  <img src="https://img.shields.io/github/actions/workflow/status/qwels559/ReCore/ci.yml?label=CI&style=flat-square" alt="CI">
  <img src="https://img.shields.io/badge/release-v1.20--26.32-blue?style=flat-square" alt="release">
</p>

<p align="center">
  <img src="https://img.shields.io/discord/000000000000000000?label=discord&style=flat-square&color=5865F2" alt="discord">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/downloads%40total-1.2k-brightgreen?style=flat-square" alt="downloads total">
  <img src="https://img.shields.io/badge/downloads%40latest-340-brightgreen?style=flat-square" alt="downloads latest">
</p>

<h1 align="center">ReCore</h1>

<p align="center">
High-performance server software for Minecraft: Bedrock Edition, forked from NetherGamesMC.
</p>

---

### What is this?

ReCore is a customizable server software for Minecraft: Bedrock Edition, built on top of PocketMine-MP and merged with NetherGamesMC's core optimizations. Supported protocol range: **1.20 – 26.32**, PHP 8.2+.

If you want to run a Bedrock server with **custom features** and **high player capacity**, this is what you're looking for.

- 🚀 **NetherGamesMC-grade optimizations** — networking and core fixes ported straight from a large-scale production network.
- 🔌 **API 5.0** — plugins are written the same way as for PocketMine-MP, so the existing plugin ecosystem works out of the box.
- 🌍 **Multi-protocol support** — players on different Bedrock client versions can connect to the same server.
- 📦 **High capacity** — built to hold larger player counts on a single instance, depending on hardware and plugins.

---

### Installation

**Requirements**

- PHP 8.2 or newer, with these extensions: `pthreads` or ext-parallel is not required, but `ctype`, `curl`, `mbstring`, `sockets`, `openssl`, `yaml` should be enabled.
- Linux, Windows, or macOS. Linux is recommended for production servers.
- At least 1 GB of RAM for a small server; scale up depending on expected player count.

**Steps**

1. Download the latest ReCore build from the [Releases](../../releases) page, or clone this repository and build it yourself.
2. Extract the archive into the folder where you want the server to run.
3. Make sure PHP is installed and available in your system `PATH`. Check with:
   ```bash
   php -v
   ```
4. Run the start script for your platform:
   ```bash
   # Linux / macOS
   ./start.sh

   # Windows
   start.cmd
   ```
5. On first launch, the server will generate its configuration files (`server.properties`, `pocketmine.yml`, etc.). Stop the server, edit them as needed, then start it again.
6. Open the port you configured (default `19132/UDP`) on your firewall or router if you're hosting from a home network.
7. Connect to the server from Minecraft: Bedrock Edition using your IP and port.

**Updating**

Stop the server, back up your `worlds/` and `plugins/` folders, replace the core files with the new release, then start the server again.

---

### Feedback

Discord: https://discord.gg/qwel11s

---

<p align="center">© ReCore Project</p>
