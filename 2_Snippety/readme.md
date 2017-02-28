# jQuery - Snippety
> Krótkie kawałki kodu, które pokazują zależności, rozwiązują popularne problemy oraz pokazują jak używać niektórych funkcji.

#### 1. Animacje

Prosta animacja, w której powiększymy kwadrat o 50px (wysokość i szerokość) i zmienimy mu opacity na 1.0 w czasie 3 sekund.

HTML:
```
<div class="animate-me"></div>
```

CSS:
```
.animate-me {
    width: 100px;
    height: 100px;
    background-color: black;
    opacity: 0.5;
}
```

JavaScript:
```
$(".animate-me").animate({
  width: "+=50",
  height: "+=50",
  opacity: 1
}, 3000);
```

#### 2. Ajax

Łączenie się z serwerem, pobranie danych i wypisanie ich w konsoli:

```
$.ajax({
  url: "XXXX",
  method: "GET",
  dataType: "json"
})
  .done(function(response) {
    console.log(response);
  });
```
Gdzie XXXX to adres serwera.
