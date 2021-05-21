# zsh-bw-autocomplete

> Bitwarden vault search with bw and zsh autocomletion
>
>

Not original code, just wanted to make a public repository for antigen

Original code found here:
https://megamorf.gitlab.io/2021/04/21/add-zsh-autocompletion-to-bitwarden-cli/

# Bitwarden CLI already includes a better structure for zsh autocomlete:

vanilla (.zshrc):

Add the following line in your .zshrc file:

eval "$(bw completion --shell zsh); compdef _bw bw;"

## Installation

### Using Antigen

````shell
antigen bundle cupricreki/zsh-bw-autocomplete
````
