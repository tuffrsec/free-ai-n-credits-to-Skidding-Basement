
Free AI (FA) — Powered by Skidding Basement


⚖️ Copyright & Distribution Notice

Copyright © 2026 Skidding Basement. All Rights Reserved.
• Authorized Distribution: Unauthorized leaking or hosting of this repository/files across servers like Skidding HQ is strictly prohibited.
• Permitted Leakers: Only Skid Leaks (aka Jolly skid) has explicit authorization to re-leak or distribute these setup assets.
• Consequences: Any distribution without formal validation from leadership will face immediate administrative and communal consequences.
• Permissions: Direct Message nexo_juan or setfpscap on Discord to request official distribution rights.
Free AI (FA) is an open-source, AGPL-v3 licensed Python proxy wrapper. It routes 12 AI coding assistants through 61 AI providers with built-in token optimization and fallback infrastructure.

🚀 Quick Start

1. Install:
	• macOS/Linux: curl -fsSL "https://raw.githubusercontent.com/Alishahryar1/free-claude-code/main/scripts/install.sh" | sh
	• Windows: & ([scriptblock]::Create((irm "https://raw.githubusercontent.com/Alishahryar1/free-claude-code/main/scripts/install.ps1")))
2. Start Proxy: Run fcc-server or launch the desktop app to access the Admin UI.
3. Add Provider: Input keys under Providers (e.g., NVIDIA NIM, Gemini) and choose a model.
4. Run Client: Execute agent launch codes in your terminal:
	• fcc-claude (Claude Code)
	• fcc-codex (Codex)
	• fcc-cline (Cline)
	• fcc-aider (Aider)
5. if you have problems installing through the command please install the zip in the repo.
# if anything dm us  cuz ai did not cook with the quick install help shi
🔌 IDE & App Integrations

Connect client workflows via Admin UI → Integrations:
• VS Code / Chat: Activate integration and select your model via native pickers.
• Claude Desktop: Fully exit the application, click connect inside the UI, and relaunch.
• JetBrains: Select Claude Code (FCC) after restarting your target IDE environment.
• Custom Environments: Adjust endpoint configuration to point to http://127.0.0.1:8082/v1.

💬 Chat Platform Hooks

Bind active sessions to Discord or Telegram wrappers via Admin UI → Messaging.
• Converts user-submitted audio notes into text strings via local Whisper or NVIDIA NIM matrices.
• Chat Commands: Use /stats for system metrics, /stop to abort execution, or /clear to wipe parameters.

🛠️ Diagnostics & Updates

• Check Version: fcc-server --version
• Debug Tool: fcc-doctor (generates detailed system logs for debugging)
• Pull Updates: Kill active wrapper environments, then run fcc-update
• Complete Purge:
	• macOS/Linux: curl -fsSL "https://raw.githubusercontent.com/Alishahryar1/free-claude-code/main/scripts/uninstall.sh" | sh
	• Windows: & ([scriptblock]::Create((irm "https://raw.githubusercontent.com/Alishahryar1/free-claude-code/main/scripts/uninstall.ps1")))
