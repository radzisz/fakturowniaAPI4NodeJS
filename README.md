# fakturowniaAPI4NodeJS
Nieoficjalna Bibliteka umożliwiająca korzystanie z systemu Fakturownia [www.fakturownia.pl].

## Przykłady użycia

``` node.js

const api = new Fakturownia("http://nazwaTwojejfirmy.fakturownia.pl", "TwojKluczAPI")

const invoiceId = 12345
const invoice = api.invoiceGet(invoiceId)

const invoices1 = api.invoiceList().forThisMonth()
const invoices2 = api.invoiceList().forPeriod(new Date(), new Date())

```

## Wspierane funkcje

### invoice

### payment

### category


# Uwagi

Biblioteka jest na wczesnym etapie, zatem
- a) nie zawiera kompletu fukkcjonalności
- b) może zaweirac błedy
- c) może podlegać istotnym zmianom i nie byc kompatybilna z wcześniejszymi wersjami

