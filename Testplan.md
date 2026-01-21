# Qeyd: Bu sənəd tədris məqsədilə hazırlanmış nümunə test planıdır.
# Test Plan – Kapital Bank 

## 1. Introduction

Bu Test plan sənədi Kapital Bank-ın internet və mobil bankçılıq sistemləri üçün hazırlanmışdır.
Sənəd test prosesinin necə aparılacağını və hansı funksiyaların yoxlanacağını göstərir


## 2. Test Objectives

* Əsas bank funksiyalarının düzgün işləməsini yoxlamaq
* İstifadəçi məlumatlarının təhlükəsizliyini təmin etmək
* Kritik funksiyalarda səhvlərin qarşısını almaq
* Sistem stabil işləyirmi onu təsdiqləmək


## 3. Test Scope

### 3.1 İn Scope

* User registration və login funksiyalarının yoxlanması
* Balansın göstərilməsi
* Kartdan karta köçürmə prosesinin yoxlanması
* Kommunal və mobil ödənişlərin yoxlanması
* Hesabatların  görüntülənməsi
* Profil məlumatlarının təzələmək
* Logout funksiyasının yoxlanması

### 3.2 Out Of Scope 

* Core banking sistemləri
* Bankın daxili server quruluşu
* Real pul əməliyyatları 


## 4. Test Types

* Functional Testing
* Regression Testing
* Smoke Testing
* UI Testing
* Basic Security Testing
* API Testing (Postman ilə)


## 5. Test Approach

* Testlər əsasən manual testing ilə aparılacaq
* API testləri Postman aləti ilə həll ediləcək
* Kritik funksiyalar prioritetlə test ediləcək
* Tapılan buglar dərhal TC kimi yazılacaq


## 6. Test Environment

* Web browser: Chrome, Firefox
* Mobile: Android və iOS
* Test environment: QA / Staging
* Test data: Dummy (test) istifadəçi məlumatları

## 7. Test Schedule

 Phase | Description | Duration 
-|-|-
 Test Planning | Test plan və test strategiyanın hazırlanması |  3 days 
 Test Case Design | Test scenario və test case-lərin yazılması | 3 days 
 Environment Setup | Test mühitinin hazırlanması və yoxlanması | 3 day 
 Test Execution | Manual və API testlərin icrası | 5 days 
 Bug Reporting | Tapılan bugların qeydiyyatı və izlənməsi | Continuous
 Regression Testing | Bug fixlərdən sonra yenidən test | 3 ays 
 Test Closure | Test hesabatının hazırlanması | 2 day 


## 8. Test Documents

* Test Plan
* Test Scenarios
* Test Cases
* Bug Reports
* Test Execution Report

## 9. Risks and Mitigation

Risk | Impact | Mitigation 
-|-|-
Login problemi | High | Erkən test 
Transfer xətası | Very High | Regression test 
OTP gecikməsi | Medium | Əlavə test 
UI xətaları | Low | Cross-browser test 



## 10. Entry Criteria

* Test mühiti hazırdır
* Tələblər (requirements) təqdim olunub
* Test data mövcuddur
* Sistem test üçün stabildir


## 11. Exit Criteria

Testlər aşağıdakı hallarda tamamlanmış sayılır:

* Kritik və yüksək prioritet buglar bağlanıb
* Test case-lərin ən azı 95%-i icra olunub
* Test nəticələri sənədləşdirilib



## 12. Roles and Responsibilities

* QA Engineer – Testlərin icrası və bug report
* Developer – Bugların düzəldilməsi
* Product Owner – Tələblərin təsdiqi

