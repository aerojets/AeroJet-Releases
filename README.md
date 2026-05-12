# AeroJet — Releases

Telecharge la derniere version ci-dessous et installe le fichier `.exe`.
Les mises a jour suivantes sont automatiques et silencieuses.

---

## Derniere version : v0.5.9

## v0.5.9 — Fix paiement charter + pourboire client

- Fix : paiement pilote corrigé à 10% exact du prix du vol (ex. $5 000 → $500 et non $1 000)
- Pourboire client : si le vol se passe très bien (score élevé + atterrissage souple), le client peut laisser un pourboire (5%–20% du pay) — affiché en vert dans le rapport de vol et crédité sur le compte banque

## v0.5.8 — SimBrief OFP intégré dans le Dispatch

- Dispatch — plan SimBrief chargé automatiquement si le SimBrief ID est configuré dans Connections
- Route réelle, carburant, masses ZFW/TOW/LW, pistes DEP/ARR et OFP complet si le plan correspond au charter
- Bouton "Open SimBrief" pré-rempli (DEP/ARR/type avion/callsign/pax) si le plan ne correspond pas au charter en cours
- Indicateur vert sur l'onglet OFP quand le plan SimBrief est synchronisé


---

_Les releases precedentes sont disponibles dans l'onglet [Releases](../../releases)._
