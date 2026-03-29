
# 🛡️ Proje Önerisi: Trust Circle

## 👤 Genel Bilgiler
* **Öneren:** Yunus
* **Proje Adı:** Trust Circle

---

## 🎯 Hedef Track (Multi-Track)
* **World ($20,000):** En İyi Mini Uygulama ödülü (MiniKit entegrasyonu ile).
* **LayerZero ($20,000):** Omnichain Identity & State (Zincirler arası güven verisi taşıma).
* **Circle ($10,000):** En İyi USDC Kullanımı (Kredilerin USDC ile dağıtılması).
* **ENS ($10,000):** Kullanıcıların .eth isimleri üzerinden birbirini tanıması ve borçlanması.

---

## ⚠️ Problem
1.  **Aşırı Teminatlandırma:** Mevcut DeFi (Aave vb.) 100$ borç için 150$ varlık kilitleme gerektirir.
2.  **Sosyal Güven Eksikliği:** Kriptoda bot hesaplar ve anonimlik riski nedeniyle "arkadaş kredisi" mekanizması yoktur.
3.  **Yüksek Gas:** Mikro-kredi işlemlerinde gas ücretleri borç miktarını aşabiliyor.

---

## ✅ Çözüm
* **Teminatsız Sosyal Kredi:** World ID (Proof of Personhood) ile sadece gerçek insanların katılabildiği ağ.
* **Güven Çemberi:** Kullanıcıların birbirine "Güven Limiti" tanımladığı bir sistem.
* **Vouching:** 3 kişiden onay alan kullanıcı, havuzdan teminat vermeden anlık USDC çekebilir.
* **Cross-Chain İtibar:** LayerZero sayesinde Base'deki güven puanı Arbitrum'da kullanılabilir.

---

## 🛠 Teknik Stack
* **Frontend:** Next.js + Tailwind CSS (MiniKit uyumlu).
* **Identity:** World MiniKit SDK (Doğrulama + Pay komutu).
* **Messaging:** LayerZero V2 (lzRead ile zincirler arası veri okuma).
* **Assets & Naming:** Circle USDC & ENS.
* **Blockchain:** World Chain (Gas-free işlemler).

---

## 🚀 MVP (Kritik Özellikler - 48/72 Saat)
1.  **World ID Login:** MiniKit ile "Gerçek İnsan" onayı.
2.  **Kefil Olma (Vouching):** ENS üzerinden güven limiti tanımlama ve contract entegrasyonu.
3.  **Mikro-Ödeme:** `minikit.pay` ile gas ücreti ödemeden USDC aktarımı.

---

## 🏆 Neden Kazanırız?
* **Gerçek Kullanım:** 23 milyonluk World ID kitlesine DeFi'nin eksiği olan "teminatsız borçlanmayı" sunuyoruz.
* **Sıfır Sürtünme:** Cüzdan kurulumu veya gas derdi yok; tanıdık mobil uygulama deneyimi.
* **Teknik Derinlik:** Sadece transfer değil, LayerZero ile omnichain "Güven Durumu" (State) yönetimi.
