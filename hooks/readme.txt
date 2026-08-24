Installation du hook pre-commit
================================

Ce hook demande, a chaque commit, si vous souhaitez enregistrer une note
de verification dans suivi/commitInfo.txt (date et heure du commit).

Pour l'installer :

1. Copier ce fichier vers .git/hooks/pre-commit :
   cp hooks/pre-commit .git/hooks/pre-commit

2. Le rendre executable :
   chmod +x .git/hooks/pre-commit

3. Repondre 'y' ou 'n' a la question posee lors du prochain commit.
