# Mettre Famio en ligne (GitHub Pages) — guide pas à pas

Objectif : obtenir un lien web pour ouvrir Famio sur ton iPhone (et l'ajouter à
l'écran d'accueil). Tout est gratuit. Compte : **Mr Joubari**.

## Étape 1 — Créer le dépôt

1. Va sur **github.com**, connecte-toi (Mr Joubari).
2. En haut à droite, clique **+** puis **New repository**.
3. **Repository name** : `famio`
4. Laisse **Public** coché.
5. Ne coche rien d'autre. Clique **Create repository**.

## Étape 2 — Déposer les fichiers

1. Sur la page du dépôt, clique **uploading an existing file**
   (lien au milieu), ou le bouton **Add file → Upload files**.
2. Glisse les 3 fichiers du dossier `famio` :
   - `index.html`
   - `LICENSE`
   - `README.md`
3. En bas, clique **Commit changes**.

## Étape 3 — Activer GitHub Pages

1. Dans le dépôt, onglet **Settings** (en haut).
2. Menu de gauche : **Pages**.
3. Section **Build and deployment** → **Source** : choisis **Deploy from a branch**.
4. **Branch** : choisis **main**, dossier **/ (root)**. Clique **Save**.
5. Patiente 1–2 minutes. Recharge la page : un encadré affiche

   **« Your site is live at https://mr-joubari.github.io/famio/ »**

   (l'adresse exacte dépend de ton nom de compte). **C'est ton lien.**

## Étape 4 — Sur l'iPhone

1. Ouvre **Safari** et tape ton lien (celui affiché à l'étape 3).
2. Famio s'ouvre et te demande de créer ton mot de passe.
3. Touche le bouton **Partager** (le carré avec une flèche en bas).
4. Choisis **« Sur l'écran d'accueil »**.
5. Une icône **Famio** apparaît → tu l'ouvres comme une vraie appli.

## Au quotidien (rappel)

- Tes données s'enregistrent **toutes seules** dans le navigateur.
- De temps en temps sur iPhone, touche **💾 Enregistrer** pour mettre à jour
  ton fichier `famio.famdb` dans iCloud/OneDrive (filet de sécurité).
- Pas de notification quand l'appli est fermée (limite du web sur iPhone).

## Mettre à jour l'appli plus tard

Quand je te livre une nouvelle version de `index.html` : sur GitHub, ouvre le
fichier `index.html`, clique l'icône crayon (**Edit**)… ou plus simple,
**Add file → Upload files**, redépose le nouveau `index.html`, puis
**Commit changes**. Le site se met à jour tout seul en 1–2 minutes.

---

Besoin d'aide à une étape ? Dis-moi où tu bloques (avec une capture si tu peux),
je te débloque.
