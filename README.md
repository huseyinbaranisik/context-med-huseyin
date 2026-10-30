# <p align="center">🩺 CONTEXT-MED (Fork)</p>
## <p align="center">AI-Powered Academic Publication Pipeline for Medical Researchers</p>

<p align="center">
  <img src="https://img.shields.io/badge/Fork%20of-seyyah%2Fcontext--med-17202C?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.11%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

<p align="center">
  <a href="#-english"><b>🇬🇧 English</b></a> · <a href="#-türkçe"><b>🇹🇷 Türkçe</b></a>
</p>

---

## 🇬🇧 English

> This repository is my fork of [seyyah/context-med](https://github.com/seyyah/context-med). The upstream project description is in [`README.md1`](README.md1).

### 📝 What is Context-Med?
**Context-Med** is an end-to-end pipeline that turns raw sources uploaded by researchers (PDF papers, theses, patient data, etc.) into academic outputs:

- **Visual Abstract** (`context-va`) — graphical abstract in JAMA/NEJM style
- **Manuscript** (`context-paper`) — full academic paper
- **Slides** (`context-slides`) — conference slide deck
- **Narrated Audio** (`context-narrate`) — narrated abstract

The whole process is orchestrated by `context-core` and follows medical privacy rules via `context-shield`.

### 🧑‍💻 My Contribution: `context-cert`
I worked on the **`context-cert`** package in `packages/context-cert`:
* CLI commands and comprehensive CLI tests
* A dashboard demo with a downloadable PDF certificate and quiz hints, translated into Turkish
* A local dev server for the demo panel
* CI fixes so the evaluation workflows run correctly for forks and Node.js packages

### 📁 Packages
`packages/` contains the monorepo packages, including `context-core`, `context-shield`, `context-gate`, `context-wiki`, `context-va`, `context-paper`, `context-slides`, `context-narrate`, `context-cert` and more.

---

## 🇹🇷 Türkçe

> Bu repo, [seyyah/context-med](https://github.com/seyyah/context-med) projesinin benim fork'umdur. Orijinal proje açıklaması [`README.md1`](README.md1) dosyasındadır.

### 📝 Context-Med Nedir?
**Context-Med**, araştırmacıların yüklediği ham kaynakları (PDF makale, tez, hasta verisi vb.) akademik çıktılara dönüştüren uçtan uca bir pipeline'dır:

- **Visual Abstract** (`context-va`) — JAMA/NEJM standartlarında grafik özet
- **Manuscript** (`context-paper`) — tam akademik makale
- **Slides** (`context-slides`) — konferans sunum destesi
- **Narrated Audio** (`context-narrate`) — makale seslendirme

Tüm süreç `context-core` tarafından yönetilir ve `context-shield` ile tıbbi gizlilik kurallarına uygun çalışır.

### 🧑‍💻 Katkım: `context-cert`
`packages/context-cert` altındaki **`context-cert`** paketi üzerinde çalıştım:
* CLI komutları ve kapsamlı CLI testleri
* Türkçeye çevrilmiş, PDF sertifika indirme ve quiz ipuçları içeren dashboard demosu
* Demo paneli için yerel geliştirme sunucusu
* Değerlendirme iş akışlarının fork'larda ve Node.js paketlerinde doğru çalışması için CI düzeltmeleri

### 📁 Paketler
`packages/` klasörü monorepo paketlerini içerir: `context-core`, `context-shield`, `context-gate`, `context-wiki`, `context-va`, `context-paper`, `context-slides`, `context-narrate`, `context-cert` ve diğerleri.
