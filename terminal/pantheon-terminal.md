Apply the desired crunchbang theme to pantheon-terminal by pasting the corresponding block of `gsettings` commands into the terminal.

The first theme features a background with slight (5%) translucency, like the background in the default pantheon-terminal theme. The second features a solid background.

### translucent background

```
gsettings set org.pantheon.terminal.settings background 'rgba(46, 52, 54, 0.95)'
gsettings set org.pantheon.terminal.settings foreground '#dfdfdf'
gsettings set org.pantheon.terminal.settings cursor-color '#bfbfbf'
gsettings set org.pantheon.terminal.settings palette '#3b4245:#c48d93:#6fa868:#ab9a6a:#75a0bd:#c48d93:#68a6a8:#dfdfdf:#999999:#bf9277:#6fa868:#ab9a6a:#75a0bd:#bd8ea1:#68a6a8:#a793c4'
```

### solid background

```
gsettings set org.pantheon.terminal.settings background '#2e3436'
gsettings set org.pantheon.terminal.settings foreground '#dfdfdf'
gsettings set org.pantheon.terminal.settings cursor-color '#bfbfbf'
gsettings set org.pantheon.terminal.settings palette '#3b4245:#c48d93:#6fa868:#ab9a6a:#75a0bd:#c48d93:#68a6a8:#dfdfdf:#999999:#bf9277:#6fa868:#ab9a6a:#75a0bd:#bd8ea1:#68a6a8:#a793c4'
```
