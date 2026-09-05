# EpicStream — Google OAuth Branding / GitHub Pages Website

## Step 1 — Edit the placeholders BEFORE publishing

Open:

- `index.html`
- `contact.html`

In `index.html`, replace:

`YOUR_GOOGLE_VERIFICATION_CODE`

with the exact Google Search Console verification value only after Google gives you one.

In `contact.html`, replace:

`YOUR_REAL_SUPPORT_EMAIL@example.com`

with your real support/privacy email address.

## Step 2 — Upload these files to GitHub Pages

Keep this structure:

```text
/
├── index.html
├── privacy-policy.html
├── terms-of-service.html
├── contact.html
├── 404.html
├── README_STEP_BY_STEP.md
└── assets/
    └── style.css
```

The public homepage must be:

`https://hosamann.github.io/`

## Step 3 — Test the website in Incognito

Open the homepage in an Incognito/Private window.

Verify that:

1. No login is required.
2. The page clearly says "EpicStream".
3. The page explains what EpicStream does.
4. Privacy Policy opens.
5. Terms of Service opens.
6. Contact opens.
7. All links work.

## Step 4 — Verify website ownership

Use Google Search Console.

Recommended property for the current GitHub Pages setup:

`https://hosamann.github.io/`

Follow Google's ownership-verification method and complete verification.

If Google gives you an HTML meta-tag verification code, put the exact value into:

`index.html`

Replace:

`YOUR_GOOGLE_VERIFICATION_CODE`

Do NOT submit the placeholder.

## Step 5 — Google Cloud OAuth Branding

Google Cloud Console → Google Auth Platform → Branding.

Use:

Application name:
`EpicStream`

Application home page:
`https://hosamann.github.io/`

Privacy policy:
`https://hosamann.github.io/privacy-policy.html`

Terms of Service:
`https://hosamann.github.io/terms-of-service.html`

Authorized domain:
`hosamann.github.io`

Only submit after the public pages are working.

## Step 6 — Important consistency check

The name `EpicStream` should be consistent across:

- Google OAuth branding
- Website title
- Homepage heading
- Application name shown to users
- Privacy Policy
- Terms of Service

## Step 7 — Do not leave placeholders

Before verification, search the website files for:

`YOUR_`

There should be no placeholder values remaining.

## Step 8 — TMDB attribution

If your app uses TMDB, keep the required TMDB attribution/notice appropriate to your actual integration and review TMDB's current terms and API requirements before production release.

## Step 9 — Legal review

This starter privacy policy and terms are a technical website template, not legal advice. Update them so they accurately describe the Firebase services, analytics, authentication, advertising, payments, data retention, account deletion, and other features actually used by your production app.

## Step 10 — Retry OAuth verification

After the website is public and ownership is verified, return to Google Cloud → Google Auth Platform → Branding and retry the verification.
