<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" width="1280" alt="Physiotherapy &amp; Clinical Skills — clear questions, repeatable workflows, reviewable results">
</picture>

# Physiotherapy & Clinical Skills

[English](README.md) · [Türkçe](README.tr.md)

![Edition](https://img.shields.io/badge/edition-2026.10.14.2-0f6e8c) [![Validate](https://github.com/yigityildiz0/physiotherapy-clinical-skills/actions/workflows/validate.yml/badge.svg)](https://github.com/yigityildiz0/physiotherapy-clinical-skills/actions/workflows/validate.yml) [![Release](https://img.shields.io/github/v/release/yigityildiz0/physiotherapy-clinical-skills?display_name=tag&sort=date)](https://github.com/yigityildiz0/physiotherapy-clinical-skills/releases/latest) ![Skills](https://img.shields.io/badge/skill-5-b0303f) ![Languages](https://img.shields.io/badge/EN%20%2B%20TR-guides-e0a43a)

**Klinik akıl yürütme, rehabilitasyon kanıtları, öğrenme ve kriz desteği iş akışları.**

5 bakımı sürdürülen giriş noktası. Göreve göre birini seç; tüm kütüphaneyi bağlama yükleme.

[Başla](docs/INSTALL.md) · [Katalog](https://yigityildiz0.github.io/universal-ai-skill-library/) · [İndirmeler](DOWNLOADS.md) · [Bakım modeli](MAINTAINING.md)

## Bu sürümde yeni (2026.10.14.2)

- **presentation-studio** (yeni): düzenlenebilir PowerPoint sunumu baştan sona — hoca kuralları varsayılan, slayt planı, lisanslı gerçek fotoğraflar, JS ve Python tasarım kitleri, süreli ve okunuşlu konuşmacı notları, PowerPoint render kontrolü, `pptx_audit.py` ve sunum öncesi okuma kılavuzu.
- `slides` artık **html-slides**: yalnız tarayıcı sunumları; PowerPoint istekleri presentation-studio'ya gider.
- academic-study-coach, office-docs-qa, design ve design-system sunum üretimini presentation-studio'ya devreder (kırık PPTX bağlantısı düzeltildi).
- Gemini paketleri (CLI klasörleri ve filtreli Gemini uygulaması yüklemeleri), her uygulama için kurulum tablosu ve SHA-256 özetli gerçek GitHub Release.
- Her uygulama için skill başına tek ZIP, parçalara bölünmez; masaüstü sürümünde Claude için toplu yükleme grupları var.

## Hangi uygulamada?

| Uygulama | Paket |
|---|---|
| Claude Code | taşınabilir klasör → ~/.claude/skills |
| Claude.ai | skill başına bir yükleme ZIP'i |
| Codex / ChatGPT desktop | Codex.zip → ~/.codex/skills |
| ChatGPT web | hesap içe aktarma sunuyorsa eklenti ZIP'i |
| Gemini CLI / app | ~/.gemini/skills · Skills yükleme (filtreli kopya) |
| OpenCode · DeepSeek Harness | taşınabilir klasör + skills yolu |

Ayrıntılı adımlar: [Kurulum](docs/INSTALL.md). Dosyanın diskte olması etkin olduğunu kanıtlamaz; bir örnek istekle dene.

## Yapmak istediğin işi seç

<details open>
<summary><strong>Öğrenme ve yazı</strong> · 1</summary>

| Skill | Ne işe yarar? |
|---|---|
| [academic-study-coach](docs/skills/academic-study-coach.tr.md) | Ders içeriğini çalışma planına, aktif hatırlamaya ve literatür okuma pratiğine dönüştürür. |

</details>

<details open>
<summary><strong>Tasarım ve üretim</strong> · 1</summary>

| Skill | Ne işe yarar? |
|---|---|
| [presentation-studio](docs/skills/presentation-studio.tr.md) | Düzenlenebilir PowerPoint sunumunu baştan sona hazırlar: hoca kuralları varsayılan, slayt planı, lisanslı gerçek fotoğraflar, tasarım kiti, süreli ve okunuşlu konuşmacı notları, render kontrolü ve denetim. |

</details>

<details open>
<summary><strong>Sağlık ve rehabilitasyon</strong> · 3</summary>

| Skill | Ne işe yarar? |
|---|---|
| [medical-evidence-research](docs/skills/medical-evidence-research.tr.md) | Rehabilitasyon ve Türkiye uygulanabilirliği dahil tıbbi kanıtı arar, değerlendirir ve sentezler. |
| [mental-health-crisis-support](docs/skills/mental-health-crisis-support.tr.md) | Ruh sağlığı kriz işaretlerine sakin ve güvenlik odaklı yanıt vermeyi destekler. |
| [physio-clinical-copilot](docs/skills/physio-clinical-copilot.tr.md) | Klinisyen kontrolündeki rehabilitasyon akıl yürütmesi, değerlendirme ve taslak planlamayı destekler. |

</details>

## Bir skill nasıl çalışır?

~~~mermaid
flowchart LR
 A[Your goal] --> B[Match the skill]
 B --> C[Load relevant module]
 C --> D[Use available tools]
 D --> E[Verify and explain]
~~~

Bu bir iş akışıdır; araç çalıştırıldığı veya bütün sonuçların doğrulandığı iddiası değildir. Her skill sayfasında örnek istek, tetikleme, mekanik, girdi/çıktı ve kaynak modüller var.

## Tek kaynak, kalıcı koleksiyonlar

Ana kaynak [Universal AI Skill Library](https://github.com/yigityildiz0/universal-ai-skill-library). Alan depoları aynı sürümün seçilmiş görünümleridir; ayrı ayrı çatallanıp elle düzenlenmez. Mevcut bağlantılar ve geçmiş korunur.

[All collections / Tüm koleksiyonlar](COLLECTIONS.md) · [Legacy/community resources](LEGACY.md) · [Licenses & provenance](docs/LICENSE-SCOPE.md)

## Dürüst kapsam

- Skill kurmak model eğitmek veya hesap/araç bağlamak değildir.
- Yerel dosya ile web hesabına yükleme farklıdır; desteklenen host akışını kullan.
- Ek ücretli API veya model indirme otomatik yapılmaz.
- Eski topluluk kataloğu güncel giriş noktalarının sayısına veya test iddiasına dahil değildir.
- Kaynak lisansları korunur; bütün üçüncü taraf içeriğine tek lisans varsayılmaz.

---
Maintained by [Yigit Yildiz](https://github.com/yigityildiz0) · Source edition 2026.10.14.2
