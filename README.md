# Kenzo PDF Site

PDF-only portfolio deployment folder for manual GitHub upload and Vercel.

## Files

- `portfolio.pdf` - the portfolio people should see
- `vercel.json` - redirects `/` straight to `/portfolio.pdf` and serves the PDF inline

## Deploy

1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. In Vercel, add a new project and import that repository.
4. Use the default static settings. No framework and no build command are required.
5. Add your domain in Vercel project settings.

The final URLs should be:

- `/` - redirects directly to the PDF
- `/portfolio.pdf` - direct PDF URL

There is no designed HTML landing page. Visitors should land in the browser's native PDF viewer.
