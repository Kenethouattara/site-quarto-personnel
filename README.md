# Site Quarto personnel – Fahd Keneth Ouattara

Site personnel du cours STT-6230 (Université Laval, automne 2026). Il est écrit avec Quarto,
rendu dans `docs/` et publié avec GitHub Pages (branche `main`, dossier `/docs`).

- Site publié : https://kenethouattara.github.io/site-quarto-personnel/
- Réalisation issue du portfolio : `realisations/portfolio-individuel.qmd`
- Réalisation issue du projet d'équipe (contient la justification technique STT-6230) : `realisations/projet-equipe-acp.qmd`

## Structure

```
_quarto.yml                            configuration du site (menu, thème, sortie dans docs/)
index.qmd                              À propos (accueil)
cv.qmd                                 CV (formation, stages, compétences)
realisations.qmd                       Vue d'ensemble des réalisations
realisations/portfolio-individuel.qmd  Réalisation 1 : trace du portfolio
realisations/projet-equipe-acp.qmd     Réalisation 2 : projet d'équipe
realisations/taln-travaux.qmd          Autre projet : TALN
realisations/analyse-donnees.qmd       Autres projets : analyse de données
reflexion.qmd                          Réflexion, choix techniques, confidentialité
references.qmd                         Références
styles.css                             Mise en forme
.nojekyll                              Désactive Jekyll sur GitHub Pages
```

## Rendu et publication

```bash
quarto render          # dans le dossier qui contient _quarto.yml
git add .
git commit -m "Mise à jour du site personnel"
git push
```
