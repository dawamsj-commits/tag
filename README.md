# Toyota Kalkulator Android

Project aplikasi Android untuk Kalkulator Toyota.

## Build APK tanpa Android Studio

1. Buat repository GitHub baru.
2. Upload **semua isi folder project ini**, termasuk folder `.github`.
3. Pastikan `.github/workflows/build-apk.yml` ada di root repository.
4. Buka menu **Actions**.
5. Pilih **Build Toyota Kalkulator APK**.
6. Tekan **Run workflow**.
7. Setelah selesai, buka hasil workflow dan download artifact **ToyotaKalkulator-APK**.
8. Extract artifact untuk mendapatkan `app-debug.apk`.

Workflow juga otomatis berjalan setiap kali ada push ke branch `main` atau `master`.
