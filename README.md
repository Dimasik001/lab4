<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<p align= "center">Лабораторная работа №4</p><br><br><br><br><br><br><br><br>
<p align= "right">Выполнил: Андреев Д.В.</p><br><br><br><br><br><br><br><br>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p><br><br><br><br><br><br><br><br>
<h2 style="text-align: center">Введение</h2>
<p align="justify">JavaScript ("JS" для краткости) — это полноценный динамический язык программирования, который применяется к HTML документу, и может обеспечить динамическую интерактивность на веб-сайтах. Его разработал Brendan Eich, сооснователь проекта Mozilla, Mozilla Foundation и Mozilla Corporation. JavaScript сам по себе довольно компактный, но очень гибкий. Разработчиками написано большое количество инструментов поверх основного языка JavaScript, которые разблокируют огромное количество дополнительных функций с очень небольшим усилием. JavaScript невероятно универсален и дружелюбен к новичкам. Обладая большим опытом, вы сможете создавать игры, анимированную 2D и 3D графику, полномасштабные приложения с базами данных и многое другое!</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify"> <br>
<h2 align="center">Цели и задачи</h2>
Задачи:
<code>
1.	Рассчитать значение у при заданном значении х
 
2.	Дано натуральное число n (n<=9999). Выяснить, является ли оно палиндромом
("перевертышем") с учетом четырех цифр, как, например, числа 7777, 8338, 0330 и т. п. (Палиндромом называется число, десятичная запись которого читается одинаково слева направо и справа налево.)

3.	Год является високосным, если его номер кратен 4, однако из кратных 100 високосными являются лишь кратные 400, например, 1700, 1800 и 1900 — невисокосные года, 2000 — високосный. Дано натуральное число n. Определить, является ли високосным год с таким номером.
4.	Составить программу для вычисления значения функции y(x): 

 
5.	Составить программу, которая в зависимости от порядкового номера дня месяца (1, 2, ..., 12) выводит на экран время года, к которому относится этот месяц.
6.	Мастям игральных карт условно присвоены следующие порядковые номера: масти "пики" — 1, масти "трефы" — 2, масти "бубны" — 3, масти "червы" — 4, а достоинству карт: "валету" — 11, "даме" — 12, "королю" — 13, "тузу" — 14 (порядковые номера карт остальных достоинств соответствуют их названиям: "шестерка", "девятка" и т. п.). По заданным номеру масти m (1 m 4) и номеру достоинства карты k (6 k 14) определить полное название (масть и достоинство) соответствующей карты в виде "Дама пик", "Шестерка бубен" и т. п.

7.	В некоторых странах Дальнего Востока (Китае, Японии и др.) использовался (и неофициально используется в настоящее время) календарь, отличающийся от применяемого нами. Этот календарь представляет собой 60-летнюю циклическую систему. Каждый 60-летний цикл состоит из пяти 12-летних подциклов. В каждом подцикле года носят названия животных: Крыса, Корова, Тигр, Заяц, Дракон, Змея, Лошадь, Овца, Обезьяна, Петух, Собака и Свинья. Кроме того, в названии года фигурируют цвета животных, которые связаны с пятью элементами природы — Деревом (зеленый), Огнем (красный), Землей (желтый), Металлом (белый) и Водой (черный). В результате каждое животное (и его год) имеет символический цвет, причем цвет этот часто совершенно не совпадает с его "естественной" окраской — Тигр может быть черным, Свинья — красной, а Лошадь — зеленой. Например, 1984 год — год начала очередного цикла — назывался годом Зеленой Крысы. Каждый цвет в цикле (начиная с зеленого) "действует" два года, поэтому через каждые 60 лет имя года (животное и его цвет) повторяется. Составить программу, которая по заданному номеру года нашей эры n печатает его название по описанному календарю в виде: "Крыса, Зеленый". Рассмотреть два случая: а) значение n 1984; б) значение n может быть любым натуральным числом.

8.	Напечатать таблицу умножения на 9.

9.	Напечатать "столбиком" значения sin 2 , sin 3 , ..., sin 20 .
10.	Найти: а) сумму всех целых чисел от 100 до 500; б) сумму всех целых чисел от a до 500 (значение a вводится с клавиатуры; a<=500); в) сумму всех целых чисел от –10 до b (значение b вводится с клавиатуры; b=>–10); г) сумму всех целых чисел от a до b (значения a и b вводятся с клавиатуры; b=>a).

11.	Вычислить сумму
12.	Даны натуральные числа х и у. Вычислить произведение x и y, используя лишь операцию сложения. Задачу решить двумя способами.
13.	Составить программу возведения натурального числа в квадрат, учитывая следующую закономерность
 



14.	Вычислить сумму
 

15.	Дана непустая последовательность целых чисел, оканчивающаяся нулем. Найти: а) сумму всех чисел последовательности; б) количество всех чисел последовательности.

16.	Дана непустая последовательность неотрицательных целых чисел, оканчивающаяся отрицательным числом. Найти среднее арифметическое всех чисел последовательности (без учета отрицательного числа).

17.	Дано натуральное число. Определить: а) количество цифр 3 в нем; б) сколько раз в нем встречается последняя цифра; в) количество четных цифр в нем. Составное условие и более одного неполного условного оператора не использовать; г) сумму его цифр, больших пяти; д) произведение его цифр, больших семи; е) сколько раз в нем встречаются цифры 0 и 5 (всего).


18.	Дано натуральное число, в котором все цифры различны. Определить: а) порядковый номер его максимальной цифры, считая номера: от конца числа; от начала числа; б) порядковый номер его минимальной цифры, считая номера: от конца числа; от начала числа.

19.	Дано натуральное число. Выяснить, является ли оно простым (простым называется натуральное число, большее 1, не имеющее других делителей, кроме единицы и самого себя). Оператор цикла с параметром не использовать.

