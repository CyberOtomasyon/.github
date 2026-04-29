# Katki Rehberi -- Cyber Otomasyon

## Branch Stratejisi

```
main        <- Uretim. Direkt push yasak.
develop     <- Aktif gelistirme.
feature/*   <- Yeni ozellikler.  or: feature/alarm-bildirimi
bugfix/*    <- Hata duzeltmeleri. or: bugfix/login-crash
hotfix/*    <- Canlidaki acil duzeltmeler.
release/*   <- Surum hazirligi. or: release/v2.1.0
```

## Gunluk Is Akisi

### 1. Yeni ozellik
```bash
git checkout develop
git pull origin develop
git checkout -b feature/ozellik-adi
```

### 2. Degisiklikleri kaydet
```bash
git add .
git commit -m "feat: ozellik eklendi"
git push origin feature/ozellik-adi
```

### 3. PR ac
- GitHub'da `feature/... => develop` PR ac
- En az 1 kisi review yapmali

## Commit Mesaji Standardi

```
<tur>: <kisa aciklama>
```

| Tur | Kullanim |
|---|---|
| feat | Yeni ozellik |
| fix | Hata duzeltme |
| refactor | Kod yeniden yazma |
| docs | Dokumantasyon |
| style | Format/stil |
| chore | Build, bagimlilik |
| hotfix | Acil uretim duzeltmesi |

### Ornekler
```bash
git commit -m "feat: alarm bildirimi eklendi"
git commit -m "fix: login crash duzeltildi"
git commit -m "docs: API endpoint listesi guncellendi"
```

## Sik Kullanilan Komutlar

```bash
git branch                 # Branch listesi
git stash                  # Degisiklikleri gecici sakla
git stash pop              # Geri getir
git log --oneline --graph  # Gorsel gecmis
git diff develop           # Develop'tan farklari gor
```
