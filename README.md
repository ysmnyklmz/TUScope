# 🧠 TUScope – TUS Çıkmış Soru ve Spot Bilgi Asistanı


<p align="center">
  <img src="https://github.com/zehra19/Yzta_bootcamp136/blob/main/assets/TUScope.png" alt="TUScope Logo" width="250"/>
</p>

<h1 align="center">🧠 TUScope</h1>
<p align="center">TUS Çıkmış Soru ve Spot Bilgi Asistanı</p>




# TUScope 📚💡

TUScope, TUS sınavına hazırlanan tıp öğrencileri için geliştirilmiş yapay zeka destekli bir öğrenme asistanıdır.  
Proje, **Yasemin Yıkılmaz** tarafından Google Yapay Zeka ve Teknoloji Akademisi Mezuniyet Bootcamp’i kapsamında **tek başına** geliştirilmiştir.

---

## 🚀 Özellikler
- **7 Bölümden** oluşan kapsamlı soru sistemi (Anatomi, Biyokimya, Fizyoloji, Farmakoloji, Mikrobiyoloji, Patoloji, Histoloji)
- JSON tabanlı soru verileri
- **Anında doğru/yanlış geri bildirimi** ve puan hesaplama
- GPT destekli **spot bilgiler** ile sınav öncesi hızlı tekrar
- Python ve Streamlit ile geliştirilen kullanıcı dostu arayüz

---


## 🛠️ Yaptıklarım 

### 1️⃣ 7 Bölümlük Quiz Sistemi Kurulumu 
- **Yaptığım İş:**  
  - Anatomi, Biyokimya, Fizyoloji, Farmakoloji, Mikrobiyoloji, Patoloji ve Histoloji olmak üzere **7 bölüm** ekledim.  
  - Her bölüm için **2 soru** olacak şekilde mini quizler tasarladım.  
- **Sonuç:** Kullanıcılar istediği bölümü seçip iki soruluk mini testi çözebiliyor.  


---

### 2️⃣ Spot Bilgiler Ekleme 
- **Yaptığım İş:**  
  - Her dersin başına, soruları çözmeden önce hızlıca gözden geçirilebilecek **spot bilgiler** ekledim.  
  - Örnek:  
    - *Farmakoloji:* “Parasempatolitikler asetilkolin etkisini gösterir.”  


---

### 3️⃣ Doğru/Yanlış Geri Bildirimi ve Skor 
- **Yaptığım İş:**  
  - Kullanıcı bir cevabı seçtiğinde anında **Doğru!** veya **Yanlış!** mesajı gösteriliyor.  
  - Yanlışsa doğru cevabı da gösterdim.  
  - Quiz sonunda **Toplam Doğru Sayısı** ekledim.  


---

### 4️⃣ Streamlit Arayüzü ve Kullanıcı Deneyimi 
- **Yaptığım İş:**  
  - Dropdown menü ile **bölüm seçimi**  
  - Doğru cevapta **yeşil kutu**, yanlış cevapta **kırmızı kutu**  
  - Temiz ve minimal bir tasarım  


---



## 🖥️ Kullanıcı Arayüzü
Aşağıda uygulamanın ekran görüntüleri yer almaktadır:

### Ana Sayfa
![Ana Sayfa]([https://github.com/ysmnyklmz/TUScope/blob/main/TUScope%20img/giri%C5%9F.png])

### Soru Ekranı
![Soru Ekranı]([https://github.com/ysmnyklmz/TUScope/blob/main/TUScope%20img/sorular.png])

### Bölüm Seçim Ekranı
![Bölüm Seçim Ekranı]([https://github.com/ysmnyklmz/TUScope/blob/main/TUScope%20img/7b%C3%B6l%C3%BCm.png])

---

## 🛠️ Teknolojiler
- **Python**  
- **Streamlit** (Frontend)
- **JSON** (Veri Depolama)
- **Pandas, NumPy** (Veri İşleme)
- **GPT** ile üretilmiş spot bilgiler

---

## 📦 Kurulum
1. Bu projeyi klonla:
   ```bash
   git clone https://github.com/kullanici_adi/TUScope.git
   cd TUScope


