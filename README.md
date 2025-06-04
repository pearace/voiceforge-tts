# VoiceForge - AI Text to Speech Web App 🎙️

VoiceForge adalah aplikasi web full-stack yang memudahkan pengguna untuk mengubah teks menjadi suara alami menggunakan ElevenLabs API, dengan fitur autentikasi, langganan bulanan via Stripe, dan pelacakan kuota penggunaan.

## ✅ Fitur Utama

- 🔊 Text to Speech via ElevenLabs
- 🔐 Login dengan Google via Firebase Auth
- 💳 Langganan Bulanan via Stripe
- 📊 Pelacakan Kuota Penggunaan
- 🔒 Backend Proxy API untuk keamanan API Key

## 🛠️ Teknologi yang Digunakan

- Frontend: React + TailwindCSS
- Backend: Node.js + Express
- Auth: Firebase Authentication
- Payment: Stripe Checkout
- TTS: ElevenLabs.io
- DB: Firebase Firestore (untuk tracking kuota)

## 🚀 Cara Menjalankan Aplikasi

### 1. Clone repo

```bash
git clone https://github.com/<username>/voiceforge-tts.git 
cd voiceforge-tts
