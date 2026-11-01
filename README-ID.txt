MIEL PERFORMANCE V2 — NATIVE ANDROID JAVA

PENTING:
- Project ini dibuat untuk build di cloud melalui GitHub Actions, supaya HP tidak perlu memasang Android Studio/Android IDE atau mengunduh Android SDK besar.
- Acode hanya dipakai untuk melihat/mengedit file.
- APK debug hasil build dapat diunduh dari tab Actions > workflow yang selesai > Artifacts.
- Untuk membuat APK, upload seluruh isi folder project ini ke repository GitHub baru pada branch main, termasuk folder .github.
- Jalankan workflow melalui Actions > Build MIEL PERFORMANCE APK > Run workflow.
- Setelah selesai, unduh artifact MIEL-PERFORMANCE-V2-APK dan ekstrak app-debug.apk.

FITUR YANG SUDAH DIIMPLEMENTASIKAN:
- Native Android Java Activity.
- Profil terpisah Free Fire dan Free Fire MAX.
- Slider profil sensitivitas tersimpan lokal (bukan mengubah sensitivitas internal game).
- Preferensi 60/90/120 Hz tersimpan (bukan memaksa refresh rate perangkat).
- Informasi baterai, RAM tersedia, Android, model perangkat, dan refresh rate layar.
- Tombol membuka game berdasarkan package name resmi yang umum dipakai.
- Floating overlay native dengan izin "Display over other apps".

BATASAN:
- Preview 16:9 hanya panel preview aplikasi, tidak mengubah rasio layar game.
- Overlay merupakan panel utility sederhana, bukan menu modifikasi game.
- Ketersediaan refresh rate aktual bergantung pada perangkat dan pengaturan sistem.
- Package game dapat berbeda menurut distribusi/versi. Jika game tidak ditemukan, tombol akan memberi notifikasi.
- Jangan berikan izin overlay kepada aplikasi yang tidak dipercaya.

MINIMUM:
- Android 6.0 (API 23)
- Build cloud: JDK 17, Gradle 8.9, Android Gradle Plugin 8.7.3
