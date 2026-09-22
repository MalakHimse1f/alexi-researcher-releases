# Alexi Researcher

A notebook where your own agent does the upfront work: ask for something and the answer lands as notes, tasks, tables and
canvases. Local only — no account, no cloud, no API key. It runs on the Claude Code or Codex (ChatGPT) sign-in you
already have; your data stays in `~/.alexi-researcher`.

## Download

- **Mac** with Apple silicon: [Alexi-Researcher-arm64.dmg](https://github.com/MalakHimse1f/alexi-researcher-releases/releases/latest/download/Alexi-Researcher-arm64.dmg)
- **Mac** with an Intel processor: [Alexi-Researcher-x64.dmg](https://github.com/MalakHimse1f/alexi-researcher-releases/releases/latest/download/Alexi-Researcher-x64.dmg)
- **Windows** 10 or 11: [Alexi-Researcher-Setup.exe](https://github.com/MalakHimse1f/alexi-researcher-releases/releases/latest/download/Alexi-Researcher-Setup.exe)

Drag the app into Applications (macOS) or run the installer (Windows: for you only, no administrator). The builds are
not notarized yet, so the first start asks once: on macOS click **Done**, then **System Settings → Privacy & Security →
Open Anyway**; on Windows click **More info → Run anyway**.

You need Claude Code (`npm install -g @anthropic-ai/claude-code`, then `claude` and /login) or Codex
(`npm install -g @openai/codex`, then `codex login`). For a Claude sign-in that nothing else on the computer can
rotate away, run `claude setup-token` and paste the token in the app's Settings.

The app updates itself from this page: the **Update** pill beside the ask field, or Settings → Check for updates.
