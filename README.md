# Zepi Calendar – Android Testversion

[**APK direkt herunterladen**](https://github.com/zepi2509/zepi-calendar-downloads/releases/download/android-test/zepi-calendar.apk)

![Installations-QR-Code](https://github.com/zepi2509/zepi-calendar-downloads/releases/download/android-test/install-qr.png)

**QR scannen → APK herunterladen → öffnen → Installation bestätigen.**
Kein GitHub-Login und kein Entpacken nötig. Android kann einmalig die Erlaubnis
zur Installation aus dem Browser/Dateimanager verlangen.

Der QR-Code bleibt für neue Testversionen gleich. Die APK nutzt eine feste
Test-Signatur und steigende Versionsnummern für Updates ohne Deinstallation.
Eine ältere Expo-/CI-/lokale Installation mit anderer Signatur muss ggf. zuerst
entfernt werden: **vorher lokale Daten sichern**, da eine Deinstallation sie löscht.

Android 8.0+ (API 26), vier ABIs. Dies ist eine Debug-/Testversion, keine
Store-Version. CI prüft die tatsächliche API-35-Emulator-Installation inklusive
AndroidKeyStore, nativer SQLite, Oberfläche und Alarm-/Benachrichtigungsadapter.
Physische Geräte, Permission-Dialoge, Notification-Öffnen/Doze/Reboot und
Accessibility sind dadurch nicht zertifiziert.

Dieses öffentliche Repository enthält nur APK, Prüfsumme, Build-Metadaten und
QR-Code. Der Anwendungscode bleibt privat. Die [Test-Release-Seite](https://github.com/zepi2509/zepi-calendar-downloads/releases/tag/android-test)
enthält SHA-256-Prüfsumme, Signatur-Fingerprint und die geprüfte Build-Identität.
