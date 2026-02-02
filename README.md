# Henrik OS

Mac development environment setup in one command.

```bash
curl -fsSL https://raw.githubusercontent.com/henrik392/henrik-os/main/setup.sh | bash
```

## What it does

Sets up a complete development environment: Homebrew, Fish shell, Neovim (LazyVim), Starship prompt, Ghostty terminal, VS Code with vim bindings, Node.js (fnm + corepack), Bun, Deno, Git, SSH keys, and macOS defaults.

## Key decisions

- **Fish shell** with vi bindings, no Oh My Fish
- **fnm** for Node version management, **corepack** for pnpm/yarn
- **Starship** prompt with custom purple palette
- **Caps Lock mapped to Escape** via `hidutil` + LaunchAgent
- **Aura Dark** theme across VS Code, Ghostty, and Starship
