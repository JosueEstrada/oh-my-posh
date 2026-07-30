### Prerequisites

Install Oh My Posh for your platform:

https://ohmyposh.dev/docs/installation

### Clone the repository

```zsh
git clone https://github.com/JosueEstrada/oh-my-posh.git
```

### Copy the theme

```zsh
mkdir -p "$HOME/.config/oh-my-posh"
cp oh-my-posh/themes/monokai-pro.omp.json "$HOME/.config/oh-my-posh/"
```

### Activate the theme

Add this line to your `~/.zshrc`:

```zsh
eval "$(oh-my-posh init zsh --config "$HOME/.config/oh-my-posh/monokai-pro.omp.json")"
```

Then reload your shell:

```zsh
exec zsh
```

### Other shells

For bash, fish, PowerShell and more, see the Oh My Posh documentation:

https://ohmyposh.dev/docs/installation/customize#set-the-configuration
