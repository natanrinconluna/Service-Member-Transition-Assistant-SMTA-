# Service-Member-Transition-Assistant-SMTA-
Service Member Transition Assistant (SMTA) is a full-stack web application that helps U.S. service members and veterans transition to civilian life by providing AI-powered resume building, personalized VA benefits guidance, job search tools, and secure community forums — all in one platform.


## 🧠 Key Features

- AI-powered resume builder (:contentReference[oaicite:3]{index=3} API)
- VA benefits guidance & personalized checklists
- Secure user data storage with encryption (:contentReference[oaicite:4]{index=4})
- Community forums with automated moderation
- Authentication via :contentReference[oaicite:5]{index=5} / :contentReference[oaicite:6]{index=6}
- Cloud-hosted (:contentReference[oaicite:7]{index=7} + :contentReference[oaicite:8]{index=8})

---

## ⚙️ Tech Stack

- **Frontend**: :contentReference[oaicite:9]{index=9} (Next.js), TailwindCSS, Zustand
- **Backend**: :contentReference[oaicite:10]{index=10} + :contentReference[oaicite:11]{index=11}
- **Database**: :contentReference[oaicite:12]{index=12} (on :contentReference[oaicite:13]{index=13})
- **AI Services**: OpenAI API, :contentReference[oaicite:14]{index=14} (OCR)
- **Cloud**: :contentReference[oaicite:15]{index=15}, :contentReference[oaicite:16]{index=16}, :contentReference[oaicite:17]{index=17}
- **Security**: OAuth2 / OpenID, Tink encryption, 2FA (TOTP/WebAuthn)

---

## 🧪 Running Locally

### 1. Clone the Repo
```bash
git clone https://github.com/<your-username>/smta.git
cd smta
