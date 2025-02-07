# Java Script

*[JavaScript]() - C подобный язык имеет те же возможности что и [C++](). Возможности были улучшены и добавлено новое.В этом описании будет немного о следующем:*

- **Условия**
- **Циклы**
- **Функции**

![](https://miro.medium.com/v2/resize:fit:1400/0*7D_7gvw57R0mMiNA.png)

## Условия

Условия **[(Condition)]()** - блок кода который работают через условия который задаёт разработчик. Если условие которое было задано принимает значение истино **[(true)]()** выполняется первая часть кода, если же было принято ложное значение **[(false)]()**.

Пример:

```javascript

    if (x > 0) {
       return "Positive";
    }
    else if (x < 0) {
        return "Negative";
    }
    else {
        return "Zero";
    }

```

В **[JavaScript]()** был добавлен **[тернаный оператор]()** для таких условий. Возможность сократить код. Теперь для того что бы создавать блок кода с механизмом условий достаточно всего лишь одной строки. 

---

![](https://miro.medium.com/v2/resize:fit:1400/1*TQqjZzzqDcdBCn5-UWUNCA.png)

## Циклы

Цикл **[(Loop)]()** - это механизм который позволяет повторяет определённый блок кода до тех пор пока выполняется условие цикла, после присвоения значения **[(false)]()** цикл остонавливается.

Пример:

```JavaScript

function generateMultiplicationTable(x) {

    for (let i = 1; i <= 10; i++) {
        console.log(x, "*" , i, "=" , x*i);
        
    }
}

generateMultiplicationTable(5);

```

---

![](https://miro.medium.com/v2/resize:fit:1400/1*JxmefVHO1fWZyfFsGxH2rg.png)

## Функции

Функция **[(Function)]()** - блок кода который выполняет заданную функцию каждый раз когда он будет вызван. В **[(JavaScript)]()** функция определяется через ключевое слово ``` Function ```. Функция является одим из основных инструменов **[(JavaScript)]()** Front-End разработчиков.

Пример: 

```JavaScript
function generateMultiplicationTable(x) {

    for (let i = 1; i <= 10; i++) {
        console.log(x, "*" , i, "=" , x*i);
        
    }
}

generateMultiplicationTable(5);

```

---

```JavaScript

function endNine(x) {
    if (x%10==9) {
        return "True"
    }
    else return "False"
}

```

---

```JavaScript

function year(x){
    if(x % 100 == 0){
        return (x / 100);
        
    }
    else if(x % 100 != 0){
        return (~~(x / 100)) + 1;
    }
  }
  console.log(year(1705));
  console.log(year(1900));
  console.log(year(2000));

```
