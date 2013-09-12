# zsh go completions
* godoc
* gom

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
