# Windows-TTS
# SpeechToText

Bu proje, OpenAI'nin Whisper API'sini kullanarak ses dosyalarını ve canlı mikrofon kayıtlarını metne çeviren bir Windows Forms uygulamasıdır. Uygulama, kullanıcıların sesli notlarını veya konuşmalarını hızlıca metne dönüştürmelerine olanak tanır. Bu depoda, uygulamanın çalıştırılabilir `.exe` dosyası ve sıkıştırılmış `.rar` dosyası bulunmaktadır.

## Proje Hakkında

Bu uygulama, hem mikrofon üzerinden canlı kayıt yapma hem de mevcut ses dosyalarını metne çevirme yeteneğine sahiptir. 

### Özellikler

- **Canlı Mikrofon Kaydı**: Mikrofonunuzdan gerçek zamanlı kayıt yapabilir ve bu kaydı metne çevirebilirsiniz.
- **Ses Dosyası Desteği**: Yerel diskinizden `.wav`, `.mp3`, `.m4a`, `.ogg`, `.flac` gibi ses dosyalarını yükleyip metne dönüştürebilirsiniz.
- **Kullanıcı Dostu Arayüz**: Windows Forms tabanlı basit ve anlaşılır bir arayüz sunar.
- **Whisper API Entegrasyonu**: Ses işleme için OpenAI'nin Whisper teknolojisinden faydalanır.

## Gereksinimler

Uygulamayı kullanabilmek için aşağıdaki gereksinimlere ihtiyacınız var:

- **İşletim Sistemi**: Windows 
- **OpenAI API Anahtarı**: Whisper API'sini kullanmak için bir OpenAI API anahtarına sahip olmalısınız.
- **Desteklenen Ses Formatları**: `.wav`, `.mp3`, `.m4a`, `.ogg`, `.flac` (Yükleyeceğiniz ses dosyaları bu formatlarda olmalı)

## Kurulum ve Kullanım

Bu depoda kaynak kodlar yerine yalnızca çalıştırılabilir `.exe` dosyası ve `.rar` dosyası bulunmaktadır. Uygulamayı kullanmak için aşağıdaki adımları izleyin:

### 1. Dosyayı İndirin
- GitHub deposundan `.rar` dosyasını indirin.
- `.rar` dosyasını bir klasöre çıkarın. İçinde `ttqs.exe` dosyasını bulacaksınız.

### 2. Uygulamayı Çalıştırın
- `ttqs.exe` dosyasını çift tıklayarak çalıştırın.
- Uygulama açıldığında, sizden bir OpenAI API anahtarı girmeniz istenecektir.

### 3. Kullanım Seçenekleri

#### Canlı Mikrofon Kaydı
1. Uygulamayı açın ve OpenAI API anahtarınızı ilgili alana girin.
2. "Kayıt Başlat" butonuna tıklayın ve mikrofonunuza konuşmaya başlayın.
3. Kaydı bitirmek için "Kayıt Durdur" butonuna basın.
4. Kısa bir süre sonra, konuşmanız metne çevrilmiş olarak ekranda görünecektir.

#### Ses Dosyası Yükleme
1. Uygulamayı açın ve OpenAI API anahtarınızı girin.
2. "Ses Dosyası Aç" butonuna tıklayın.
3. Bilgisayarınızdan bir ses dosyası seçin (desteklenen formatlar: `.wav`, `.mp3`, `.m4a`, `.ogg`, `.flac`).
4. Dosya işlendikten sonra, metne çevrilmiş hali ekranda görünecektir.

## Önemli Notlar
- **API Anahtarı**: Uygulama, OpenAI Whisper API'sine bağlanmak için bir internet bağlantısı ve geçerli bir API anahtarı gerektirir.
- **Hata Durumları**: Eğer bir hata alırsanız, API anahtarınızın doğru olduğundan ve internet bağlantınızın aktif olduğundan emin olun.
- **Ses Dosyası Boyutu**: Büyük ses dosyaları, işleme süresini uzatabilir.

## Ekran Görüntüleri
![STT](https://github.com/user-attachments/assets/d6dfb420-c5a2-442c-b0c9-18488c9bd244)
