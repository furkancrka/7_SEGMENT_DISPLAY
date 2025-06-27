# 🔢 EasyEDA – 7 Segment Gösterge Kartı

Bu proje, **EasyEDA** ile tasarlanmış **tek basamaklı (ortak katot) 7-segment LED gösterge** kartının tamamlanmış dosyalarını içerir.  
Amaç; düşük maliyetli, doğrudan **Arduino UNO**’ya takılabilen ve üretime hazır bir gösterge kartı geliştirmektir.

---

## 📂 Proje İçeriği

| Dosya / Klasör              | Açıklama                                   |
|-----------------------------|--------------------------------------------|
| [`schematic.pdf`](./schematic.pdf)      | Şematik diyagram (PDF)                  |
| [`PCB_Layout_Top.png`](./PCB_Layout_Top.png) | PCB’nin üst katman görünümü (PNG)       |
| [`PCB_3D_View.png`](./PCB_3D_View.png)  | 3-boyutlu PCB önizlemesi                |
| [`BOM.csv`](./BOM.csv)                  | Malzeme listesi (Bill of Materials)     |
| [`gerber/`](./gerber/)                  | Üretime hazır Gerber dosyaları          |
| `README.md`                             | Bu açıklama dosyası                     |

> **Not** – Tüm dosyalar bu `README` ile aynı klasörde durmalıdır;  
> aksi hâlde görsel ve linkler çalışmaz.

---

## 🖼️ Hızlı Görsel Bakış

![Şematik](./schematic.pdf)
![PCB Üst Katman](./PCB_Layout_Top.png)
![3D Önizleme](./PCB_3D_View.png)

---

## 📦 Temel BOM Özeti

| # | Parça                       | Değer / Model          | Miktar |
|---|-----------------------------|------------------------|-------:|
| 1 | 7-Segment Display           | 1 haneli – ortak katot | 1      |
| 2 | Direnç                      | 330 Ω                  | 7      |
| 3 | Erkek Header (Arduino)      | 2 × 6 + 1 × 8          | 2      |
| 4 | Baskı Devre (PCB)           | 2 kat, 70 mm × 35 mm   | 1      |

*Tüm ayrıntılar için lütfen `BOM.csv` dosyasını inceleyin.*

---

## ⚙️ Kurulum & Üretim

1. **Gerber** klasörünü PCB üreticisine (JLCPCB, PCBWay vb.) yükleyin.  
2. Parçaları `BOM.csv` dosyasına göre temin edin.  
3. Dirençleri ve LED modülü doğru yönlendirmeyle lehimleyin.  
4. Kartı Arduino UNO’ya takın, gerekli pinlere yazılımınızı yükleyin.

---

## 🎓 Kaynak

Bu tasarım, **BTK Akademi**’de tamamlanan  
*“Proteus ile Devre Tasarımı”* ve *“Temel Elektronik ve Robotiğe Giriş”*  
eğitimleri sonrasında geliştirilmiştir.

---

## 📜 Lisans

Bu proje **eğitsel amaçlı** olarak MIT Lisansı altında paylaşılmıştır.  
Dilediğiniz gibi kopyalayabilir, değiştirebilir ve dağıtabilirsiniz.  
Kaynak belirtmeniz yeterlidir.

---

> **Tarih:** 2025  **Hazırlayan:** Furkan Çurka
