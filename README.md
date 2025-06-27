# 🔢 EasyEDA – 7 Segment Gösterge Kartı

Bu proje, **EasyEDA** ile tasarlanmış **tek basamaklı (ortak katot) 7-segment LED gösterge** kartının tamamlanmış dosyalarını içerir.  
Amaç; düşük maliyetli, doğrudan devre kartlarına takılabilen ve üretime hazır bir gösterge kartı geliştirmektir.



## 🖼️ Hızlı Görsel Bakış

![Şematik](![schematic](https://github.com/user-attachments/assets/fd98cf77-b70e-416f-b628-66b0625b5a40))
![PCB Üst Katman](![upper layer](https://github.com/user-attachments/assets/6e261f70-6fd1-4288-b36f-f94722984562))
![3D Önizleme](![3D_View](https://github.com/user-attachments/assets/84e45d04-0937-4e5c-bc40-69abcebdae37))



## 📦 Temel BOM Özeti

| # | Parça                       | Değer / Model          | Miktar |
|---|-----------------------------|------------------------|-------:|
| 1 | 7-Segment Display           | 1 haneli – ortak katot | 1      |
| 2 | Direnç                      | 330 Ω                  | 7      |
| 3 | Erkek Header (Arduino)      | 2 × 6 + 1 × 8          | 2      |
| 4 | Baskı Devre (PCB)           | 2 kat, 70 mm × 35 mm   | 1      |

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

> **Tarih:** 2025  **Hazırlayan:** Furkan Fırat Çurka

SERTİFİKALAR
-- PROTEUS İLE DEVRE TASARIMI = [Proteus_ile_Devre_Tasarımı_Sertifika.pdf](https://github.com/user-attachments/files/20956405/Proteus_ile_Devre_Tasarimi_Sertifika.pdf)

-- TEMEL ELEKTRONİK VE ROBOTİĞE GİRİŞ = [Temel_Elektronik_ve_Robotiğe_Giriş_Sertifika.pdf](https://github.com/user-attachments/files/20956407/Temel_Elektronik_ve_Robotige_Giris_Sertifika.pdf)
