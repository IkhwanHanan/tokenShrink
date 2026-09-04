# ⚡ TokenShrink

**TokenShrink** adalah middleware & SDK open-source ringan yang memotong biaya API LLM hingga **50% - 80%** menggunakan kombinasi **NLP Pre-processing**, **Semantic Caching**, dan **YAGNI (You Aren't Gonna Need It) Output Compression**.

![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.10%2B-blue)

---

## 🚀 Fitur Utama

- **Prompt Minifier (Input)**: Membersihkan *filler words* dan basa-basi sebelum dikirim ke API tanpa mengubah arti/maksud.
- **Semantic Vector Cache (0-Token)**: Mengidentifikasi pertanyaan dengan makna serupa menggunakan kemiripan vektor lokal (*Cosine Similarity*).
- **YAGNI Compression Engine**: Memaksa LLM menghasilkan JSON/Output terkompresi tanpa *whitespace* dan field redundan.
- **Local Decompressor**: Mengubah balik schema ringkas menjadi format JSON utuh secara instan di sisi client.

---

## 📦 Instalasi

```bash
pip install tokenshrink
