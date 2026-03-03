# TEST SUMMARY REPORT
## Kapital Bank – Veb Sayt (Practice Project)

---

## 1. Layihə Məlumatları

**Layihənin adı:** Kapital Bank Website Testing (Practice)  
**Versiya:** 1.0  
**Test edilən modullar:**
- Login səhifəsi
- Kredit kalkulyatoru
- Axtarış (Search) funksiyası  

**Test növü:** Manual Testing  

---

## 2. Testin Məqsədi və Əhatə

### Məqsəd:
Sistemin əsas funksionallığını, input validasiyasını və istifadəçi interfeysini yoxlamaq.

### Əhatə dairəsi:
- Funksional test
- Mənfi test ssenariləri
- UI yoxlamaları
- Input sahələrinin validasiyası

### İstisnalar:
- Backend API testləri
- Performance testing
- Security testing (ətraflı)

---

## 3. Test Statistikası

| Ümumi Test Case | İcra olunan | Passed | Failed | Skipped |
|----|--|--|--|--|
| 13 | 13 | 10 | 3 | 0 |

### Qısa izah:
Test case-lərin böyük əksəriyyəti uğurla keçmişdir. 3 test case zamanı uyğunsuzluq aşkar edilmişdir.

---

## 4. Defekt Statistikası

| Kritiklik | Say |
|--|--|
| High | 1 |
| Medium | 1 |
| Low | 1 |

### Tapılan problemlər:

1. **High:** Kredit kalkulyatorunda limitdən artıq məbləğ daxil edilərkən düzgün xəbərdarlıq mesajı göstərilmir.  
2. **Medium:** Login səhifəsində boş input zamanı validasiya gecikməsi müşahidə olunur.  
3. **Low:** Axtarış funksiyasında xüsusi simvollar daxil edilərkən mesaj qeyri-dəqiq göstərilir.  

---

## 5. Ümumi Qiymətləndirmə

Test nəticələrinə əsasən sistemin əsas funksionallığı stabil işləyir.  
Aşkarlanan problemlər kritik sistem dayanmalarına səbəb olmur, lakin istifadəçi təcrübəsinə təsir edə bilər.

Ümumilikdə məhsul istifadəyə yararlı hesab olunur, lakin qeyd edilən defektlərin aradan qaldırılması tövsiyə olunur.

---

## 6. Tövsiyələr

- Kredit kalkulyatorunda input limitlərinə nəzarət gücləndirilməlidir.
- Login səhifəsində real-time validasiya mexanizmi təkmilləşdirilməlidir.
- Axtarış sistemində xüsusi simvollar üçün daha aydın mesaj təqdim olunmalıdır.
- Düzəlişlərdən sonra regresiya testi aparılmalıdır.

---

## 7. Əlavələr

- Test Plan sənədi
- Test Scenarios

