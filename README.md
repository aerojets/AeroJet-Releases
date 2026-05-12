# AeroJet — Releases

Telecharge la derniere version ci-dessous et installe le fichier `.exe`.
Les mises a jour suivantes sont automatiques et silencieuses.

---

## Derniere version : v0.4.5

## v0.4.4 — Avion utilisateur enfin stable

### Corrections
- **Cycle de reconnexion corrigé** — le heartbeat n'était jamais mis à jour lors de la réception des snapshots simulateur, ce qui provoquait une fausse déconnexion toutes les 15s et masquait l'avion sur la carte.
- **Erreur MapLibre vatsim-stations corrigée** — une expression `zoom` imbriquée dans un `case` forçait MapLibre à reconstruire le style entier à chaque mise à jour VATSIM, bloquant l'affichage de l'avion.


---

_Les releases precedentes sont disponibles dans l'onglet [Releases](../../releases)._
