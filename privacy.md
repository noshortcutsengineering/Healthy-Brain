# Privacy Policy — Healthy Brain

**Product:** Healthy Brain (Chrome extension)  
**Effective date:** August 27, 2026  
**Developer:** [github.com/noshortcutsengineering/Healthy-Brain](https://github.com/noshortcutsengineering/Healthy-Brain)

This Privacy Policy describes how the Healthy Brain Chrome extension (“the Extension,” “we,” “us”) handles information. It is written to satisfy Chrome Web Store privacy disclosure requirements.

---

## Summary

- The Extension **does not collect**, sell, share, or transmit personal user data to us or to any analytics service.
- The Extension **does not** require an account.
- Redirects run **locally** in your browser.
- A **pause preference** (and resume time) may be stored **only on your device**.
- An optional **donation link** may open Buy Me a Coffee; that is separate from the Extension.

---

## What the Extension does

Healthy Brain helps reduce distracting feeds by redirecting main-frame navigations:

| Site | Destination |
| --- | --- |
| youtube.com (any path) | https://feedly.com/ |
| linkedin.com (any path) | https://feedly.com/ |
| instagram.com (any path) | https://feedly.com/ |

You can **pause** redirects for **one hour** from the extension popup. Redirects turn back on automatically after that hour, or sooner if you resume manually.

The Extension does **not** read the content of web pages, does **not** inject trackers, and does **not** upload browsing activity to our servers (we do not operate a backend for this Extension).

---

## Information we collect

### Personal information

We **do not** collect personal information, including:

- Name, email, or contact details  
- Payment or financial information  
- Authentication credentials  
- Location  
- Health or sensitive information  
- Web history, browsing activity, or website content for our own use  
- Personally identifiable information of any kind transmitted off your device  

### Local data stored on your device only

To support the pause feature, the Extension may store in Chrome’s local extension storage:

- Whether redirects are currently paused  
- The timestamp when redirects should automatically resume  

This data:

- Stays on your device  
- Is not sent to us  
- Can be cleared by removing the Extension or clearing extension data in Chrome  

### Remote code / network transmission

The Extension does not send user data to remote servers operated by us. Redirects change the navigation destination in the browser using Chrome’s `declarativeNetRequest` API; they do not phone home.

---

## Permissions and why they are used

| Permission | Purpose |
| --- | --- |
| `declarativeNetRequest` | Apply redirect rules from YouTube, LinkedIn, and Instagram to Feedly |
| `storage` | Remember pause state and resume time on your device |
| `alarms` | Automatically re-enable redirects one hour after a pause |
| Host access to `youtube.com`, `linkedin.com`, `instagram.com` | Allow those sites’ main-frame navigations to be redirected |

These permissions are used only for the purposes above. They are not used to collect or monetize user data.

---

## How we use information

We do not receive personal information from the Extension, so we do not use, sell, rent, or share personal information.

Local pause state is used solely to enable/disable redirects on your browser.

---

## Data sharing and third parties

We do not share Extension user data with third parties because we do not collect it.

If you visit other sites through normal browsing or redirects, those sites (including **YouTube**, **LinkedIn**, **Instagram**, and **Feedly**) have their own privacy policies. The Extension does not control them.

### Optional donations

The Extension may show a link to [Buy Me a Coffee — healthyscreens](https://buymeacoffee.com/healthyscreens).  
If you choose to open that link and donate:

- The transaction is handled by Buy Me a Coffee (and its payment processors)  
- Their privacy policy applies to that interaction  
- The Extension does **not** receive or store your payment details  

---

## Children’s privacy

The Extension is not directed at children under 13. We do not knowingly collect personal information from children.

---

## Data retention and deletion

Because we do not collect personal data on our servers, there is no server-side retention.

Local pause data remains on your device until you:

- Resume redirects / let the pause expire, and/or  
- Clear site/extension data, or  
- Uninstall the Extension  

---

## Security

We do not maintain user databases for this Extension. Local storage is managed by Chrome on your device. You should keep Chrome and the Extension updated.

---

## Chrome Web Store disclosures (developer checklist)

When filling out the Chrome Web Store privacy practices form for Healthy Brain, declare consistently with this policy:

- **Single purpose:** Redirect YouTube, LinkedIn, and Instagram navigations to Feedly, with an optional 1-hour pause.  
- **Does not collect user data** (no remote collection).  
- **Does not sell user data.**  
- **Does not use remote code** beyond the packaged extension.  
- **Local storage only** for pause/resume preference.  
- **Privacy policy URL:** host this file (or `privacy.html`) at a public HTTPS URL and paste that URL in the dashboard.

---

## Changes to this policy

If this policy changes, we will update this document and the effective date. Continued use of the Extension after changes means you accept the updated policy.

---

## Contact

Questions about this Privacy Policy or the Extension:

- GitHub Issues: [github.com/noshortcutsengineering/Healthy-Brain/issues](https://github.com/noshortcutsengineering/Healthy-Brain/issues)

---

## How to use this file for the Chrome Web Store

The Chrome Web Store requires a **public HTTPS privacy policy URL** (not only a file inside the `.zip`).

Suggested options:

1. **GitHub:** push `privacy.md` to the repo and use the rendered page URL, or enable GitHub Pages and link to it.  
2. **GitHub Pages example:** `https://noshortcutsengineering.github.io/Healthy-Brain/privacy.html` (HTML version) or a Pages URL that serves this markdown.  
3. Paste that HTTPS link into **Developer Dashboard → Privacy practices → Privacy policy**.

Do **not** put `privacy.md` inside the extension package zip used for upload; keep it on a public website/repo page for reviewers and users.
