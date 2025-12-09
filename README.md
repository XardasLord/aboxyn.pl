# Aboxyn - Landing Page

Nowoczesny landing page dla Aboxyn - systemu zarządzania zamówieniami e-commerce dla sklepów z elektroniką, RTV, AGD i GSM.

## 🚀 Funkcje

- ✅ Responsywny design (mobile-first)
- ✅ TailwindCSS
- ✅ Formularz zapisu na listę oczekujących z walidacją
- ✅ SEO optimized (meta tagi, semantic HTML)
- ✅ Smooth scroll navigation
- ✅ Custom favicon i web manifest
- ✅ Zero dependencies (poza TailwindCSS CDN)

## 📁 Struktura plików

```
aboxyn.pl/
├── index.html                  # Główny plik landing page
├── favicon.svg                 # SVG favicon
├── favicon-16x16.png          # Favicon 16x16
├── favicon-32x32.png          # Favicon 32x32
├── apple-touch-icon.png       # Apple touch icon 180x180
├── android-chrome-192x192.png # Android icon 192x192
├── android-chrome-512x512.png # Android icon 512x512
├── site.webmanifest           # Web app manifest
├── generate-favicons.html     # Narzędzie do generowania faviconów
└── README.md                  # Ten plik
```

## 🎨 Generowanie faviconów

Pliki favicon zostały przygotowane. Jeśli chcesz je wygenerować ponownie:

1. Otwórz `generate-favicons.html` w przeglądarce
2. Pliki PNG zostaną automatycznie pobrane
3. Przenieś je do głównego katalogu projektu

Favicon SVG jest już gotowy i nie wymaga generowania.

## 🔧 Integracja z Kit (ConvertKit)

W pliku `index.html` w sekcji `<script>` na końcu pliku znajdziesz komentarz z przykładem integracji:

```javascript
// TODO: Connect to Kit (ConvertKit) mailing system
```

Aby podłączyć Kit:

1. Zarejestruj się na https://convertkit.com
2. Stwórz formularz
3. Znajdź API Key i Form ID
4. Zamień zakomentowany kod na właściwy z Twoimi danymi

Przykład integracji:
```javascript
fetch('https://api.convertkit.com/v3/forms/YOUR_FORM_ID/subscribe', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify({
        api_key: 'YOUR_API_KEY',
        email: email,
        tags: ['aboxyn-waitlist']
    })
})
```

## 🎯 Sekcje strony

1. **Hero** - Główny przekaz z CTA
2. **Problemy** - Pain points klientów
3. **Killer Feature** - Szablony paczek
4. **Moduły** - 6 głównych funkcjonalności
5. **Jak to działa** - 3-stopniowy proces
6. **Dla kogo** - Segmenty docelowe
7. **Social Proof** - Statystyki
8. **Waitlist CTA** - Formularz zapisu

## 🎨 Kolorystyka

- Primary: `#9333ea` (fiolet)
- Odcienie: `#7e22ce`, `#a855f7`, `#c084fc`
- Neutralne: szarości od `#f9fafb` do `#111827`

## 📱 Responsywność

Strona jest w pełni responsywna z breakpointami:
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

## 🚀 Deployment

Strona jest gotowa do wdrożenia na:
- Netlify
- Vercel
- GitHub Pages
- Dowolny hosting statyczny

Wystarczy wrzucić pliki i gotowe!

## 📝 Licencja

© 2025 Aboxyn. Wszelkie prawa zastrzeżone.

