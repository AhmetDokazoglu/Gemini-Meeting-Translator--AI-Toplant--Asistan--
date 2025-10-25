# 🤖 Gemini Meeting Translator  
### Yapay Zekâ Destekli Gerçek Zamanlı Toplantı Çeviri Asistanı

---

## 🎯 Proje Özeti
**Gemini Meeting Translator**, çok dilli toplantılarda dil engelini ortadan kaldırmak amacıyla geliştirilmiş, **yapay zekâ destekli gerçek zamanlı bir çeviri platformudur.**  
Sistem, konuşmaları anlık olarak algılar, hedef dile çevirir ve sesli ya da metin formatında iletir.  
Amaç, herkesin **aynı anda ve aynı anlamda** iletişim kurabildiği küresel bir toplantı ortamı sağlamaktır.

---

## 🧠 Temel Özellikler
- Gerçek zamanlı konuşma tanıma (Speech-to-Text)  
- Anında dil çevirisi (Machine Translation)  
- Sesli çıktı (Text-to-Speech)  
- Çoklu dil desteği (TR, EN, FR, DE vb.)  
- Otomatik dil algılama  
- Kullanıcı dostu ve sezgisel arayüz  
- Mobil ve masaüstü uyumlu tasarım  

---

## 🏗️ Teknolojik Altyapı
| Katman | Kullanılan Teknoloji | Görev |
|--------|----------------------|--------|
| **STT (Speech-to-Text)** | OpenAI Whisper / SpeechRecognition | Sesin metne dönüştürülmesi |
| **MT (Machine Translation)** | GPT API / Google Translate | Metnin hedef dile çevrilmesi |
| **TTS (Text-to-Speech)** | gTTS | Çevirinin seslendirilmesi |
| **GUI / Dashboard** | Streamlit / PyQt | Toplantı arayüzü |
| **Veri Akışı** | WebSocket / Async Queue | Ses ve çeviri senkronizasyonu |

---

## 🧩 Sistem Mimarisi ve İşleyişi
1. Kullanıcı konuşur → mikrofon girişi alınır.  
2. Ses, **Whisper** modeliyle metne dönüştürülür.  
3. Metin, **GPT** veya **Google Translate API** aracılığıyla çevrilir.  
4. Çeviri sonucu ekranda gösterilir ve **gTTS** ile seslendirilir.  
5. Altyazı sistemi (subtitle overlay) ile eş zamanlı görüntü sağlanır.

---

## 💻 Kullanım Senaryoları
- 🌐 **Kurumsal Toplantılar:** Zoom / Teams / Meet entegrasyonu ile anlık çeviri  
- 🎓 **Akademik Konferanslar:** Farklı dillerde verilen sunumların eşzamanlı takibi  
- 💼 **Uluslararası Müşteri Görüşmeleri:** Freelance veya danışmanlık toplantılarında dil bariyerini kaldırma  
- 🤝 **Freelance Platformları (Upwork, Fiverr vb.):** Küresel işbirliği süreçlerinde gerçek zamanlı çeviri desteği  

---

## 🧪 Geliştirme ve Test Süreci
- Ortalama tepki süresi: **1.8 – 2.3 saniye**  
- Dil çiftleri testleri: **Türkçe–İngilizce, İngilizce–Fransızca, Almanca–Türkçe**  
- Farklı mikrofon ve ağ koşullarında kararlı performans  
- Kullanıcı geri bildirimi: *“Doğal ve kolay kullanılabilir.”*

---

## 🔐 Güvenlik ve Gizlilik
- Veriler **kalıcı olarak depolanmaz.**  
- İşlemler **RAM üzerinde geçici olarak yürütülür.**  
- Veri aktarımı **SSL/TLS protokolüyle şifrelenir.**  
- Sistem, **GDPR standartları** ile uyumludur.

---

## 🚀 Gelecekteki Geliştirmeler
- Gerçek zamanlı altyazı (subtitle overlay) sistemi  
- Toplantı özeti oluşturma (Meeting Summarizer)  
- Çoklu kullanıcı senkronizasyonu  
- Mobil uygulama sürümü  
- Genişletilmiş API desteği  

---

## 📜 Sonuç
“**Gemini Meeting Translator**”, yalnızca bir çeviri aracı değil;  
**insanlar arasındaki dil farkını ortadan kaldıran bir yapay zekâ iletişim köprüsüdür.**  
Proje, küresel toplantı deneyimini yeniden tanımlayan yenilikçi bir AI çözümüdür.

---

## 👨‍💻 Hazırlayan
**Yunus Ahmet Dokazoğlu**  
📍 Ankara, Türkiye  
🔗 [GitHub Profilim](https://github.com/AhmetDokazoglu)  
🔗 [LinkedIn Profilim](https://www.linkedin.com/in/ahmet-dokazo%C4%9Flu-9660b2346/)

---

## 📎 Ek Dökümanlar  
📄 [Proje Raporu (Word Versiyonu)](https://github.com/AhmetDokazoglu/Gemini-Meeting-Translator--AI-Toplant--Asistan--/raw/refs/heads/main/Gemini%20Meeting%20Translator%20(AI%20Toplant%C4%B1%20Asistan%C4%B1).docx)
