# Nouvel ordinateur
```
chezmoi init --apply https://github.com/lpoirothattermann/dotfiles.git
```

## Ajout de variables manquantes
Dans le cas où une variable doit être ajoutée à ~/.config/chezmoi/config.toml il faut exécuter la commande suivante pour régénérer le fichier de configuration, la commande va automatiquement prompt toutes les variables (dont les manquantes)
```
chezmoi init
```

## Customisation (machine-to-machine differences)
Les fichiers dans le repertoire ~/.zshrc.d/ sont automatiquement sourcées.
