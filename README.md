# Blowfish

Template PBN genere depuis https://github.com/nunocoracao/blowfish.git.

## Validation

- Slug PBN: `blowfish`
- Theme Hugo: `blowfish`
- Profil: `blog`
- Contrat contenu: `content/posts/{{slug}}.md` -> `/posts/{{slug}}/`
- Build: `npm --prefix themes/blowfish install --include=dev --include=optional --no-package-lock && npm --prefix themes/blowfish run build && hugo --gc --minify`
- Publication: `public`

Avant activation production, lancer un build Hugo avec un contenu de test.
