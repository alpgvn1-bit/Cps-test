========================================
  CPS TEST - Windows .exe Kurulum Rehberi
========================================

GEREKSINIM:
  Node.js kurulu olmalı → https://nodejs.org (LTS indir)

ADIMLAR:
  1. Bu klasörü bir yere çıkart (örn: C:\cps-electron)
  2. Klasörün içinde Shift + Sağ tık → "PowerShell penceresi aç"
  3. Şu komutları sırayla çalıştır:

     npm install
     npm run build

  4. "dist" klasörü oluşacak → içindeki .exe'yi kur veya doğrudan çalıştır

SADECE TEST ETMEK İSTİYORSAN (.exe olmadan):
  npm install
  npm start

  → Uygulama pencere olarak açılır, kurulum gerekmez.

SORUN YAŞARSAN:
  - Node.js kurulu mu kontrol et: node -v
  - npm sürümü: npm -v
  - En az Node.js 18+ olmalı

========================================
