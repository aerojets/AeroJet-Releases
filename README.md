# AeroJet — Releases

Telecharge la derniere version ci-dessous et installe le fichier `.exe`.
Les mises a jour suivantes sont automatiques et silencieuses.

---

## Derniere version : v0.5.7

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
