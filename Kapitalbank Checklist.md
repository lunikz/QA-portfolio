# QA Checklist -Kapital Bank 

----
## Qeyd: Bu checklist tədri və portfolio üçün hazırlanmışdır və real mühiti əks etdirmir.

## 1. Authentication Login
- Duzgun usrename ve sifre ile giris edilir
- validation var (istifadeci bos sahelerle daxil olmaga calisanda bu xanani doldur mesaji)
- Yalnis sifre daxil etdikde xeberdarliq mesaji cixir
- müəyyən vaxtdan sonra sistemden cixis etme
- Show/Hide password işləyir
-Şifrə gizli göstərilir
  
## Registration 
- Emailin formasi yoxlanilir
- Bos sahelerde validation var
- Butun sahelerin doldurulmagi teleb olunur
- Sifre telebleri gosterilir
- Sifre ve sifreni tekrar yaz bolmesinin uygunlugu yoxlanilier
- Movcud olan hesab maili ile yeni qeydiyyata icaze vermir
- Qeydiyyatdan sonra login etmek olur

## Forgot Password
- Forgot password linki var
- Reset password gondərilir
- Reset linkin vaxtin bitdikdən sonra istifadə etmək olmur
- Yeni şifrədə Qaydalar tətbiq olunur
- Kohnə şifre ilə giriş etmək mümkün olmur 

## İstifadəci Profili
- Profil məlumatlari düzgün açilir
- Şəxsi məlumatlarda duzəliş etmək olur
- Telefon email/ gmail dəyişikliyi edərkən təsdiq tələb olunur

## Hesablar və kartlar 
- Bütün hesablar düzgün siyahılanıb
- Kartın aktiv və ya blooklu oldugu düzgün göstərilir
- Kartı bloklayıb açmaq işləyir
- Balans düzgün göstəilir

## Pul köçürmələri
- Bank daxili köçürmələr işləyir
- Başqa banklara köçürmələrdə problem olmur
- Köçürmə zamani yalnıış məlumat daxil etdikdə eror mesajı çıxır
- Komisiyalar düzgün çıxılır hesablanır
- Köçürmə  etdikdən sonra balansda düzgün dəyişiklik edilir(duzgun pul cixilir)
  
## Ödənişlər 
- Komunal ödənişlər işləyir
- Telefon operatorları bölməsi işləyir
- Ödənişlər tarixçədə əks olunur
- Uğursuz ödəniş edildikdə xəta mesajı əks olunur

## Təhlükəsizlik 
- HTTPS dən istifadə olunur
- Başqa cihazdan giriş edərkən doğrulama mesajının istənilməsi
- Eyni anda iki cihazdan işlətmək qadağası qoyulub

## Uİ/UX
- Mobil və desktopda sistem düzgün açılır
- Xəta mesajları aydın və başa düşülür
- Dil dəyişərkən sistemdə hər şey düzgün işləyir

## Performance 
- Login zamanı gecikmələr baş vermir
- Köçürmə edərkən donma gecikmə və gözləmə müddəti olmur
- Eyni anda bir neçə köçürmə etmək olmur

