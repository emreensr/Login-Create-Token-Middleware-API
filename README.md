## SMS API

Laravel kullanarak restful bir api geliştirmeni istiyoruz.
ExampleSMS firması müşterilerine sms gönderim hizmeti sunan bir
firmadır. Bu müşterilerin kendilerine ait kullanıcı adları ve
şifreleri vardır. Müşteriler restful api kullanarak sms gönderimi
yapabilir, sms raporlarını(kayıtlarını) görebilir, sms rapor
detayını görebilir ve bu raporları tarih filtresine göre
filtreleyebilir.


### Projeyi ayağa kaldırmak için 

```
composer install

php artisan key:generate

php artisan serve
```

## Postman collection dosyası projenin içinde database klasörünün altındadır.
