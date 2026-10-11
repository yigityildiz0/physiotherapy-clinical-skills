<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" width="1280" alt="Physiotherapy &amp; Clinical Skills — clear questions, repeatable workflows, reviewable results">
</picture>

# Physiotherapy & Clinical Skills

[English](README.md) · [Türkçe](README.tr.md)

**Klinik akıl yürütme, rehabilitasyon kanıtları, öğrenme ve kriz desteği iş akışları.**

4 bakımı sürdürülen giriş noktası. Göreve göre birini seç; tüm kütüphaneyi bağlama yükleme.

[Başla](docs/INSTALL.md) · [Katalog](https://yigityildiz0.github.io/universal-ai-skill-library/) · [İndirmeler](DOWNLOADS.md) · [Bakım modeli](MAINTAINING.md)

## Yapmak istediğin işi seç

<details open>
<summary><strong>Öğrenme ve yazı</strong> · 1</summary>

| Skill | Ne işe yarar? |
|---|---|
| [academic-study-coach](docs/skills/academic-study-coach.tr.md) | Ders içeriğini çalışma planına, aktif hatırlamaya ve literatür okuma pratiğine dönüştürür. |

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
Maintained by [Yigit Yildiz](https://github.com/yigityildiz0) · Source edition 2026.10.11
