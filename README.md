# Cline Bangla — VS Code-এ বাংলায় AI কোডিং

Bangla rules for Cline, built on **cline/cline**.

- **Original repo:** https://github.com/cline/cline (autonomous coding agent as an SDK, IDE extension, or CLI assistant)

## কী আছে / What is inside

- `.clinerules` — project rules in Bangla. Cline reads `.clinerules` files automatically (VS Code extension, JetBrains plugin and CLI) and follows them in every task.

## যা ঠিক করা হয়েছে / What was fixed

- Upstream ships with no rules file at all — Cline starts with generic English behaviour. This adds the missing piece: Bangla conversation, small steps, no placeholder code, no secrets in code, ask before adding libraries.

## ব্যবহার / How to use

1. Install Cline from the VS Code Marketplace (`saoudrizwan.claude-dev`) or JetBrains Marketplace — links are in the upstream README.
2. Copy `.clinerules` into your project's root folder.
3. Open Cline in VS Code and write your task in Bangla — it will answer in Bangla and explain each change in Bangla, while keeping code and comments in English.
