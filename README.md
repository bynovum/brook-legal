# Brook legal (Privacy + Terms)

> **Not legal advice · review before publish.**  
> Drafts for **Brook** (`app.hk.001`) — friends beta / App Store Connect. Have a lawyer review before wide public release.

**Effective date:** 17 October 2026  
**Publisher (Seller of Record framing):** Singh Jaskaran (individual developer), Hong Kong  
**Contact / support:** [cozkyle@gmail.com](mailto:cozkyle@gmail.com)  
**GitHub Pages repo:** public [`bynovum/brook-legal`](https://github.com/bynovum/brook-legal) (to be created / pushed)

---

## Live URLs (GitHub Pages)

| Doc | URL |
| --- | --- |
| **Privacy Policy** | https://bynovum.github.io/brook-legal/privacy-policy.html |
| **Terms of Service** | https://bynovum.github.io/brook-legal/terms-of-service.html |
| **Site index** | https://bynovum.github.io/brook-legal/ |
| **Support** | mailto:cozkyle@gmail.com |

App Store Connect → paste **Privacy Policy URL** = `https://bynovum.github.io/brook-legal/privacy-policy.html`.  
Support URL can be `mailto:cozkyle@gmail.com` or the site index once Pages is live.

---

## Files

| File | Purpose |
| --- | --- |
| `privacy-policy.html` / `.md` | Privacy Policy |
| `terms-of-service.html` / `.md` | Terms of Service / Terms of Use |
| `index.html` | Cream landing page linking both (in publish folder) |
| `README.md` | This guide |

**Mac:** `/Users/juggymade/Desktop/Brook-legal/`  
**Box drafts:** `/workspace/brook-legal/`  
**Publish folder (Pages-ready):** `/workspace/brook-legal-pages/` — HTML only + index + this README

Placeholders are **filled**. Do not reintroduce `{{…}}`.

---

## Publish (parent / Jugdeep)

1. Create public repo **`bynovum/brook-legal`**.  
2. Push contents of `/workspace/brook-legal-pages/` to `main` (root).  
3. Settings → Pages → Deploy from branch `main` / `/ (root)`.  
4. Wait ~1–2 minutes; open the Privacy URL on a phone.  
5. App Store Connect → Privacy Policy URL → `https://bynovum.github.io/brook-legal/privacy-policy.html`.  
6. In Brook Settings, link Privacy + Terms to the URLs above.

---

## App Store Connect reminders

| Field | Value |
| --- | --- |
| Privacy Policy URL | `https://bynovum.github.io/brook-legal/privacy-policy.html` |
| EULA | Apple standard EULA is OK; still link custom Terms in-app |
| Support URL | `mailto:cozkyle@gmail.com` or https://bynovum.github.io/brook-legal/ |

### App Privacy labels

Align with reality: on-device logs, optional HealthKit / Location / Photos, DeepSeek for AI features, AdMob present but **ads OFF** for beta, no Brook accounts. See earlier nutrition-label checklist in git history / co-founder notes if needed.

### Product facts in these docs

- No accounts / no Sign in with Apple; SwiftData on device  
- Camera + Photos; optional Location + Notifications  
- HealthKit read/write as documented — **never for ads**  
- Open Food Facts; DeepSeek (may process outside HK / in China)  
- Ads OFF for friends beta  
- Age 13+; Hong Kong governing law  

---

*English only for V1. No GDPR DPO claimed — add later if you expand to EU.*
