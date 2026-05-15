# Renovator Saga — Landing Page

Wgraj pliki na serwer pod: `https://volt-pixel.com/RenovatorSaga/`

## Struktura

```
index.html          <- strona główna
style.css           <- style
docs/
  privacy-policy.html
img/
  icon.png          <- ikona gry (512x512 lub 1024x1024, kwadrat)
  hero-screenshot.png  <- screenshot gry (telefon/portret, ~400x700px)
  screen1.png       <- "Solve puzzles, earn stars"      (portret)
  screen2.png       <- "Your home, your style"          (portret)
  screen3.png       <- "Before & after magic"           (portret)
  screen4.png       <- "Multiple rooms to renovate"     (portret)
  characters.png    <- Maja i Alex                      (dowolny)
  google-play-badge.png  <- oficjalna odznaka Google Play
  og-image.png      <- social share preview (1200x630)
```

## Odznaka Google Play

Pobierz oficjalną odznakę: https://play.google.com/intl/en_us/badges/
Zapisz jako `img/google-play-badge.png`.

## Deploy

Skopiuj cały folder na serwer (FTP / rsync / panel hostingu):
- Wszystkie pliki z `RenovatorSaga/` -> `public_html/RenovatorSaga/`

Strona będzie dostępna pod: https://volt-pixel.com/RenovatorSaga/
Polityka prywatności: https://volt-pixel.com/RenovatorSaga/docs/privacy-policy.html
