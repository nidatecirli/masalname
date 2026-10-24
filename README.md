# MASALNAME — Anadolu'nun Hikâye Atlası

MASALNAME, Türk halk anlatılarını keşfetmek için hazırlanmış tek sayfalı, duyarlı bir web sitesidir.

**Depo:** https://github.com/nidatecirli/masalname  
**Yayın adresi (Pages etkinleştirildikten sonra):** https://nidatecirli.github.io/masalname/

## Özellikler

- 12 Türk masalı, kısa tanıtımları ve okuma pencereleri
- Başlık, açıklama ve masal metni içinde arama
- Masal türüne göre filtreleme
- Okuma penceresinde yazı boyutunu değiştirme ve okuma ilerlemesi göstergesi
- Telefon, tablet ve masaüstü ekranlarına uyumlu tasarım
- Kaynakça ve yapay zekâ kullanımına ilişkin proje notu
- CSS ve JavaScript aynı HTML dosyasının içinde; harici kitaplık veya font kullanılmaz

## Çalıştırma

`index.html` dosyasını indirip tarayıcıda açabilirsin. Site harici font veya JavaScript kitaplığı kullanmaz.

## Kaynaklar

Masal başlıkları ve yazar/derleyen bilgileri, Atatürk Kültür Merkezi Başkanlığı'nın **Türk Masal Külliyatı I** kapsamında sağlanan PDF dosyalarına göre listelenmiştir. Masal metinleri bu proje için yeniden ifade edilmiştir. Sağlanan dosyalarda teyit edilemeyen yayın yılı ve sayfa bilgileri eklenmemiştir.

## Yapay zekâ kullanımı

Tasarım ve kod geliştirme aşamalarında yapay zekâ desteğinden yararlanılmıştır. Proje sahibi metinleri, tasarım kararlarını ve JavaScript işleyişini sunumda açıklayabilmelidir.

## İlk kez GitHub Pages'i etkinleştirme

İlk yayın için depo sahibi bir kez **Settings → Pages → Build and deployment → Source → GitHub Actions** yolunu seçmelidir. Bağlı entegrasyonun yetkileri Pages ayarını kendiliğinden oluşturmaya yetmediği için ilk yayın bu ayardan önce tamamlanamadı. Bu ayar seçildikten sonra `.github/workflows/pages.yml` dosyası `main` dalındaki güncellemeleri otomatik yayımlamak üzere yapılandırılmıştır.
