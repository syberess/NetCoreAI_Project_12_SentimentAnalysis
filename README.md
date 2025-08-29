# 🧠 NetCoreAI Project 12 - Sentiment Analysis (OpenAI)

Bu proje, **.NET Console Application** kullanarak **OpenAI Chat Completions API** üzerinden duygu analizi (sentiment analysis) yapmaktadır.  
Kullanıcıdan alınan metin pozitif, negatif veya nötr olarak sınıflandırılır ve konsola yazdırılır.  

---

## 🛠️ Kullanılan Teknolojiler
- .NET 8 / 9 Console Application  
- OpenAI API (Chat Completions - `gpt-3.5-turbo`)  
- HttpClient (API isteği için)  
- Newtonsoft.Json (JSON serialize/deserialize)  

---

## 📂 Proje Yapısı
- `Program.cs` → Konsoldan metin alır, OpenAI API’ye gönderir ve duygu analizini konsola yazdırır.  
- `.csproj` → Proje yapılandırma dosyası  

---

## ⚙️ Kurulum ve Çalıştırma
1. Repo’yu klonla:
   git clone https://github.com/kullaniciadiniz/NetCoreAI_Project_12_SentimentAnalysis.git
   cd NetCoreAI_Project_12_SentimentAnalysis
Program.cs içinde kendi OpenAI API anahtarını ekle:
private static readonly string apiKey = "YOUR_API_KEY";

Konsol uygulamasını çalıştır:
dotnet run
Konsolda örnek kullanım:
Lütfen metni giriniz:
> Bugün çok güzel bir gün!

Duygu Analizi Yapılıyor...
Sonuç: Positive

✨ Özellikler
✔️ Konsoldan metin alır

✔️ OpenAI Chat API ile duygu analizi yapar

✔️ Sadece Positive, Negative veya Neutral döndürür

✔️ Hata durumlarında JSON cevabı gösterir﻿
