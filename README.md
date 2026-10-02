# Explorateur de noms de communes (France 2026)

Outil web pour rechercher dans le référentiel officiel des communes françaises (`v_commune_2026.csv`).

## Utilisation en ligne

Ouvrir l’application : **https://julesgrandin.github.io/communes-2026/**

## Utilisation en local

```bash
python3 -m http.server 8765
```

Puis ouvrir [http://127.0.0.1:8765/index.html](http://127.0.0.1:8765/index.html).

## Données

- `v_commune_2026.csv` — colonne `LIBELLE` pour le nom affiché des communes.
- `depcomplets.geojson` — contours des départements (fond de carte ; outre-mer en encarts).

Après géocodage des résultats, le bouton **Faire la carte** affiche les communes sur une carte D3 (métropole + Corse, DOM en bandeau « îles » en bas).
