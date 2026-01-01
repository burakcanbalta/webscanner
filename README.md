# 🛡️ Ultimate Web Pentest – Advanced Web Vulnerability Scanner

Ultimate Web Pentest, modern web uygulamalarında yaygın olarak karşılaşılan zafiyetleri tespit etmek için geliştirilmiş güçlü ve modüler bir güvenlik tarayıcısıdır. Aracın payload tabanlı motoru sayesinde SQLi, XSS, LFI, BAC gibi açıklar kolayca test edilebilir.

---

## 🚀 Özellikler

- 🔍 SQL Injection (Classic / Error-Based / Blind)
- ⚠️ XSS (Reflected & Stored)
- 🔐 Broken Access Control (BAC)
- 📂 Local File Inclusion (LFI)
- 🧪 Modüler Payload Sistemi (payloads klasörü üzerinden)
- 📄 Terminal çıktısı ve JSON/HTML rapor desteği (isteğe bağlı)
- 🌐 Otomatik form ve parametre analizi

---

## ⚙️ Gereksinimler

```bash
pip install -r requirements.txt
```

---

## 🛠️ Kurulum

1. Bu projeyi klonla veya ZIP olarak indir:
```bash
git clone https://github.com/burakcanbalta/ultimate-web-pentest.git
cd ultimate-web-pentest
```

2. Gerekli modülleri yükle:
```bash
pip install -r requirements.txt
```

---

## ▶️ Kullanım

Temel kullanım:
```bash
python webpentest.py --url https://example.com --scan all
```

### Parametreler:
| Parametre       | Açıklama                        |
|------------------|----------------------------------|
| `--url`          | Hedef web sitesi URL’si          |
| `--scan`         | Taramak istediğiniz açık türü: `sqli`, `xss`, `lfi`, `bac`, `all` |

### Örnek:
```bash
python webpentest.py --url https://hedefsite.com --scan xss
```

---

## 📁 Proje Yapısı

```
ultimate_webpentest/
├── webpentest.py             # Ana tarama scripti
├── payloads/                 # SQLi, XSS vb. için payload listeleri
├── requirements.txt          # Python bağımlılıkları
├── LICENSE                   # MIT lisansı
└── README.md                 # Bu dökümantasyon
```

---

## 📜 Lisans

MIT Lisansı © 2025 Burak BALTA – Herkese açık, özgürce kullanılabilir.
