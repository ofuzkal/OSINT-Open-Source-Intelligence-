# Robots.txt Nedir?

Web sitelerinin arama motorlarına hangi alanlara erişilebileceğini veya erişilemeyeceğini belirten bir dosyadır. Bu dosya, web tarayıcıları tarafından otomatik olarak okunur ve sitenin hangi sayfalarının dizine eklenip eklenmeyeceğini belirler.

## Örnek Bir Robots.txt Dosyası:

User-agent: * Disallow: /gizli-dizin/ Sitemap: https://domain/sitemap .xml


# Steghide Nedir?

Steghide, dosyaların içine başka dosyaları gizleyerek veri saklama amacıyla kullanılan bir steganografi aracıdır. Verileri görüntü veya ses dosyalarına gizlemek için kullanılır. Ayrıca, şifreleme desteğiyle gizlenen verilerin sadece belirli kişiler tarafından okunabilmesini sağlar.

## Steghide ile Veri Çıkarma

Steghide ile veri çıkarmak için şu adımlar takip edilebilir:

1. Steghide ile veri çıkarma komutu kullanılır.
2. Gerekli şifre veya anahtarlar girilir.
3. Çıkartılan veri kaydedilir.

### Steghide Komut Örnekleri:

- Veriyi bir dosyaya gömmek için:
steghide embed -cf filename.jpg -ef filename.txt


- Veriyi bir dosyadan çıkarmak için:
steghide extract -sf filename.jpg


# Exiftool Nedir?

Exiftool, medya dosyalarının meta verilerini okumak ve düzenlemek için kullanılan bir yazılımdır. Fotoğrafların çekildiği tarih, kamera modeli gibi bilgileri düzenlemek için kullanılır.

## Exiftool Komut Örnekleri:

- EXIF verilerini görüntülemek için:
exiftool image.jpg


- EXIF verilerini düzenlemek için:
exiftool -DateTimeOriginal='2022:01:01 12:00:00' image.jpg


Bu komut, `image.jpg` dosyasının yaratılış tarihini 1 Ocak 2022, saat 12:00 olarak değiştirir.
