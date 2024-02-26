# ADS-1 Библиотека для работы с простыми числами


![GitHub pull requests](https://img.shields.io/github/issues-pr/NNTU-CS/ADS-1)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/NNTU-CS/ADS-1)

Срок выполнения задания:

**по 03.03.23** ![Relative date](https://img.shields.io/date/1709499599) 


## Задание 1

> Написать прототип библиотеки для работы с простыми (prime) числами.

**Состав проекта**

```C++
   - bool checkPrime(uint64_t value) - проверка числа на простоту.
   - uint64_t nPrime(uint64_t n) - нахождение n-ого простого числа (в ряду).
   - uint64_t nextPrime(uint64_t value) - нахождение ближайшего следующего простого числа к value.
   - uint64_t sumPrime(uint64_t hbound) - сумма всех чисел до hbound (не включая его)
 ```



## Пояснение

Требуется написать несколько функций на языках С/С++, выполняющих поставленные задачи.

Функции должны иметь заданную сигнатуру и располагаться в файле **alg.cpp**:


```C++
bool checkPrime(uint64_t value) {

}
```

- **value** - проверяемое значение

Функция возвращает **true**, если число **value** простое и **false** в противном случае.


```C++
uint64_t nPrime(uint64_t n) {

}
```

- **n** - n-ое число в ряду. Например, 2 - первое простое число, 3 - второе, 5 - третье... 

Функция возвращает найденное простое число.

```C++
uint64_t nextPrime(uint64_t value) {

}
```

- **value** - исходное число, начиная с которого мы ищем ближайшее простое. Само **value** при поиске не учитывается. Например, для числа 4 следующим простым будет 5, а для 11 следующим простым будет 13.

Функция возвращает найденное простое число.

```C++
uint64_t sumPrime(uint64_t hbound) {
   
}
```

Функция находит сумму простых чисел до **hbound** (сама граница в сумму не включается)

Функция возвращает сумму простых чисел.

Функции должны располагаться в файле **src/alg.cpp**.

