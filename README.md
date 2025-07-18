# 📘 Tanya Jawab Dokumen PDF dengan OpenAI & LangChain

Pernah ingin bertanya langsung pada file PDF seperti sedang ngobrol? Aplikasi ini memungkinkan anda melakukannya. Dengan bantuan LangChain dan OpenAI, kamu bisa mengajukan pertanyaan terhadap isi PDF apa pun, dan mendapatkan jawaban yang relevan seolah-olah kamu sedang berbicara dengan si dokumen itu sendiri.

---

## ✨ Apa yang Dilakukan Aplikasi Ini?

- 📄 Membaca dan mengekstrak isi file PDF
- ✂️ Memecah teks menjadi bagian-bagian kecil agar bisa diproses lebih baik
- 🧠 Membuat representasi vektor dari potongan teks dengan OpenAI Embeddings
- 🔎 Mencari bagian teks paling relevan berdasarkan pertanyaan pengguna
- 💬 Menghasilkan jawaban dengan model bahasa dari OpenAI

---

## 🧰 Teknologi yang Digunakan

| Komponen       | Deskripsi                          |
|----------------|-----------------------------------|
| Streamlit      | Antarmuka pengguna berbasis web   |
| PyPDF2         | Ekstraksi teks dari PDF           |
| LangChain      | Framework integrasi LLM & vector  |
| OpenAI API     | Embeddings dan Language Model     |
| FAISS          | Search engine berbasis vektor     |
| dotenv         | Manajemen secret key (API)        |

---
