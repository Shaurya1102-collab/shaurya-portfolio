# Shaurya Sinha — Developer Portfolio

Responsive React + TypeScript + Vite portfolio.

## Run locally
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
npm run preview
```
The production site is generated in `dist/`.

## Deploy to Vercel
1. Extract this ZIP file.
2. Create a new, empty GitHub repository.
3. Upload the **contents of the extracted folder** to the repository root. Do not upload the ZIP itself or an extra enclosing folder.
4. Confirm that `package.json`, `index.html`, `src/`, `public/`, `vite.config.ts`, and `vercel.json` are visible at the repository's top level.
5. In Vercel, select **Add New → Project** and import that GitHub repository.
6. Vercel should detect Vite automatically. Confirm:
   - Framework Preset: `Vite`
   - Build Command: `npm run build`
   - Output Directory: `dist`
   - Install Command: `npm install`
7. Click **Deploy**.

No environment variables are required.

## Functional notes
- The résumé button downloads `public/Shaurya_Sinha_Resume.pdf`.
- Public GitHub repositories are loaded from the GitHub REST API for `Shiroyasha1102-cmd`; a fallback message appears if the API is unavailable.
- The contact form opens the visitor's email application with a prefilled message. It does not send automatically.
- The original portrait photograph is not included in the deployed public assets; dot-art portrait data is included.

## Content maintenance
Update profile links, experiences, skills, projects, education and certifications in `src/main.tsx`. Replace `public/Shaurya_Sinha_Resume.pdf` when updating the résumé.
