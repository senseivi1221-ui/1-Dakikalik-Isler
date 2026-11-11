# 1 Dakikalık İşler (1 Minute Jobs)

**3B Oyun Geliştirme – 3D Açık Dünya Prototipi** · Hazırlayan: **Yiğit Efe Erkişi** · Beykent Üniversitesi · Sürüm 1.0 Demo · Kasım 2026

![Logo](1_dakikalik_isler_logo_koyu.png)

## Oyna
- **Web (itch.io):** https://yigitefeerkisi.itch.io/1-dakikalk-ler
- **Windows + Unity projesi:** [Releases v1.0](https://github.com/senseivi1221-ui/1-Dakikalik-Isler/releases/tag/v1.0) sayfasından indir.

> Web sürümü tarayıcıda çalıştığı için bilgisayara göre düşük FPS verebilir. En akıcı deneyim için Windows sürümünü öneririz.

## Oyun Özeti
Şehre yeni taşınan karakter boş ve kirli bir evde, cebinde para olmadan uyanır. Mahallede herkesin acil bir işi vardır ama hepsinin tek bir şartı vardır: **1 DAKİKA**. Telefondaki İş Bul uygulamasından ilan alınır, rota takip edilir, işverenle konuşulur ve **10 nesne 60 saniye içinde itilerek 10 deliğe** sokulur.

- **1. Gün:** Kargocu Ahmet – 10 kargo kutusu (bazıları kaçar)
- **2. Gün:** Ev temizliği + Manav Fatma Teyze – 10 karpuz
- **3. Gün:** Akşam, yağmur ve rüzgâr – Çöpçü Hasan Abi – 10 çöp poşeti
- **Final:** Gizemli bir mesaj… *Demo – Devamı Yakında*

## Kontroller
| Tuş | İşlev |
|---|---|
| W A S D | Yürü |
| Shift | Koş |
| Space | Zıpla |
| Fare / Tekerlek | Kamera / yakınlaştır |
| E / Sol tık | Konuş, diyaloğu geç, süpür |
| T | Telefon (İş Bul, Mağaza, Kıyafetlerim, Mesajlar, Ayarlar) |
| M | Büyük harita |
| G + 1-2-3 | Dans çarkı |
| ESC | İmleci serbest bırak |

## Teknik
- Unity 6 (6000.3), URP, C#, Input System, TextMeshPro
- Animator blend tree (Idle / Walk / Run), zıplama, 3 dans
- Rigidbody fizik ile itme, kaçan nesneler, rüzgâr
- Gün-gece döngüsü, yağmur, mini harita + büyük harita, telefon arayüzü, ses ayarları
- Sahne: `Assets/KacanKargo/Scenes/KacanKargo.unity` · Kurulum: **Kargo > Sahneyi Kur**
