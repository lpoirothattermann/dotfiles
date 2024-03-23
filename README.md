# New computer
```
chezmoi init --apply https://github.com/lpoirothattermann/dotfiles.git
```

## Ajout de variables manquantes
Dans le cas ou une variable doit etre ajoutee au ~/.config/chezmoi/config.toml il faut executer la commande suivante pour regener le fichier de configuration, la commande va automatiquement prompt, toutes, les variables dont les manquantes
```
chezmoi init
```

## Customisation (machine-to-machine differences)
Les fichiers dans le repertoire ~/.zshrc.d/ sont automatiquement sourcees.