20.	Дано натуральное число. Установить, является ли последовательность его цифр при просмотре их слева направо упорядоченной по возрастанию. Например, для числа 1478 ответ положительный, для чисел 1782 и 1668 — отрицательный и т. п.

21.	Дана непустая и упорядоченная по возрастанию последовательность целых чисел, оканчивающаяся числом 10 000. Определить порядковый номер первого числа, большего заданного n. Если таких чисел в последовательности нет, то на экран должно быть выведено соответствующее сообщение.

22.	Дано натуральное число. Верно ли, что цифра a встречается в нем реже, чем цифра b?
23.	Имеется фрагмент программы в виде оператора цикла с параметром, обеспечивающий вывод на экран "столбиком" всех целых чисел от 10 до 30. Оформить этот фрагмент в виде: а) оператора цикла с предусловием; б) оператора цикла с постусловием.

----------------------------------------------------
function func1() {
    alert( null || 2 || undefined );1
}

function func2() {
    alert( alert(1) || 2 || alert(3) );
}

function func3() {
    alert( 1 && null && 2 );
}

function func4() {
    alert( alert(1) && alert(2) );
}

function func5() {
    alert( null || 2 && 3 || 4 );
}

function func6() {
let age = 10;
if (age >= 14 && age <= 90) {
    alert( "В диопазоне" );
    } else {
    alert( "не В диопазоне" );    
    }
}


function func7() {
    let age = 30;
    if (!(age >= 14 && age <= 90)) {
    alert("не В диапазоне");
    } else {
    alert(" В диапазоне");
    }
}

function func8() {
    if (null || -1 && 1) alert( 'third' );
    }


function func9() {

let login = prompt("Введите логин", "");
if (login === "Админ") {
let password = prompt("Введите пароль", "");

if (password === "Я главный") {
alert("Здравствуйте!");
} else if (password === null || password === "") {
alert("Отменено");
} else {
alert("Неверный пароль");
}
} else if (login === null || login === "") {
alert("Отменено");
} else {
alert("Я вас не знаю");
}
}


function func10() {
let i = 3;
while (i) {
  alert( i-- );
}
}


function func11() {
    let i = 0;
    while (i++ < 5) alert( i ); //5
   
    }

    function func12() {
for (let i = 0; i < 5; i++) alert( i ); //0-5

for (let i = 0; i < 5; ++i) alert( i ); //0-4
    }
    
    function func13() {
        for (let i = 2; i <= 10; i += 2) {
           alert(i);
            }
       }


function func14() {
let i = 0;
while (i < 3) {
alert(`number ${i}!`);
i++;
}
}

function func15() {
let number;
do {
number = prompt("Введите число, большее 100", "");
} while (number <= 100 && number !== null);
if (number !== null) {
    alert("Вы ввели число больше 100");
} else {
    alert("Операция отменена");
}
}
function func16() {
    //проверка на простое число
function qqq(num) {
    for(let i = 2, sqrt = Math.sqrt(num); i <= sqrt; i++) {
      if(num % i === 0) {
        return false;
      }
    }
    return num > 1;
  }
  
  function sss(n) {
    const primes = [];
    
    for(let i = 2; i <= n; i++) {
      if(qqq(i)) {
        primes.push(i);
      }
    }
    
    return primes;
  }
  const n = 10;
  const result = sss(n);
  alert(result);
}
    
function func17() {
    let browser = 'Edge';
if (browser === 'Edge') {
    alert("You've got the Edge!");
    } else if (browser === 'Chrome' || browser === 'Firefox' || browser === 'Safari' || browser === 'Opera') {
    alert('Okay we support these browsers too');
    } else {
    alert('We hope that this page looks ok!');
    }
}

function func18() {
const number = +prompt('Введите число между 0 и 3', '');

switch (number) {
case 0:
alert('Вы ввели число 0');
break;
case 1:
alert('Вы ввели число 1');
break;
case 2:
case 3:
alert('Вы ввели число 2, а может и 3');
break;
}
}
function func19() {
    let age=20;
function checkAge(age) {
    if (age > 18) {
      return true;
    }//else {
    // ...
    return confirm('Родители разрешили?');
  //}
}
  alert(checkAge(age));
}

function func20() {
    let age=10;
function checkAge1(age) {
return age > 18 ? true : confirm('Родители разрешили?');
    }
function checkAge2(age) {
return age > 18 || confirm('Родители разрешили?');
}
alert(checkAge1(age));
alert(checkAge2(age));
}

function func21() {
function min(a, b) {
    if (a < b) {
    return a;
    } else {
    return b;
    }
    }
    alert(min(2, 5)); // Выведет 2
    alert(min(3, -1)); // Выведет -1
    alert(min(1, 1)); // Выведет 1
}

function func22() {
function pow(x, n) {
    let result = 1;
    for (let i = 0; i < n; i++) {
    result *= x;
    }
    return result;
    }
    const x = prompt("Введите число x:");
    const n = prompt("Введите степень n:");
    const result = pow(x, n);
    alert(`Результат: ${result}`);
}
  
  </code>
    <h2 style="text-align: center">ВЫВОД</h2>
  JavaScript – это язык программирования, который добавляет интерактивность на ваш веб-сайт (например: игры, отклик при нажатии кнопок или при вводе данных в формы, динамические стили, анимация). Эта статья поможет вам начать работать с этим захватывающим языком и даст вам представление о том, на что он способен.

Хотя PHP, главным образом, предназначен для работы в среде веб-серверов, область его применения не ограничивается только этим. Читайте дальше и не пропустите главу Возможности PHP либо, начните непосредственно с Вводного руководства, если вас интересует исключительно веб-программирование.

