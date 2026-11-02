# Katkı Rehberi

Katkı vermek için zaman ayırdığın için teşekkürler. Bu rehber, kendi `CONTRIBUTING.md` dosyası
olmayan [github.com/sametbrr](https://github.com/sametbrr) altındaki tüm açık repolar için geçerlidir.

> 🇬🇧 For English see [CONTRIBUTING.md](CONTRIBUTING.md)

## Nasıl katkı verebilirsin

| Ne yapmak istiyorsun | Nereye |
|---|---|
| Soru sormak, fikir paylaşmak, yaptığını göstermek | reponun **Discussions** sekmesi |
| Hata bildirmek | hata bildirimi formuyla yeni bir **Issue** |
| Özellik istemek | özellik isteği formuyla yeni bir **Issue** ya da Ideas tartışması |
| Güvenlik açığı bildirmek | **Security → Report a vulnerability** (asla herkese açık issue değil), bkz. [SECURITY.md](SECURITY.md) |
| Bir şeyi düzeltmek | pull request (aşağıya bak) |

Issue ve tartışmalar Türkçe ya da İngilizce olabilir.

## Pull request'ler

1. Yazım hatasından büyük her değişiklik için önce bir issue ya da tartışma aç, yaklaşımda anlaşalım.
2. Repoyu fork'la ve varsayılan daldan (`main` ya da `master`) bir dal aç.
3. Değişikliği odaklı tut: her pull request'te tek bir düzeltme ya da özellik.
4. Mevcut kod stiline uy ve reponun belirttiği kontrolleri çalıştır (testler, linter'lar, agent
   plugin'leri için `claude plugin validate .`).
5. Değişikliğin etkilediği dokümantasyonu güncelle. `README.tr.md` olan repolarda onu
   `README.md` ile senkron tut.
6. Anlaşılır bir commit mesajı yaz, tercihen [Conventional Commits](https://www.conventionalcommits.org/)
   (`fix: …`, `feat: …`, `docs: …`).
7. Pull request şablonunu doldur ve ilgili issue'yu bağla.

Sürüm, sürüm artışı ve tag işlemlerini bakımcı yapar.

## İlk katkı için

[`good first issue`](https://github.com/search?q=user%3Asametbrr+label%3A%22good+first+issue%22+state%3Aopen&type=issues)
etiketli issue'lar küçük ve net tanımlıdır; başlamak için iyi bir yer.

## Davranış kuralları

Katılan herkesin [Davranış Kuralları](CODE_OF_CONDUCT.md)'na uyması beklenir.

## Lisans

Katkı vererek, katkının katkı verdiğin reponun lisansıyla (çoğunda MIT) lisanslanmasını kabul etmiş olursun.
