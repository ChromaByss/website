# Chromabyss

Static test site for `chromabyss.com`.

## Deploy with Cloudflare Pages

1. Create the GitHub repository `ChromaByss/chromabyss`.
2. Push this repository to GitHub.
3. In Cloudflare, go to **Workers & Pages** > **Create application** > **Pages**.
4. Connect the GitHub repository.
5. Use these build settings:
   - Framework preset: `None`
   - Build command: leave empty
   - Build output directory: `/`
6. Add the custom domains:
   - `chromabyss.com`
   - `www.chromabyss.com`

