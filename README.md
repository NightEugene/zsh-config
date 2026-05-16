# zsh-config
NightEugene's zsh configuration

## Theme Installation

1. Clone repository
```sh
git clone https://github.com/NightEugene/zsh-config.git
```

2. Copy theme
```sh
cp zsh-config/themes/nighteugene.zsh-theme $ZSH/themes/
```

3. Modify ```~/.zshrc```: set ```ZSH_THEME``` to ```"nighteugene"```
```
ZSH_THEME="nighteugene"
```

## Root update

```sh
sudo cp -r {~/.oh-my-zsh,~/.zshrc} /root/
```
