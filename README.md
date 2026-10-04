# Ma'atywellness — site

## Déploiement Netlify via GitHub
1. Créer un dépôt GitHub (ex. `maatywellness-site`) et y déposer **le contenu** de ce dossier (index.html à la racine).
2. Netlify → *Add new site* → *Import an existing project* → GitHub → choisir le dépôt.
3. Build command : *(vide)* — Publish directory : `.` → *Deploy*.
4. Netlify → *Domain management* : connecter le domaine (ex. maatywellness.com).
5. Netlify → *Forms* : activer la détection de formulaires (contact, freebie, newsletter, commentaire) puis redéployer. Ajouter une notification e-mail par formulaire.

## À compléter avant mise en ligne
- Domaine : remplacer `https://maatywellness.com` s'il diffère (index.html, article-blog.html, sitemap.xml, robots.txt, llms.txt).
- Téléphone, adresse, e-mail de contact (section Contact de index.html).
- Liens réseaux sociaux + calculateur de charte : chercher `"#"` / `#design-humain` ou renseigner les props dans l'éditeur avant export.
- Mentions légales / CGV / Confidentialité (liens du pied de page).

## SEO
- Après la mise en ligne : soumettre `/sitemap.xml` dans Google Search Console et Bing Webmaster Tools.
- `llms.txt` résume le site pour les moteurs génératifs (ChatGPT, Claude, Perplexity…).
