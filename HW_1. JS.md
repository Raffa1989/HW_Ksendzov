ОБЯЗАТЕЛЬНО ДЕЛАТЬ СОХРАНЕНИЯ (CTRL + S) ПЕРЕД КАЖДЫМ console.log()!!!!

1.1 Создать переменную “item_1”. Присвоить переменной item_1 цифру 5
```js
let item_1 = 5
```
1.2 Вывести в консоль item_1
```js
console.log(item_1)
```
Result:
```txt
5
```
2.1 Создать переменную “item_2”. Присвоить переменной item_2 цифру 3
```js
let item_2 = 3
```
2.2 Вывести в консоль item_2
```js
console.log(item_2)
```
Result:
```txt
3
```
3.1 Создать переменную “item_3”. Присвоить переменной item_3 сложение item_1 и item_2
```js
let item_3 = item_1 + item_2
```
3.2 Вывести в консоль item_3
```js
console.log(item_3)
```
Result:
```txt
8
```
4.1 Создать переменную “item_4”. Присвоить переменной item_4 строку “Yolochka”
```js
let item_4 = "Yolochka"
```
4.2 Вывести в консоль item_4
```js
console.log(item_4)
```
Result:
```txt
Yolochka
```
5. Вывести в консоль сложение item_3 и item_4
```js
console.log(item_3 + item_4)
```
Result:
```txt
8Yolochka
```
6. Вывести в консоль умножение item_3 и item_4
```js
console.log(item_3 * item_4)
```
Result:
```txt
NaN
```
7.1 Создать переменную “item_5”. Присвоить переменной item_5 переменную item_3
```js
let item_5 = item_3
```
7.2 Создать переменную item_6. Создать переменную item_6_type. Присвоить переменной item_6 значение 15. 
Присвоить переменной item_6_type тип переменной item_6
```js
let item_6 = 15
let item_6_type = typeof(item_6)
```
7.3 Вывести в консоль тип данных item_6 в виде ——  “item_6 == ”  item_6,  “item_6_type == ”  item_6_type ——  
```js
console.log("item_6 ==", typeof(item_6), "item_6_type", typeof(item_6_type))
```
Result:
```txt
item_6 == number item_6_type string
```
8.1 Создать переменную item_7 и в ней преобразовать item_6 в String
```js
let item_7 = String(item_6)
```
8.2 Создать переменную item_7_type. Присвоить переменной item_7_type тип переменной item_7
```js
let item_7_type = typeof(item_7)
```
8.3 Вывести в консоль тип данных item_7 в виде ——  “item_7 == ”  item_7,  “item_7_type == ”  item_7_type ——  
```js
console.log("item_7 ==", typeof(item_7), "item_7_type", typeof(item_7_type))
```
Result:
```txt
item_7 == string item_7_type string
```
9.1 Создать переменную “age_1” и присвоить ей значение 10
```js
let age_1 = 10
```
9.2 Создать переменную “age_2” и присвоить ей значение 18
```js
let age_2 = 18
```
9.3 Создать переменную “age_3” и присвоить ей значение 60
```js
let age_3 = 60
```
9.4 Создать if в котором будите проверять значение переменной age_1

  1. Если age_1 < age_2, вывести в консоль “You don’t have access cause your age is ” + age_1 + “ It’s less then ”
  2. Если age_1 >=  age_2 и age_1 <  age_3, вывести в консоль “Welcome  !”
  3. Если age_1  > age_3, вывести в консоль “Keep calm and look Culture channel”
  4. Иначе выводите “Technical work”

```js
if (age_1 < age_2){
    console.log("You don't have access cause your age is", age_1, "It's less then", age_2)
} else if (age_1 >= age_2 && age_1 < age_3) {
    console.log("Welcome !")
} else if (age_1 > age_3) {
    console.log("Keep calm and look Culture channel")
} else {
    console.log("Technical work")
}
```
Result:
```txt
You don't have access cause your age is 10 It's less then 18
```
