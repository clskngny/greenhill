# Green Hill Run - Online APK projesi

Uygulama, https://frosty-forest-3e83.clskngny.workers.dev adresindeki oyunu tam ekran ve yatay açar.
Oyunda yaptığın her güncelleme (Worker'a yüklediğinde) APK'yı yeniden derlemeden uygulamaya yansır. Internet gerekir.

## APK'yı almak (GitHub, bilgisayar gerekir)
1. github.com'da yeni repo aç, bu klasörün içindekileri (gizli `.github` klasörü dahil) yükle.
2. Actions -> "APK derle" -> bitince "GreenHillRun-apk" dosyasını indir, içinden app-debug.apk çıkar.
3. Telefona kur.

Adresi değiştirmek için: app/src/main/java/com/greenhill/run/MainActivity.java içindeki loadUrl satırı.
Geri tuşu oyun menüsünü açar.
