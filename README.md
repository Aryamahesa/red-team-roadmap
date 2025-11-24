# Exploit Roadmap - Web Security Learning Tracker

![Status](https://img.shields.io/badge/Status-OWASP%20TOP%2010%20Aligned-green)
![Version](https://img.shields.io/badge/Version-1.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📋 Deskripsi

**Exploit Roadmap** adalah aplikasi web interaktif yang dirancang untuk membantu Anda melacak progres pembelajaran keamanan web (web security). Aplikasi ini menyediakan jalur pembelajaran terstruktur dari tingkat pemula hingga ahli, dengan fokus pada vulnerabilitas web yang paling umum dan berbahaya berdasarkan **OWASP Top 10 (2021)**.

---

## 🎯 Tujuan

Aplikasi ini membantu Anda untuk:

- ✅ **Menguasai 80% vulnerabilitas** yang ditemukan di dunia nyata
- 🏆 **Mempersiapkan diri untuk Bug Bounty Programs**
- 📜 **Siap mengikuti sertifikasi** seperti BSCP (Burp Suite Certified Practitioner) dan eWPT
- 📈 **Melacak progres pembelajaran** secara visual dan terstruktur

---

## ✨ Fitur Utama

### 1. 📚 **Pembelajaran Bertahap (4 Phase)**

Materi dibagi menjadi 4 fase pembelajaran berdasarkan tingkat prioritas dan kompleksitas:

#### **Phase 1: Foundation (Critical)** - 4 topik fundamental
- SQL Injection
- Cross-site Scripting (XSS)
- Authentication Vulnerabilities
- Access Control Vulnerabilities

#### **Phase 2: Intermediate (High)** - 5 topik pengembangan
- CSRF (Cross-Site Request Forgery)
- SSRF (Server-Side Request Forgery)
- XXE Injection
- OS Command Injection
- Path Traversal

#### **Phase 3: Advanced (Medium)** - 8 topik kompleks
- Server-side Template Injection
- Insecure Deserialization
- Business Logic Vulnerabilities
- File Upload Vulnerabilities
- Information Disclosure
- JWT Attacks
- OAuth Authentication
- NoSQL Injection

#### **Phase 4: Specialized (Specialized)** - 13 topik khusus
- HTTP Request Smuggling
- HTTP Host Header Attacks
- Web Cache Poisoning
- Web Cache Deception
- Clickjacking
- DOM-based Vulnerabilities
- WebSockets
- CORS
- API Testing
- Web LLM Attacks
- GraphQL API Vulnerabilities
- Race Conditions
- Prototype Pollution

---

### 2. 📊 **Pelacakan Progress Real-time**

- ✔️ Checkbox interaktif untuk menandai topik yang sudah dipelajari
- 📊 Persentase progres per fase
- 🎯 Total mastery percentage
- 💾 Progress tersimpan otomatis di browser (localStorage)

---

### 3. 🏆 **Sistema Level**

Sistem level yang memotivasi pembelajaran:

| Level | Progress | Emoji |
|-------|----------|-------|
| Script Kiddie | 0-19% | 🆕 |
| Apprentice | 20-39% | 📚 |
| Practitioner | 40-59% | ⚡ |
| Expert | 60-79% | 🎓 |
| Elite Hacker | 80-100% | 👑 |

---

### 4. 📝 **Informasi Lengkap**

Setiap topik dilengkapi dengan:

- 📝 **Deskripsi singkat** tentang vulnerability
- 🎨 **Badge level kesulitan** (Critical, High, Medium, Low)
- 🔗 **Badge OWASP Top 10** kategori
- 🌐 **Link langsung** ke materi PortSwigger Web Security Academy

---

### 5. 📈 **Dashboard Informatif**

- 🎯 **Your Target**: Tujuan pembelajaran yang jelas
- 💡 **Study Tips**: Tips belajar efektif
- 📊 **Mastery Card**: Statistik progress secara visual

---

## 🚀 Cara Menggunakan

### Metode 1: Langsung Buka File

1. Download file `index.html`
2. Buka file tersebut menggunakan browser modern (Chrome, Firefox, Edge, Safari)
3. Mulai belajar dan centang topik yang sudah Anda kuasai!

### Metode 2: Hosting Lokal
```bash