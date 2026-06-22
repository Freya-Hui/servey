# Chinese Luxury Survey - Vercel Deployment

Upload the contents of this folder to the root of a GitHub repository.

The repository root must contain:

- `package.json`
- `vercel.json`
- `public/index.html`
- `public/media/C_part_video_materials/*.mp4`

Vercel settings:

- Framework Preset: Other
- Build Command: `npm run build`
- Output Directory: `dist`
- Root Directory: leave empty if these files are in the repository root

If the GitHub repository contains this folder as a subfolder, set Vercel Root Directory to:

`GITHUB_UPLOAD_THIS_SURVEY`

If Vercel shows `404: NOT_FOUND`, it usually means Root Directory is wrong or Vercel cannot see `package.json`.
