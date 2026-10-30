<div align="center">

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Stethoscope.png" width="110" alt="Stethoscope">

# Context-Med (Fork)

<img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=22&duration=2600&pause=700&color=2563EB&center=true&vCenter=true&width=600&lines=Research%20%E2%86%92%20academic%20outputs;My%20part%3A%20the%20context-cert%20package;Fork%20of%20seyyah%2Fcontext-med" alt="Research → academic outputs">

<p>
  <img src="https://img.shields.io/badge/Fork%20of-seyyah%2Fcontext--med-17202C?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.11%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

<a href="#-english"><b>🇬🇧 English</b></a> · <a href="#-türkçe"><b>🇹🇷 Türkçe</b></a>

</div>

<br>

<table align="center">
  <tr>
    <td align="center" width="25%"><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Page%20Facing%20Up.png" width="40" alt="Page Facing Up"><br><b>Paper</b><br><sub>manuscript</sub></td>
    <td align="center" width="25%"><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Artist%20Palette.png" width="40" alt="Artist Palette"><br><b>Visual abstract</b><br><sub>JAMA/NEJM style</sub></td>
    <td align="center" width="25%"><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Shield.png" width="40" alt="Shield"><br><b>Privacy</b><br><sub>PII masking</sub></td>
    <td align="center" width="25%"><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Sports%20Medal.png" width="40" alt="Sports Medal"><br><b>context-cert</b><br><sub>my contribution</sub></td>
  </tr>
</table>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Clapper%20Board.png" width="32" align="center"> Demo

<div align="center">
  <img src="packages/context-cert/demo/certification_programs_dash.png" width="32%" alt="Certification programs dashboard"> <img src="packages/context-cert/demo/quiz_session_view.png" width="32%" alt="Quiz session"> <img src="packages/context-cert/demo/approval_curation_panel.png" width="32%" alt="Approval and curation panel"><br><sub>context-cert demo: programs dashboard · quiz session · approval panel</sub>
</div>

---

## 🇬🇧 English

> This repository is my fork of [seyyah/context-med](https://github.com/seyyah/context-med). The upstream project description is in [`README.md1`](README.md1).

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Memo.png" width="26" align="center"> What is Context-Med?
**Context-Med** is an end-to-end pipeline that turns raw sources uploaded by researchers (PDF papers, theses, patient data, etc.) into academic outputs:

- **Visual Abstract** (`context-va`) — graphical abstract in JAMA/NEJM style
- **Manuscript** (`context-paper`) — full academic paper
- **Slides** (`context-slides`) — conference slide deck
- **Narrated Audio** (`context-narrate`) — narrated abstract

The whole process is orchestrated by `context-core` and follows medical privacy rules via `context-shield`.

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Technologist.png" width="26" align="center"> My Contribution: `context-cert`
I worked on the **`context-cert`** package in `packages/context-cert`:
* CLI commands and comprehensive CLI tests
* A dashboard demo with a downloadable PDF certificate and quiz hints, translated into Turkish
* A local dev server for the demo panel
* CI fixes so the evaluation workflows run correctly for forks and Node.js packages

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/File%20Folder.png" width="26" align="center"> Packages
`packages/` contains the monorepo packages, including `context-core`, `context-shield`, `context-gate`, `context-wiki`, `context-va`, `context-paper`, `context-slides`, `context-narrate`, `context-cert` and more.

---

## 🇹🇷 Türkçe

> Bu repo, [seyyah/context-med](https://github.com/seyyah/context-med) projesinin benim fork'umdur. Orijinal proje açıklaması [`README.md1`](README.md1) dosyasındadır.

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Memo.png" width="26" align="center"> Context-Med Nedir?
**Context-Med**, araştırmacıların yüklediği ham kaynakları (PDF makale, tez, hasta verisi vb.) akademik çıktılara dönüştüren uçtan uca bir pipeline'dır:

- **Visual Abstract** (`context-va`) — JAMA/NEJM standartlarında grafik özet
- **Manuscript** (`context-paper`) — tam akademik makale
- **Slides** (`context-slides`) — konferans sunum destesi
- **Narrated Audio** (`context-narrate`) — makale seslendirme

Tüm süreç `context-core` tarafından yönetilir ve `context-shield` ile tıbbi gizlilik kurallarına uygun çalışır.

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Technologist.png" width="26" align="center"> Katkım: `context-cert`
`packages/context-cert` altındaki **`context-cert`** paketi üzerinde çalıştım:
* CLI komutları ve kapsamlı CLI testleri
* Türkçeye çevrilmiş, PDF sertifika indirme ve quiz ipuçları içeren dashboard demosu
* Demo paneli için yerel geliştirme sunucusu
* Değerlendirme iş akışlarının fork'larda ve Node.js paketlerinde doğru çalışması için CI düzeltmeleri

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/File%20Folder.png" width="26" align="center"> Paketler
`packages/` klasörü monorepo paketlerini içerir: `context-core`, `context-shield`, `context-gate`, `context-wiki`, `context-va`, `context-paper`, `context-slides`, `context-narrate`, `context-cert` ve diğerleri.


<br>

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Red%20Heart.png" width="22" align="center" alt="Red Heart">
  <sub>Made by <a href="https://github.com/huseyinbaranisik">Hüseyin Baran Işık</a> · Animated emojis: <a href="https://github.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis">Animated Fluent Emojis</a></sub>
</div>
