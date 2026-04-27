# Berber Proje - Flutter & Firebase Barber Management System

Bu proje, berber işletmeleri ve müşterileri için geliştirilmiş, bulut tabanlı veri senkronizasyonu sunan çapraz platform bir yönetim sistemidir. Modern mobil ve web teknolojilerini kullanarak randevu süreçlerini dijitalleştirmeyi hedefler.

## 🚀 Proje Özeti

Berber Proje, servis sağlayıcılar (berberler) ile hizmet alan kullanıcıları ortak bir platformda buluşturur. Uygulama, gerçek zamanlı veri yönetimi ve güvenli kimlik doğrulama katmanları üzerine inşa edilmiştir. Android, iOS, Web ve Masaüstü (Windows/Linux) platformlarını destekleyen tek bir kod tabanından (single codebase) oluşmaktadır.

## 🛠 Kullanılan Teknolojiler

  * **Framework:** Flutter 3.24.3
  * **Dil:** Dart 3.5
  * **Backend & Veritabanı (Firebase):**
      * **Cloud Firestore:** Randevu ve kullanıcı verilerinin gerçek zamanlı takibi için NoSQL veritabanı.
      * **Firebase Authentication:** Güvenli oturum açma ve kayıt süreçleri.
      * **Firebase Core:** Temel servis entegrasyonu.
  * **Yerel Depolama:** `shared_preferences` (Kullanıcı durumu ve tercih yönetimi için).
  * **Bağımlılıklar:** `http`, `random_string`, `cupertino_icons`.

## 🏗 Mimari ve Yapılandırma

Proje, Flutter'ın çoklu platform desteğini optimize eden bir yapıya sahiptir:

  * **Modüler Yapı:** `lib/` dizini altında servisler, sayfalar ve veri modelleri ayrıştırılarak sürdürülebilir bir mimari hedeflenmiştir.
  * **Platform Uyumluluğu:**
      * **Android:** Gradle 8.3 tabanlı, Android API 29+ desteği.
      * **iOS/macOS:** `Info.plist` yapılandırmaları ve Apple Push Notification (APN) hazırlığı.
      * **Web:** Progressive Web App (PWA) desteği ve `manifest.json` yapılandırması.
      * **Desktop:** Windows (Win32 API/DPI aware) ve Linux (GTK+ 3.0) için CMake derleme sistemleri.

## ✨ Temel Özellikler

  * **Eşzamanlı Veri Akışı:** Cloud Firestore ile randevuların anlık olarak senkronize edilmesi.
  * **Oturum Yönetimi:** Firebase Auth ve `shared_preferences` entegrasyonu ile güvenli kullanıcı deneyimi.
  * **Geniş Platform Desteği:** Mobil cihazların yanı sıra web tarayıcıları ve masaüstü sistemlerde tam uyumlu çalışma.
  * **Modern UI:** Platforma özgü widget setleri ve duyarlı (responsive) tasarım.

-----

*Son Güncelleme: Jan 03, 2025*
