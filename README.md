## Installation

### 1. Download Configuration

**Bash / Zsh:**

```bash
mkdir -p ~/.config/fastfetch && \
curl -sSL https://raw.githubusercontent.com/Miho1254/fastfetch-dotfiles/main/groups.jsonc -o ~/.config/fastfetch/groups.jsonc && \
curl -sSL https://raw.githubusercontent.com/Miho1254/fastfetch-dotfiles/main/elaina.png -o ~/.config/fastfetch/elaina.png

```

**Fish:**

```fish
mkdir -p ~/.config/fastfetch
curl -sSL https://raw.githubusercontent.com/Miho1254/fastfetch-dotfiles/main/groups.jsonc -o ~/.config/fastfetch/groups.jsonc
curl -sSL https://raw.githubusercontent.com/Miho1254/fastfetch-dotfiles/main/elaina.png -o ~/.config/fastfetch/elaina.png

```

### 2. Set Alias (Optional)

Bind `ff` to quickly launch the preset:

* **Zsh:** `echo "alias ff='fastfetch --config groups'" >> ~/.zshrc && source ~/.zshrc`
* **Bash:** `echo "alias ff='fastfetch --config groups'" >> ~/.bashrc && source ~/.bashrc`
* **Fish:** `alias -s ff="fastfetch --config groups"`

---

## File Structure

```text
~/.config/fastfetch/
├── groups.jsonc
└── elaina.png

```

## Usage

```bash
fastfetch --config groups
# or
ff

```
