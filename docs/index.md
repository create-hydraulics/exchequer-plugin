# Exchequer Deployment Overview

Exchequer is a high-fidelity macroeconomic simulation engine designed for modern Minecraft server environments. It replaces traditional static fiat economies with dynamic loops encompassing taxation, inflation, fractional banking, and responsive market values.

## System Prerequisites

Before initializing the plugin, verify that your host meets the operational requirements below:

* **Platform Environment:** Paper, Purpur, or Folia. Traditional Spigot pipelines are explicitly unsupported due to synchronous asset handling limitations.
* **Java Runtime:** Java 21 or higher.
* **Storage Engine:** SQLite (Local/Default) or MySQL 8.0+ / MariaDB (Recommended for distributed proxy networks).
* **Core Bridge:** Vault API framework or a native direct hook mapping implementation.

## Initial Installation

1. Download the latest release distribution binary from the official BuiltByBit resource panel.
2. Place the file into your server's `/plugins/` subdirectory.
3. Restart the server instance to generate default configuration directories and establish the database schemas.
