# Calaix Blog 📝

Un espai personal de divulgació, apunts tècnics, reflexions i publicacions. Aquest repositori conté el codi font i els continguts del blog publicat a [calaix.github.io/blog](https://calaix.github.io/blog/).

---

## 🚀 Característiques

- **Ràpid i Lleuger:** Generat com a lloc estàtic per garantir la màxima velocitat de càrrega.
- **Suport per a Markdown / MDX:** Gestió de continguts senzills i adaptats amb bloc de codi, taules i equacions en LaTeX.
- **Disseny Adaptatiu (Responsive):** Optimitzat per a lectors en dispositius mòbils, tauletes i escriptori.
- **Allotjament i Automatització:** Desplegat automàticament a **GitHub Pages** mitjançant GitHub Actions a cada *commit*.
- **Feed RSS i SEO:** Optimitzat per a motors de cerca i subscripció de lectors.

---

## 📁 Estructura del Repositori

```text
.
├── .github/
│   └── workflows/      # Configuració de GitHub Actions per al desplegament
├── src/                # Codi font de l'aplicació (components, estils, pàgines)
│   ├── components/     # Components UI reutilitzables
│   ├── layouts/        # Plantilles generals de pàgina
│   └── styles/         # Arxius de configuració de CSS / Tailwind
├── content/            # Articles i contingut del blog (.md / .mdx)
│   └── posts/          # Publicacions individuals
├── public/             # Immobles estàtics (imatges, favicon, etc.)
├── package.json        # Dependències i scripts del projecte
└── README.md           # Documentació del projecte
```

---

## 🛠️ Desenvolupament Local

Per executar el projecte entorn de desenvolupament local, segueix aquests passos:

### Prerequisits
- [Node.js](https://nodejs.org/) (versió 18 o superior recomanada)
- Un gestor de paquets com `npm`, `pnpm` o `yarn`

### Passos d'instal·lació

1. **Clona el repositori:**
   ```bash
   git clone https://github.com/calaix/blog.git
   cd blog
   ```

2. **Instal·la les dependències:**
   ```bash
   npm install
   # o bé: pnpm install / yarn install
   ```

3. **Inicia el servidor de desenvolupament:**
   ```bash
   npm run dev
   ```

4. Obre el teu navegador i visita `http://localhost:3000` (o el port indicat a la terminal).

---

## ✍️ Com publicar un nou article

1. Crea un nou arxiu `.md` o `.mdx` dins de la carpeta `content/posts/` (ex: `2026-10-06-el-meu-article.md`).
2. Afegiu la metainformació (*Frontmatter*) al principi de l'arxiu:

```markdown
---
title: "Títol de la publicació"
description: "Una breu descripció o resum del contingut."
pubDate: 2026-10-06
tags: ["tecnologia", "desenvolupament", "notes"]
draft: false
---

Escriu aquí el contingut de l'article utilitzant sintaxi Markdown...
```

3. Guarda l'arxiu, fes *commit* i envia els canvis (*push*) a la branca principal.

---

## 🚢 Desplegament

El projecte està configurat per desplegar-se automàticament a **GitHub Pages** cada vegada que es fa un *push* a la branca `main`.

Pots comprovar l'estat dels desplegaments a la pestanya **Actions** d'aquest repositori.

---

## 📄 Llicència

El contingut textual d'aquest blog s'distribueix sota la llicència [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), i el codi font està disponible sota la llicència [MIT](LICENSE).
