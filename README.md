# AeroJet — Releases

Telecharge la derniere version ci-dessous et installe le fichier `.exe`.
Les mises a jour suivantes sont automatiques et silencieuses.

---

## Derniere version : v0.5.6

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
