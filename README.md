# gpg
Helpful GPG Aliases 

## Install

```bash
git clone https://github.com/marvinroman/oh-my-zsh-gpg-plugin.git ~/.oh-my-zsh/custom/plugins/gpg
```

To use it, add gpg to the plugins array of your zshrc file:
```
plugins=(... gpg)
```

## Aliases
Alias | Command | Use | Description
--- | --- | --- | ---
`gpglk` | `gpg --list-secret-key --keyid-format LONG` | `gpglk [email]` | Prints out secret key in long format
`gpgep` | `gpg --armor --exort` | `gpgep [email]` | Export the public key for key of the given email
