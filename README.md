# 💥 Shinyuu SMS Spammer
> 🤖 **Sms/OTP Gönderim Aracınız**

Bu proje, önceden tanımlanmış bir dizi API üzerinden hızlı ve eş zamanlı (concurrent) işlemler yapabilmek için tasarlanmıştır. Proxy desteği ve özelleştirilebilir işçi (worker) sayısı ile yüksek performansı hedefler.

## 🚀 Kurulum

Projeyi yerel makinenizde kurmak ve çalıştırmak için aşağıdaki adımları izleyin.

### 1. Dosyaları Hazırlama

Öncelikle, projenizin ana dosyasını (`index.js` veya hangi adı verdiyseniz) ve `package.json` dosyasını aynı klasörde bulunduğundan emin olun.

### 2. Bağımlılıkları Yükleme

Terminalinizde (Komut İstemi, PowerShell, Terminal vb.) projenizin bulunduğu klasöre gidin ve bağımlılıkları yükleyin.

```bash
# Proje klasörüne git
cd /yol/proje/klasorunuz

# Bağımlılıkları yükle. 
# Bu komut, 'postinstall' scripti sayesinde yükleme biter bitmez aracı otomatik olarak başlatır.
npm install
