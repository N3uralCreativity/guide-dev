branch
Créer une branche dédiée depuis main : git checkout -b feat/nom-du-changement

commit
Coder, puis enregistrer les changements :
git add .
git commit -m "feat: description claire du changement"

push
Envoyer la branche sur le remote :
git push -u origin feat/nom-du-changement

pull request
Ouvrir une PR (branche -> main), décrire ce qui a été fait, demander review.

merge
Après validation/tests : merger la PR dans main, puis nettoyer la branche.
