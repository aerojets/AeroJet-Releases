# AeroJet — Releases

Telecharge la derniere version ci-dessous et installe le fichier `.exe`.
Les mises a jour suivantes sont automatiques et silencieuses.

---

## Derniere version : v0.5.8

## v0.5.8 — SimBrief OFP intégré dans le Dispatch

- Dispatch — plan SimBrief chargé automatiquement si le SimBrief ID est configuré dans Connections
- Route réelle, carburant, masses ZFW/TOW/LW, pistes DEP/ARR et OFP complet si le plan correspond au charter
- Bouton "Open SimBrief" pré-rempli (DEP/ARR/type avion/callsign/pax) si le plan ne correspond pas au charter en cours
- Indicateur vert sur l'onglet OFP quand le plan SimBrief est synchronisé

## v0.5.7 — Dispatch, barre de vol + Admin Flights

- Page Dispatch complète : DISPATCH / WEATHER / OFP + carte route intégrée
- Barre de vol active en bas de la Map (phase, elapsed, callsign, abandon)
- Admin : onglet Flights avec historique de tous les vols + recherche
- Admin : recherche dans la liste utilisateurs
- Météo METAR temps réel dans la page Dispatch (aviationweather.gov)

## v0.5.6 — Corrections console + stabilité worker

- Fix MapLibre : erreur "Only one zoom-based step" — layers CTR et Approach séparés
- Fix Worker 503 : boundaries VATSIM rafraîchies en arrière-plan (stale-while-revalidate)
- Cache boundaries : 5 min fresh, 30 min stale acceptable — plus de timeouts CPU

- Rapport de vol redessiné : score par catégorie, violations, bonus, récapitulatif réputation
- Charter validé uniquement si score ≥ 50 et pas de crash (validation automatique)
- Section charter dans le rapport : paiement crédité ou refusé avec explication
- Stats atterrissage : fpm, vitesse sol, G-force


---

_Les releases precedentes sont disponibles dans l'onglet [Releases](../../releases)._
