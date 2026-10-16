---
name: minecraft-plugin-development
description: Develop and troubleshoot Minecraft Java server plugins with compatibility and permission safety.
---

# Minecraft Plugin Development

Inspect the server software (Paper/Purpur/Spigot), Minecraft version, Java version, plugin API version, build system, and dependencies before editing. Follow existing event, command, configuration, permission, and persistence conventions. Avoid blocking the main server thread with heavy I/O. Validate configuration and handle missing dependencies gracefully. Check plugin compatibility rather than assuming versions match. Test builds and startup logs; back up worlds and configs before server-side changes. Never expose credentials or RCON secrets.
