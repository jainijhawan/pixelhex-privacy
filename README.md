# Pixel Hex Privacy Policy

This repository hosts the privacy policy for the Pixel Hex iOS app in multiple languages using GitHub Pages.

## Live URLs

Once published, your privacy policies will be available at:

### Default (English - US)
```
https://[your-username].github.io/pixelhex-privacy/
```

### Privacy Policy & Support URLs by Localization

| Language | App Store Code | Privacy URL | Support URL |
|----------|---------------|-------------|-------------|
| English (US) | Default | `https://[your-username].github.io/pixelhex-privacy/` | `https://[your-username].github.io/pixelhex-privacy/support.html` |
| English (UK) | en-GB | `https://[your-username].github.io/pixelhex-privacy/en-GB.html` | `https://[your-username].github.io/pixelhex-privacy/support.html` |
| English (Canada) | en-CA | `https://[your-username].github.io/pixelhex-privacy/en-CA.html` | `https://[your-username].github.io/pixelhex-privacy/support.html` |
| English (Australia) | en-AU | `https://[your-username].github.io/pixelhex-privacy/en-AU.html` | `https://[your-username].github.io/pixelhex-privacy/support.html` |
| French (France) | fr | `https://[your-username].github.io/pixelhex-privacy/fr.html` | `https://[your-username].github.io/pixelhex-privacy/support-fr.html` |
| French (Canada) | fr-CA | `https://[your-username].github.io/pixelhex-privacy/fr-CA.html` | `https://[your-username].github.io/pixelhex-privacy/support-fr.html` |
| Spanish (Spain) | es-ES | `https://[your-username].github.io/pixelhex-privacy/es-ES.html` | `https://[your-username].github.io/pixelhex-privacy/support-es.html` |
| Spanish (Mexico) | es-MX | `https://[your-username].github.io/pixelhex-privacy/es-MX.html` | `https://[your-username].github.io/pixelhex-privacy/support-es.html` |
| Portuguese (Portugal) | pt-PT | `https://[your-username].github.io/pixelhex-privacy/pt-PT.html` | `https://[your-username].github.io/pixelhex-privacy/support-pt.html` |
| Portuguese (Brazil) | pt-BR | `https://[your-username].github.io/pixelhex-privacy/pt-BR.html` | `https://[your-username].github.io/pixelhex-privacy/support-pt.html` |
| Korean | ko | `https://[your-username].github.io/pixelhex-privacy/ko.html` | `https://[your-username].github.io/pixelhex-privacy/support-ko.html` |
| Chinese (Simplified) | zh-Hans | `https://[your-username].github.io/pixelhex-privacy/zh-Hans.html` | `https://[your-username].github.io/pixelhex-privacy/support-zh-Hans.html` |
| Chinese (Traditional) | zh-Hant | `https://[your-username].github.io/pixelhex-privacy/zh-Hant.html` | `https://[your-username].github.io/pixelhex-privacy/support-zh-Hant.html` |
| Vietnamese | vi | `https://[your-username].github.io/pixelhex-privacy/vi.html` | `https://[your-username].github.io/pixelhex-privacy/support-vi.html` |
| Russian | ru | `https://[your-username].github.io/pixelhex-privacy/ru.html` | `https://[your-username].github.io/pixelhex-privacy/support-ru.html` |
| Arabic | ar | `https://[your-username].github.io/pixelhex-privacy/ar.html` | `https://[your-username].github.io/pixelhex-privacy/support-ar.html` |

## Setup Instructions

### 1. Create a new GitHub repository
- Go to GitHub and create a new **public** repository
- Name it: `pixelhex-privacy` (or any name you prefer)
- Initialize without README (since we already have one)

### 2. Push this folder to GitHub
```bash
cd "/Users/jainijhawan/Documents/PixelHex Privacy"
git init
git add .
git commit -m "Initial commit: Add multilingual privacy policies"
git branch -M main
git remote add origin https://github.com/[your-username]/pixelhex-privacy.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repository settings on GitHub
- Navigate to "Pages" section
- Under "Source", select "Deploy from a branch"
- Select branch: `main` and folder: `/ (root)`
- Click "Save"

### 4. Add URLs to App Store Connect

When configuring your app in App Store Connect:

#### Support URL (Required)
In your app's **General Information** section:
```
https://[your-username].github.io/pixelhex-privacy/support.html
```

#### Privacy Policy URLs
1. Go to your app's **App Privacy** section
2. For each localization that requires a Privacy Policy URL, use the corresponding URL from the table above
3. Replace `[your-username]` with your actual GitHub username

**Example:**
- For **Korean**, use: `https://yourusername.github.io/pixelhex-privacy/ko.html`
- For **French**, use: `https://yourusername.github.io/pixelhex-privacy/fr.html`
- For **English (Canada)**, use: `https://yourusername.github.io/pixelhex-privacy/en-CA.html`

## Files Included

### Privacy Policy Pages
- `index.html` - English (US) - Default privacy policy page
- `en-GB.html` - English (UK)
- `en-CA.html` - English (Canada) with PIPEDA references
- `en-AU.html` - English (Australia) with Australian Privacy Principles
- `fr.html` - French (France)
- `fr-CA.html` - French (Canada)
- `es-ES.html` - Spanish (Spain) with GDPR references
- `es-MX.html` - Spanish (Mexico)
- `pt-PT.html` - Portuguese (Portugal) with GDPR references
- `pt-BR.html` - Portuguese (Brazil) with LGPD references
- `ko.html` - Korean
- `zh-Hans.html` - Chinese (Simplified)
- `zh-Hant.html` - Chinese (Traditional)
- `vi.html` - Vietnamese
- `ru.html` - Russian
- `ar.html` - Arabic (RTL layout)

### Support Pages
- `support.html` - English (US, UK, Canada, Australia)
- `support-ko.html` - Korean
- `support-fr.html` - French (France & Canada)
- `support-es.html` - Spanish (Spain & Mexico)
- `support-pt.html` - Portuguese (Portugal & Brazil)
- `support-zh-Hans.html` - Chinese (Simplified)
- `support-zh-Hant.html` - Chinese (Traditional)
- `support-vi.html` - Vietnamese
- `support-ru.html` - Russian
- `support-ar.html` - Arabic (RTL layout)

Each privacy policy file includes:
- Translated privacy policy content
- Appropriate regional compliance references (GDPR, CCPA, PIPEDA, LGPD, etc.)
- Your contact information
- Responsive design for mobile and desktop
- Professional Apple-style aesthetics

Each support page includes:
- Contact information with your email
- FAQs for common questions
- Getting started guide
- Troubleshooting tips
- Feature highlights
- Subscription management information
- Responsive design for all devices
- Professional gradient contact section

## Making Updates

To update any privacy policy:

1. Edit the appropriate HTML file(s) in this folder
2. Update the "Last Updated" date
3. Commit and push changes:
   ```bash
   git add .
   git commit -m "Update privacy policy"
   git push
   ```
4. Changes will automatically deploy to GitHub Pages within a few minutes

## Contact

Email: jainijhawan@gmail.com
Developer: Jai Nijhawan

