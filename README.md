# Noks.io | Secure & Anonymous Student Communities

Noks.io is a next-generation, anonymous community platform designed exclusively for high school and university students. It facilitates open dialogue, campus-wide networking, and safe expression through a hybrid AI+Human moderation system.

## 🌟 Vision & Key Features (English)

* **Verified Anonymity:** Users can post without revealing their identities, but must undergo **Campus Verification** to ensure the community remains exclusive to real students.
* **Hybrid Moderation Engine:** Combines **OpenAI/TensorFlow** for real-time risk detection with a community-driven moderator election system.
* **Transparent Governance:** All AI and moderator actions are logged on a transparent ledger for community audit, preventing censorship and bias.
* **Safety First:** Dedicated **Age Control** mechanisms for users under 18 and strict content filtering protocols.
* **Gamified Engagement:** Voluntary donation systems and merit-based ranking to incentivize positive community contributions.

## 🛠️ Technical Architecture (Planned)

* **Frontend:** React / React Native for a seamless cross-platform experience.
* **Backend:** Node.js (Express) or Python (Django).
* **Database:** PostgreSQL for structured user data and MongoDB for flexible post storage.
* **AI Layer:** Integration with OpenAI API for sentiment analysis and toxic content filtering.

---

# Noks.io | Güvenli ve Anonim Öğrenci Topluluğu

Noks.io, üniversite ve lise öğrencileri için anonim ve güvenli bir topluluk platformudur. Kendi kampüsünüzde veya sınıfınızda fikirlerinizi paylaşabilir, sohbet edebilir ve topluluğun nabzını tutabilirsiniz.

## ⚡ Özellikler (Turkish)

* **Anonim Paylaşım:** Gerçek ad kullanmadan içerik paylaşabilirsiniz.
* **Kampüs Doğrulama:** Her kullanıcı kendi okulunu doğrulamak zorundadır; bu sayede topluluk güvenliği korunur.
* **AI + İnsan Moderatörler:** Riskli içerikler yapay zeka tarafından otomatik tespit edilir, moderatörler ise topluluk içinden seçilir.
* **Şeffaf Loglama:** Moderatör ve AI müdahaleleri kaydedilir, denetlenebilir ve şeffaf bir yönetim sağlanır.
* **Yaş Kontrolü:** 18 yaş altı kullanıcılar için ekstra güvenlik önlemleri ve içerik filtreleme mevcuttur.

## 💻 Teknolojiler / Technologies

* **Front-end:** React / React Native, Tailwind CSS
* **Back-end:** Node.js + Express / Python + Django
* **Veritabanı / Database:** PostgreSQL / MongoDB
* **Depolama / Storage:** Backblaze B2 / Wasabi
* **AI:** OpenAI API veya TensorFlow / PyTorch içerik moderasyonu

---

## 📂 System Design (Abstract)

```text
├── api/                # Core Logic & AI Moderation Layer
├── client/             # Mobile-Responsive React Interface
├── verification/       # Academic Domain Validation Service
└── moderation/         # Transparent Action Logs
