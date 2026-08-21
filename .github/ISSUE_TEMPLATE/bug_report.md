---
name: Hata Bildirimi
about: Bir hata veya beklenmeyen davranışı bildirin
title: ''
labels: bug
assignees: ''
---

<!--
Doldurmadan önce:
- Aynı konuda açık bir taslak var mı diye ~/Documents/Obsidian Vault/issue önerileri/
  klasörüne (ve gönderilenler/ alt klasörüne) bakın — mükerrer olmasın.
- Başlığa repo'nun kendi adını (ör. [Backend]) EKLEMEYİN — hangi repoda
  olduğunuz zaten belli. Alt sistem/bileşen etiketi eklemek isterseniz
  [subscription], [chat] gibi kısa bir tag yeterli.
- Belirli bir geliştiriciyi/commiti suçlayan bir dil KULLANMAYIN — sadece
  kodun şu anki davranışını anlatın, kim/ne zaman yazdığını değil.
-->

## 🟢 TL;DR
<!-- 1-2 cümle: sorun ne, etkisi ne. -->

## Özet
<!-- Sorunun ne olduğu ve neden önemli olduğu — 1 paragraf. -->

## Etki
<!-- Numaralı liste: bu bug kimi/neyi nasıl etkiliyor. -->

### Düzeltilmezse
<!-- "Etki" bugünü anlatır, burası yarını: ertelenirse ne olacak? Öncelik
     tartışmasını bitirecek somut şeyler yazın — bu yüzden bekleyen bir iş,
     büyüyecek maruziyet (bugün 1 müşteri, dönüşüm başlayınca her yeni abone),
     geçici çözümün yetmediği durumlar, aynı hatanın tekrar etme ihtimali.
     Ertelemenin bilinen bir maliyeti yoksa bu bölümü tamamen silin —
     doldurmak için senaryo uydurmayın. -->

## 🩹 Geçici çözüm
<!-- Kalıcı düzeltme gelene kadar sahada/kullanıcıda ne yapılabilir? Somut ve
     uygulanabilir olsun (ör. "siyah ekran görülünce panelden restart",
     "APK'yı bir kez elle kur"). Bilinen bir geçici çözüm yoksa "Yok — kalıcı
     düzeltmeye kadar çalışmıyor" yazın; bölümü boş bırakmayın. -->

<!--
Aşağıdaki iki bölümden BİRİNİ seçin, ikisini birden kullanmayın (çakışırlar):

- Davranışsal bug ("X yapınca Y beklenir ama Z oluyor" tarzı, kullanıcı/istemci
  gözlemlenebilir bir istek-cevap çifti varsa): "Beklenen Davranış" +
  "Gerçekleşen Davranış" kullanın.
- Veri bütünlüğü / iç mantık bug'ı ("alan A her zaman B ile tutarlı olmalı ama
  değil" tarzı, ayrık bir kullanıcı eylemi yoksa): "Kanıt (gözlemlenen)"
  kullanın — ham log/JSON/DB kaydını gösterin.
-->

## Yeniden üretim
<!-- Numaralı adımlar. -->

## Kanıt (gözlemlenen)
<!-- Ham log çıktısı / API cevabı / DB kaydı — yukarıdaki adımların sonucu. -->

## Beklenen Davranış
<!-- Ne olması gerekiyordu. (Davranışsal bug'larda kullanın, veri bütünlüğü
     bug'larında "Kanıt" bölümü genelde yeterlidir.) -->

## Gerçekleşen Davranış
<!-- Ne oluyor. -->

## Kök neden (kod)
<!-- dosya:satır + kod parçası. Birden fazla ilgili bulgu varsa ayrı ## başlıkları
     yerine madde imleriyle listele. -->

## Önerilen çözüm
<!-- Somut kod önerisi, sadece düz yazı değil — Kök neden'deki kodun düzeltilmiş hâlini göster. -->

## Kabul kriterleri
- [ ]

## Mobil taraf notu
<!-- Bu bug mobil uygulamayı etkiliyorsa: mobil tarafta değişiklik gerekip
     gerekmediğini belirtin. İlgisizse bu bölümü tamamen silin. -->

## Bağlam / ilişkili
<!-- Bu bug hangi işin sırasında bulundu? Benzer/ilişkili ama kapsam dışı
     başka bir bulgu fark ettiyseniz burada not düşün (ayrı issue'ya konu
     olabilir). -->
