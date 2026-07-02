# JSanfeliu Events

App per gestionar els events del President de Barcelona Global.

## Funcionalitats

- **Directora**: omple un formulari per cada event amb tots els detalls de presència
- **President**: veu un dashboard en temps real amb tots els events guardats
- Dades persistents via **Supabase** (postgres + realtime)

## Camps

- Nom, data, hora i lloc de l'event
- Dress code (slider: informal → black tie)
- Presència activa (slider: passar desapercebut → saludar activament)
- Seients (sense seient → presidència reservada)
- Discurs (cap → 20 minuts)
- Assistència: tota la sessió / només inici / només final
- Per què hi som: Ajuntament, Generalitat, Ministeri, Soci corporatiu, President d'honor, Institucional

## Deploy

App 100% estàtica. Obre `index.html` directament al navegador o desplegua-la a:
- **GitHub Pages**: Settings → Pages → Deploy from branch `main`
- **Vercel / Netlify**: connecta el repo, zero configuració
- **Render**: Static Site, root directory `/`, build command buit

## Tecnologia

- HTML / CSS / Vanilla JS
- [Supabase](https://supabase.com) per base de dades i temps real
