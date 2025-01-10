# 🚗 ECE Rent A Car Yönetim Sistemi

## 📝 Proje Hakkında
ECE Rent A Car, araç kiralama işlemlerini kolaylaştıran ve yöneten bir C++ konsol uygulamasıdır. Bu sistem, müşterilerin araç kiralamasını ve yetkililerin müşteri bilgilerini yönetmesini sağlar.

## ✨ Özellikler

### 👥 Müşteri İşlemleri
- 🔍 Mevcut araçları görüntüleme
- 💰 Fiyata göre artan/azalan sıralama
- 🏢 Şehir bazlı araç kiralama
- 📋 Kişisel bilgilerle rezervasyon yapma

### 👨‍💼 Yetkili İşlemleri
- 📊 Müşteri listesini görüntüleme
- 📈 Günlük ziyaretçi sayısını takip etme
- 🔍 TC kimlik numarası ile müşteri arama
- 🔐 Şifre korumalı yetkili girişi

## 🚀 Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/[kullanıcı-adı]/Rent-A-Car-Little-Work.git
```

2. Proje dizinine gidin:
```bash
cd Rent-A-Car-Little-Work
```

3. Programı derleyin:
```bash
g++ "RaC Proje.cpp" -o rentacar
```

4. Programı çalıştırın:
```bash
./rentacar
```

## 💻 Sistem Gereksinimleri
- C++ derleyici (GCC/G++ veya benzeri)
- Windows veya macOS işletim sistemi

## 🗃️ Dosya Yapısı
- `RaC Proje.cpp`: Ana program dosyası
- `Araba Data.txt`: Araç bilgilerinin tutulduğu dosya
- `Musteri Data.txt`: Müşteri kayıtlarının tutulduğu dosya
- `Musteri Sayac.txt`: Günlük ziyaretçi sayısının tutulduğu dosya
- `Kucukten Buyuge.txt`: Fiyat sıralaması için geçici dosya
- `Buyukten Kucuge.txt`: Fiyat sıralaması için geçici dosya

## 🔑 Yetkili Girişi
Varsayılan yetkili şifresi: `112233`

## 🤝 Katkıda Bulunma
1. Bu depoyu fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/yeniOzellik`)
5. Bir Pull Request oluşturun

## 📄 Lisans
Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

## 👥 İletişim
Proje ile ilgili sorularınız için [issues](https://github.com/[kullanıcı-adı]/Rent-A-Car-Little-Work/issues) sayfasını kullanabilirsiniz. 