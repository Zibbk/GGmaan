## Raven Albüm İnceleme
Kullanıcıların veritabanına albüm veya single eklemesine ve bunları değerlendirmesine olanak sağlayan bir sistem.

0.5 (minimum) ile 5 (maksimum) puan arası bir değerlendirmede ve buna ek olarak istek dahilinde yorum veya incelemelerde de bulunulabilir.

## Veritabanı Yapısı
#artist
id
name
<b>sort_name</b>
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


## Veritabanı Yapısı
#artist
artist_id
artist_name
artist_sort_name
artist_type
artist_gender
area
comment

#recording
#recording_id
artist_credit
recording_name
recording_length
comment

#release_group
release_group_id
name
artist_credit
release_group_type
comment

#url
url_id
url

#label
label_id
label_name
label_sort_name
label_type
label_code
area
comment

#work
work_id
work_type
work_name
work_language
comment

#release
release_id
release_group
artist_credit
release_name
release_barcode
release_language
comment

#area
area_id
area_name
area_sort_name
area_type
comment
