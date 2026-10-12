# LexFlow Copilot — Insurance Legal Operations Chat-first Demo

A responsive, static, **free** GitHub Pages portfolio project by **Wenting Wang**. This alternate format places a guided rule-based chatbot beside a nine-stage insurance legal operations workspace.

## What's working

- Nine lifecycle stages: engagement initiation, central intake, risk triage, matter/counsel assignment, execution, review and approval, resolution/financials, closure/analytics, and customer communication.
- Chat assistant guides a *fictional* five-question intake and populates a matter; provides scripted guidance for triage, counsel, approval, financials and communication.
- Fictional example case, editable matter data, simple illustrative risk tier, demo budget and spend calculations, in-page activity log, client-side JSON export, and reset.
- Email/SMS **draft simulation** (nothing is sent). Mobile responsive. No build step, account, external services or API keys.

## Preview

Open `index.html` in any modern browser.

## Publish to GitHub Pages

1. Create a public GitHub repository, suggested name: `insurance-legal-chatbot`.
2. Upload **index.html**, **styles.css**, **app.js**, and **README.md** to the repository root, and commit to `main`.
3. GitHub repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. The expected URL for GitHub account `elliewang` is `https://elliewang.github.io/insurance-legal-chatbot/`.

If you prefer Git Bash, execute in the folder **after creating an empty repository**:

```bash
git init
git config user.name "Wenting Wang"
git config user.email "YOUR_GITHUB_EMAIL"
git add .
git commit -m "Publish LexFlow chat-first demo"
git branch -M main
git remote add origin https://github.com/elliewang/insurance-legal-chatbot.git
git push -u origin main
```

If an existing Git remote exists, inspect `git remote -v` first. Replace the placeholder email with your GitHub account email or GitHub-provided noreply address.

## Important limits

**Independent educational portfolio simulation, not affiliated with any insurance carrier. Not legal advice.** Do not submit real customer PII, confidential records, insurance claims or privileged case facts. Data lives only in your browser memory and disappears on refresh. Chat responses are **rule-based**, not connected to an LLM, AWS Bedrock, or an AI API. There is no identity system, server, evidence upload, real counsel assignment, legal review, immutable audit, email/SMS sending, billing, payments or case storage. JSON downloads are local to the browser.

Production architecture would require authentication, role-based authorizations, encryption, authenticated APIs, conflict checks, sensitive-data controls, audit immutability, document retention and legal holds, human counsel decisions, approved provider integrations, and notification consent. Do not place secret API keys in public GitHub Pages JavaScript.
