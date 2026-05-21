# Serenity 1 Digital Business Card

A simple mobile-first digital business card for Dan Tuker at Serenity 1 Consulting Group.

## Included

- `index.html` — the public business card page
- `style.css` — professional responsive styling
- `contact.vcf` — downloadable contact card
- `assets/serenity1-logo.png` — company logo

## GitHub Pages Setup

1. Create a new GitHub repository, for example: `serenity-digital-card`.
2. Upload all files in this folder to the repo.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch: `main`, folder: `/root`.
6. Save.
7. GitHub will give you a live URL like:

```text
https://YOUR-GITHUB-USERNAME.github.io/serenity-digital-card/
```

Write that URL to the NFC card using NFC Tools or your NFC writer software.

## NFC Recommendation

Write the GitHub Pages URL to the NFC card as a URL record. Do not write all contact details directly to the NFC card. This keeps the card editable later by updating the website.
