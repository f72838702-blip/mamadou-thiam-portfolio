# Portfolio — Mamadou Thiam

Site portfolio moderne pour **Mamadou Thiam**, Technicien / Ingénieur Junior en Réseaux & Télécommunications (Conakry, Guinée). Étudiant en L3 à l'ESMT, spécialisé fibre optique, réseaux mobiles 2G–5G et protocoles TCP/IP.

## Stack
- HTML5 + Tailwind CSS (CDN) + JavaScript vanilla (aucun build)
- Lucide Icons (CDN) + Google Fonts (Sora, Inter, JetBrains Mono)
- Design **dark mode tech** — accents bleu/cyan, grille animée, glow
- One-page responsive (mobile / tablette / desktop)

## Sections
1. Hero — accroche + CTAs (CV / Contact / LinkedIn) + photo
2. À propos — bio + 4 domaines (fibre, mobiles, protocoles, gestion projet)
3. Compétences — barres animées (protocoles, outils, langues) + cartes réseaux mobiles 2G/3G/4G/5G
4. Parcours & Projets — timeline filtrable (Académique / Projets) — L3 ESMT, projet fibre optique, certifications BB 2026
5. Références — ESMT Conakry + Alpha Mamadou Sylla (réf. pro)
6. Contact — formulaire `mailto:` + boutons `tel:` / WhatsApp / e-mail / LinkedIn
7. Bouton WhatsApp flottant (FAB)

## Aperçu local
```
cd mamadou-thiam-portfolio
python -m http.server 8000
```
→ http://localhost:8000

## Déploiement Vercel
1. `npm i -g vercel`
2. `cd mamadou-thiam-portfolio`
3. `vercel` puis `vercel --prod`

Fichier `index.html` unique → Vercel le détecte automatiquement.
> Note : l'intégration Git auto n'est pas active — après un push, relancer `vercel --prod` pour mettre la prod à jour.

## À remplacer
- **Photo (Hero)** : remplacer le placeholder `// photo à insérer` par `<img src="assets/mamadou-thiam.jpg" ...>`.
- **CV (PDF)** : placer `assets/cv-mamadou-thiam.pdf` et pointer le bouton « Télécharger le CV » dessus (retirer l'`alert` JS).

## Contact
- ✉️ mamadouthiam646@gmail.com
- 📞 +224 610-18-79-86
- 💼 linkedin.com/in/mamadou-thiam-709002368