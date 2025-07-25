# 🍿🎬 Popcorn Bot

**Popcorn Bot**, kullanıcıdan aldığı film türü veya ruh hâline göre Google’ın yapay zekâ modeli **Gemini 2.5 Flash** destekli olarak film öneren bir asistandır.  
Gradio arayüzü ile interaktif ve kullanıcı dostu bir deneyim sunar.

---

## 🚀 Özellikler

- 🎭 Belirttiğiniz türe uygun **film önerisi**
- 🌟 Özel istek (yıl, ödül, platform vb.) opsiyonu
- 🤖 Google Gemini 2.5 Flash modeli ile içerik üretimi
- 💻 FastAPI backend
- 🖼️ Gradio frontend
- 🎨 Özel CSS ile şık tasarım

---

## 🛠️ Kurulum

```bash
git clone https://github.com/aydnhayatt/popcorn-bot.git
cd popcorn-bot
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt



---

 📁 Proje Dosya Yapısı
popcorn-bot/
├── app.py               # Gradio arayüzü
├── main.py              # FastAPI backend uygulaması
├── .env                 # Gizli API anahtarlarını içerir (git'e dahil edilmez)
├── .gitignore           # Git için ihmal dosyası
├── requirements.txt     # Proje bağımlılıkları
└── README.md            # Proje dokümantasyonu


.env dosyanızı oluşturun ve içine Gemini API anahtarınızı ekleyin:
GEMINI_API_KEY=your_api_key_here

---


▶️ Çalıştırma

1. Backend (FastAPI)
uvicorn main:app --reload --port 8000

2. Frontend (Gradio)
python app.py

---

👩‍💻 Geliştirici

Developed with ❤️ by Hayat Aydın  
📂 [GitHub Profilim](https://github.com/aydnhayatt)

---

⭐ Destek Ol
Bu repo işine yaradıysa ⭐ bırakmayı ve takip etmeyi unutma:
👉 GitHub’da beni ziyaret et 👩‍💻✨
