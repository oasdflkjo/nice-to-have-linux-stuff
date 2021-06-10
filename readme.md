# Nice to have linux stuff

install oh my posh
https://ohmyposh.dev/docs/linux


put these lines to ~/.bashrc

tab completes names
```bash
bind '"\t":menu-complete'
```

tab ignores cases
```bash
bind 'set completion-ignore-case on'
```
minimal ohmyposh theme

terminal emulator has to have fonts that support special characters

```bash
eval "$(oh-my-posh --init --shell bash --config ~/.poshthemes/stelbent.minimal.omp.json)"
```

