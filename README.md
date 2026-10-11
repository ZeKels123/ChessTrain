# Échiquier d'entraînement

Outil d'apprentissage des échecs : parties contre 26 bots (50 à 3200 Elo),
45 ouvertures et défenses avec répétition espacée, 250 tactiques, 17 finales,
16 questions de stratégie, analyse de partie et estimation de niveau.

Moteur : **Stockfish 19** compilé en WebAssembly, exécuté dans le navigateur.

- Comptes et synchronisation de la progression : Supabase
- Parties en ligne par lien d'invitation, horloge tenue côté serveur

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | toute l'application |
| `sf.js`, `sf.wasm` | Stockfish 19 (GPL v3) |
| `supabase.js` | client Supabase |

## Licence

Stockfish est sous **GPL v3** — voir https://github.com/official-stockfish/Stockfish
