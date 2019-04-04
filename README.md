# P210-20190404-Task

## Tapşırıq 1.

Aşağıdakı linkdə verilən template-i hazırlayın
- https://templated.co/epilogue

## Tapşırıq 2.
Slider hazırlayın. Next buttonuna click edəndə şəkillər sağdan sola, prev buttonuna click edəndə isə soldan sağa doğru gəlsin.

## Tapşırıq 3.
Aşağıdakı tələblərə uyğun Web Application hazırlayın.

**Qeyd 1:** Dizayn hissə bu repository-yə şəkil kimi əlavə olunacaq, email ünvanlarınıza da göndəriləcək.

Car object-i olsun.

Car
- Properties:
    - id
    - manufacturer
    - model
    - release

Səhifədə 3 ədəd input olmalıdır. Type attributları text olmalıdır. 
Birinci input Car obyektinin manufacturer (istehsalçı), ikinci input model, üçüncü input isə release (buraxılış ili) dəyərlərini daxil etmək üçündür. 
İnputları dolduran zaman aşağıdakı validation-lar yoxlanılmalıdır:
- Heç biri boş qoyula bilməz
- manufacturer inputu yalnız hərflər qəbul etməlidir.
- release inputu yalnız number tipində il qəbul etməlidir. məsələn 2002

İnputlardan sonra bir ədəd "Add" button olmalıdır. Butun inputlar düzgüz doldurulduğu halda button-a click olunanda məlumatlar əsasında yeni bir obyekt yaradılıb Cars array-inə əlavə olunmalıdır və inputların içi təmizlənməlidir. Bütün maşınlar səhifədə siyahı şəklində göstərilməlidir.

Siyahidakı hər bir item-da maşının id-si, istehsalçısı, modeli və ili yazılmalıdır. Məsələn:
```sh
1. Mercedes S600 - 1997
2. Ford Fiesta - 2005
```

Siyahıdakı elementləri silə bilmək üçün hər birində icon olmalıdır. O icona click olunanda həmin elementi siyahıdan və eyni zamanda Cars array-indən silmək lazımdır.

Siyahıdakı elementlərin üzərinə click olunduqda isə həmin məlumatlar yuxarıda inputlara dolmalıdır. İnputlardaki məlumatları dəyişib yenidən buttona click olunduqda həmin object edit olunmalıdır.

