# Afro Host Farm

Static website (HTML + images). No build step.

## Deploy to Hostinger

**Option A — Git (auto-deploy):**
1. hPanel → Websites → Manage → Advanced → **GIT**.
2. Repository: `https://github.com/Mesumraza08-art/farm.git`, branch `main`, directory: leave empty (deploys to `public_html`).
3. Click **Create**, then **Deploy**. Optionally enable auto-deployment via the webhook shown.

**Option B — File Manager / FTP:**
Upload all files (including `.htaccess`) into `public_html`.

After deploy, enable SSL in hPanel → Security → SSL so the HTTPS redirect in `.htaccess` works.
