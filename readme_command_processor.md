# Command Processor

Programme interactif qui lit une commande suivie d'un texte et applique une transformation.

## Utilisation

```bash
python3 main.py
```

Invite :
```
commade>
```

## Commandes

- `uppercase <texte>` : met le texte en majuscules.
- `lowercase <texte>` : met le texte en minuscules.

## Exemple
```
commade> uppercase hello
HELLO
```

## Fonctionnement

- `process_line()` analyse la commande.
- `main()` boucle jusqu'au EOF.

