## Raven Albüm İnceleme
Kullanıcıların veritabanına albüm veya single eklemesine ve bunları değerlendirmesine olanak sağlayan bir sistem.

0.5 (minimum) ile 5 (maksimum) puan arası bir değerlendirmede ve buna ek olarak istek dahilinde yorum veya incelemelerde de bulunulabilir.

## Veritabanı Yapısı
#artist
id
name
sort_name
type
gender
area
comment

#recording
id
artist_credit
name
length
comment

#release_group
id
name
artist_credit
type
comment

#url
id
url

#label
id
name
sort_name
type
label_code
area
comment

#work
id
type
name
language
comment

#release
id
release_group
artist_credit
name
barcode
language
comment

#area
id
name
sort_name
type
comment

#place
id
name
type
address
area
comment
