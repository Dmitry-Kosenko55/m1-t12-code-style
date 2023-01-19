# Новое оформление файла README для репозитория **Code style. Правила красивого кода**
[Яндекс](https://www.yandex.ru "Я Yandex!")

_Часть кода для примера:_
``` public class DepositCalculator {
double calculateComplexPercent(double amount, double yearRate, int depositPeriod) {
    double pay = amount * Math.pow((1 + yearRate / 12), 12 * depositPeriod);
        return round(pay, 2);
    }
```