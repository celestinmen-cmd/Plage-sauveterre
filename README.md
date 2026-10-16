# Soaring Sauveterre 🪂

Mini-app web mobile qui indique si on peut faire du parapente (soaring) à la **plage de Sauveterre**
(Olonne-sur-Mer / Les Sables-d'Olonne, Vendée) — coordonnées utilisées : **46.5530 N, -1.8340 W**.

- Prévisions **Open-Meteo**, modèle **Météo-France** (`meteofrance_seamless` : AROME 1,3 km puis ARPEGE),
  récupérées en direct à chaque ouverture (+ toutes les 15 min si l'app reste ouverte).
- Maintenant : vent, direction, rafales, pluie + verdict **Ça vole / Limite / Ça vole pas**.
- 72 h heure par heure, créneaux volables surlignés, alerte rafales fortes.
- Seuils réglables (enregistrés sur le téléphone). Par défaut : vent d'ouest (±30°), 20–25 km/h,
  rafales ≤ 35 km/h, pas de pluie, de jour uniquement.

Site 100 % statique (`index.html`), hébergé sur GitHub Pages.
