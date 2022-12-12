# Ödev 1:

Node.JS Komut Satırı Kullanımı
Hepimizin Matematik derslerinden bildiği üzere Dairenin Alanı = π x r2 şeklinde hesaplanır. Node.JS Javascript çalışma ortamında yarıçap değerini konsoldan parametre olarak girerek alanı bulmaya çalışacağız. Konsol çıktısı: Yarıçapı (Yarıçap) olan dairenin alanı: (Alan) şeklinde olmalıdır.
Kolay gelsin.

## Cevap:

```javascript
const r = process.argv.slice(2) *1
const alan = Math.PI * r^2
console.log(`Yarıçapı ${r} olan dairenin alanı: ${alan}`)
```
