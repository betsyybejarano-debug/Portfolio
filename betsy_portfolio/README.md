# Betsy Bejarano — Portfolio (v2)

```
index.html      the public website
assets/         resume PDF (+ photos you add later)
admin/index.html  your private editor (works from any browser, anywhere)
```

## One-time setup (about 15 minutes, free)

1. **Create a GitHub account** and a new repository (e.g. `portfolio`).
2. **Upload everything in this folder** to the repository (Add file → Upload files). `index.html`, `assets/` and `admin/` must be at the top level.
3. **Turn on hosting:** repo → Settings → Pages → Source: *Deploy from a branch* → `main` / root. Your site appears at `https://YOURNAME.github.io/portfolio/` after a minute. (A custom domain like betsyybejarano.com can be connected later in the same Pages settings, after you buy it from a registrar.)
4. **Make your edit key:** GitHub → Settings → Developer settings → Personal access tokens → *Fine-grained tokens* → Generate.
   - Repository access: **Only select repositories** → your portfolio repo
   - Permissions → Repository → **Contents: Read and write**
   - Copy the token (starts with `github_pat_`). Treat it like a password.

## Editing whenever you want

1. Go to `https://YOURNAME.github.io/portfolio/admin/` and enter `YOURNAME/portfolio`, branch `main`, and your token (saved in that browser only).
2. In the preview, click any text to edit it. Click a photo box to add or replace a photo.
3. Use the side panel to **upload a new resume PDF**, **add collaborators** to a project, duplicate a project card, or change your email/LinkedIn.
4. Click **Publish changes**. The live site updates in about a minute.

Security: the admin page is public but can do nothing without your token, and GitHub only accepts changes from it. Never share the token. If it leaks, delete it in GitHub and make a new one.

## Before you publish
- Fill in the **About Me** section (intro, quick facts, hobbies, photos). Those are placeholders.
- Replace the LinkedIn link with your real profile.
- Confirm you're comfortable with your email being public.
- Get permission before naming collaborators or posting their photos.
