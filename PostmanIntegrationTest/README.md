# Çiçeksepeti Integration Test 

```
Çiçeksepeti'nde comment işleminde kullanılan API  için;

* https://www.getpostman.com/collections/c0a484250e8d7efbafa0  POSTMAN collection'ında bulunan API için cityName parametresine göre dönen response'da,

* cityName değerlerinin kontrolü için entegrasyon testi yazılması,

Params

Key          Value
cityName     ankara         => Ankara ili için yapılan yorumlar listesi
cityName     istanbul       => İstanbul ili için yapılan yorumlar listesi
cityName     van            => status is 404
cityName     null           => status is 400
```

------



![hatay](https://github.com/ciceksepetibootcamp/Ramazan_TUYLUOGLU_Homework/blob/main/PostmanIntegrationTest/hatay.PNG)





![eekran](https://github.com/ciceksepetibootcamp/Ramazan_TUYLUOGLU_Homework/blob/main/PostmanIntegrationTest/eekran.PNG)



Ankara ili için dönen response'da Hatay ili olduğu için test hata veriyor.
