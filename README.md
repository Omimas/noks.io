# Noks.io | Secure & Anonymous Student Communities

Noks.io is a next-generation, anonymous community platform designed exclusively for high school and university students. It facilitates open dialogue, campus-wide networking, and safe expression through a hybrid AI+Human moderation system.

## 🌟 Vision & Key Features

* **Verified Anonymity:** Users can post without revealing their identities, but must undergo **Campus Verification** to ensure the community remains exclusive to real students.
* **Hybrid Moderation Engine:** Combines **OpenAI/TensorFlow** for real-time risk detection with a community-driven moderator election system.
* **Transparent Governance:** All AI and moderator actions are logged on a transparent ledger for community audit, preventing censorship and bias.
* **Safety First:** Dedicated **Age Control** mechanisms for users under 18 and strict content filtering protocols.
* **Gamified Engagement:** Voluntary donation systems and merit-based ranking to incentivize positive community contributions.

## 🛠️ Technical Architecture (Planned)

* **Frontend:** React / React Native for a seamless cross-platform experience.
* **Backend:** Node.js (Express) or Python (Django) focusing on high-concurrency handling.
* **Database:** PostgreSQL for structured user/verification data; MongoDB for flexible post storage.
* **AI Layer:** Integration with OpenAI API for sentiment analysis and toxic content filtering.
* **Storage:** Backblaze B2 or Wasabi for cost-effective, high-availability media storage.

## 📂 System Design (Abstract)

```text
├── api/                # Core Logic & AI Moderation Layer
├── client/             # Mobile-Responsive React Interface
├── verification/       # Academic Domain Validation Service
└── moderation/         # Transparent Action Logs

# Noks.io

**Noks.io**, üniversite ve lise öğrencileri için anonim ve güvenli bir topluluk platformudur.  
Kendi kampüsünüzde veya sınıfınızda fikirlerinizi paylaşabilir, sohbet edebilir ve topluluğun nabzını tutabilirsiniz.  
AI destekli moderasyon sayesinde içerikler güvenli, moderatörler topluluğun kontrolünde.  

---

## ⚡ Özellikler / Features

- **Anonim Paylaşım / Anonymous Posting:** Gerçek ad kullanmadan içerik paylaşabilirsiniz.  
- **Kampüs Doğrulama / Campus Verification:** Her kullanıcı kendi okulunu doğrulamak zorundadır.  
- **AI + İnsan Moderatörler / AI + Human Moderation:** Riskli içerikler otomatik olarak tespit edilir, moderatörler topluluk tarafından seçilir.  
- **Bağış ve Sıralama / Donation & Ranking:** Kullanıcılar gönüllü bağış yapabilir ve sıralama listelerinde görünebilir.  
- **Yaş Kontrolü / Age Control:** 18 yaş altı kullanıcılar için ekstra güvenlik önlemleri.  
- **Şeffaf Loglama / Transparent Logging:** Moderatör ve AI müdahaleleri kaydedilir ve denetlenebilir.  

---

## 💻 Teknolojiler / Technologies

- **Front-end:** React / React Native, Tailwind CSS  
- **Back-end:** Node.js + Express / Python + Django  
- **Veritabanı / Database:** PostgreSQL / MongoDB  
- **Depolama / Storage:** Backblaze B2 / Wasabi  
- **AI:** OpenAI API veya TensorFlow / PyTorch içerik moderasyonu  

---

## 🚀 Kurulum / Installation

```bash
# Repo’yu klonla / Clone the repo
git clone https://github.com/kullanici/noks.io.git

# Proje dizinine gir / Go to project directory
cd noks.io

# Node.js backend için / For Node.js backend
npm install
npm start

# Frontend için / For frontend
cd client
npm install
npm start
