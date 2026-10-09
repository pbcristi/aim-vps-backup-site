# AIM VPS Backup

Public information website for the **AIM VPS Backup** personal-use Google Drive OAuth application.

This repository contains only the static website used to explain the app's purpose and privacy practices. The private AI Investment Manager application, server configuration, financial data, encrypted backups, OAuth tokens, and recovery keys are **not** published here.

- **Application homepage:** https://pbcristi.github.io/aim-vps-backup-site/
- **Privacy policy:** https://pbcristi.github.io/aim-vps-backup-site/privacy.html

## Publishing

In the repository's **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save. GitHub Pages will serve `index.html` as the homepage and `privacy.html` as the policy.

These links are only live after Pages deployment is enabled.

## Google Drive access

The Google OAuth client requests `https://www.googleapis.com/auth/drive.file` only. The private rclone-based integration is intended to transfer **encrypted** backup archives to a Google Drive account controlled by the owner.

This website has no OAuth callback, no sign-in flow, and no backend.

## Contact

Open a [public issue](https://github.com/pbcristi/aim-vps-backup-site/issues/new) for non-sensitive questions. **Never include tokens, passwords, cryptographic keys, or financial details in a public issue.**
