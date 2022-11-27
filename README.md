# zsh go completions

Move to [https://github.com/syohex/zsh-misc-completions](https://github.com/syohex/zsh-misc-completions)

My own zsh completion collections

- godoc
- [gom](https://github.com/mattn/gom)
- [peco](https://github.com/peco/peco)
- [byzanz-window](https://github.com/syohex/byzanz-window)
- [alp](https://github.com/tkuchiki/alp)

## Requirements

- [gopkgs](https://github.com/haya14busa/gopkgs) for godoc completion

## How to Use

### Download Repository

```
% git clone https://github.com/syohex/zsh-go-completions.git ~/.zsh/go-completions
% rm ~/.zcompdump # remove cache
```

### Zsh configuration

Add following code to your zsh configuration file(such as `~/.zshrc`)

```sh
fpath=(~/.zsh/go-completions $fpath)
```

### ScreenCast

#### peco

![peco](image/peco.gif)
