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
    let result=document.getElementById('q')
    let x = prompt("Введите х","2");
    let itog;
    if (x>0)
    {
        itog = Math.pow(Math.sin(x),2);
    }
    else {
        itog = 1-2*Math.pow(Math.sin(x),2);
    }
     result.textContent=itog;
}



function func2() {
    let result=document.getElementById('qq')
    var n = prompt("Введите n")
    let str = n.toString();
    let reversStr=str.split('').reverse().join('');
    if(str===reversStr){
        result.textContent= "Полиндром";
    }
    else{
        result.textContent= "не Полиндром";
    }
}

function func3() {
    let result=document.getElementById('qqq')
    let year = prompt("Введите год ", "2002")
    if ((year % 4 === 0 && year % 100 !== 0) || year % 400 === 0) {
       result.textContent=year + "високосный год.";
    } else {
        result.textContent=year = year + "не високосный год.";
    }
}

function func4() {
    let resultt=document.getElementById('qqqq')
    let x = prompt("Введите значение x: ", "2")
    let itog;
    if (x < -1)
    {
   itog = -1;
    }
    else
    {
     if(x>-1)
        {
     itog = x;
        }
        else
        {
            if (x==-1)
            {
                itog = 1;
            }
        }      
    }
    resultt.textContent=itog;
}

function func5() {
    let resultt=document.getElementById('qqqqq')
    let month = prompt("Введите месяц: ", "5")
    let vremgoda;
    if (month >= 1 && month <= 2 || month === 12) {
      vremgoda = "Зима";
    } else if (month >= 3 && month <= 5) {
      vremgoda = "Весна";
    } else if (month >= 6 && month <= 8) {
      vremgoda = "Лето";
    } else if (month >= 9 && month <= 11) {
      vremgoda = "Осень";
    } else {
      vremgoda = "Некорректный номер месяца";
    }    
    resultt.textContent="Этот месяц относится к времени года:" + vremgoda;
}

function func6() {
let resultt=document.getElementById('s')
let m = parseInt(prompt("Введите m: ", "5"))
let k = parseInt(prompt("Введите k: ", "7"))
let masti;
let rang;

switch (m) {
  case 1:
    masti = "пики";
    break;
  case 2:
    masti = "трефы";
    break;
  case 3:
    masti = "бубны";
    break;
  case 4:
    masti = "червы";
    break;
  default:
    masti = "неизвестная масть";
}
switch (k) {
  case 6:
    rang = "шестерка";
    break;
  case 7:
    rang = "семерка";
    break;
  case 8:
    rang = "восьмерка";
    break;
  case 9:
    rang = "девятка";
    break;
  case 10:
    rang = "десятка";
    break;
  case 11:
    rang = "валет";
    break;
  case 12:
    rang = "дама";
    break;
  case 13:
    rang = "король";
    break;
  case 14:
    rang = "туз";
    break;
  default:
    rang = "неизвестное";
}
resultt.textContent=rang + " " + masti;
}


function func7() {
    let resultt=document.getElementById('ss')
    let n = prompt("Введите значение n: ", "1984")
    const hivotnie = ["Крыса", "Корова", "Тигр", "Заяц", 
    "Дракон", "Змея", "Лошадь", "Овца", "Обезьяна", "Петух", "Собака", "Свинья"];
    const cvet = ["Зеленый", "Красный", "Желтый", "Белый", "Черный"];
    const nahGod = 1984; // Год с которого начинается цикл
    const animalIndex = (n - nahGod) % 12;
    const colorIndex = Math.floor((n - nahGod) / 2) % 5;
    const animalName = hivotnie[animalIndex];
    const colorName = cvet[colorIndex];
    resultt.textContent=animalName + " " + colorName;
}

function func8() {
    let result =  ""
    for (let i = 1; i <= 10; i++) {
        const x = 9 * i;
        result += `9 x ${i} = ${x}` + "\n";
    }
    alert(result);
}


function func9() {
    let resultt=document.getElementById('sss')
    let itog = '';
    for(let i = 2; i <= 20; i++) {
    itog += Math.sin(i) + '\n';
    }
    alert(itog);
}


function func10() {
    let result = "";
    let a = parseInt(prompt("Введите число а: ", " "));
    let b = parseInt(prompt("Введите число b: ", " "));
    let sum = 0;
    for (let i = 100; i <= 500; i++) {
      sum += i;
    }
    result += "а)" + sum + "\n";
    sum = 0
    for (let i = a; i <= 500; i++) {
        sum += i;
    }
    result += "б)" + sum + "\n";
    sum = 0
    for (let i = -10; i <= b; i++) {
        sum += i;
    }
    result += "в)" + sum + "\n";
    sum = 0
    for (let i = a; i <= b; i++) {
        sum += i;
    }
    result += "г)" + sum + "\n";    
    alert(result);
}


function func11() {
    let resultt=document.getElementById('ssss')
    let n = parseInt(prompt("Введите число n"));
    let sum = 0;
    for (let i = 1; i <= n; i++) {
      sum += 1 / i;
    }
    resultt.textContent = sum;
  }   


    function func12() {
      let resultt=document.getElementById('e')
      let x = prompt("Введите натуральное число x");
      let y = prompt("Введите натуральное число y");
      let product = 0;
      for (let i = 1; i <= y; i++) {
        product += parseInt(x);
      }
      resultt.textContent =  product;
    }
    
    function func13() {
      let resultt=document.getElementById('ee')
      let number = prompt("Введите натуральное число:");
      let sum = 0;
      
      for (let i = 1; i <= number; i++) {
      sum += 2*i - 1;
      }
      resultt.textContent = sum;
       }


function func14() {
let i = 0;
while (i < 3) {
alert(`number ${i}!`);
i++;
}
}

function func15() {
  let resultt=document.getElementById('eee')
  let sum = 0;
  let count = 0;
  
  while (true) {
    let num = parseInt(prompt("Введите числа"));
  
    if (num === 0) {
      break; 
    }
    sum += num;
    count++;
  }
  resultt.textContent = "Сумма"+sum+"Кол-во"+count;
}

function func16() {
  let resultt=document.getElementById('eeee')
  let sum = 0;
  let count = 0;
  while (true) {
    let number = Number(prompt("Введите числa"));
    if (number < 0) {
      break;
    }
    sum += number;
    count++;
  }
  const average = sum / count;
  resultt.textContent = average;
  }
  
  
    
function func17() {
  let resultt=document.getElementById('f')
  var number = parseInt(prompt("Введите натуральное число:"));

  // Переменные для хранения результатов
  var count3 = 0;
  var countLastDigit = 0;
  var countEven = 0;
  var sumDigitsGreaterThan5 = 0;
  var prodDigitsGreaterThan7 = 1;
  var count05 = 0;
  
  // Преобразование числа в строку для обработки цифр
  var numberStr = number.toString();
  
  // Обход каждой цифры числа
  for (var i = 0; i < numberStr.length; i++) {
    var digit = parseInt(numberStr[i]);
  
    // Подсчет количества цифр 3
    if (digit === 3) {
      count3++;
    }
  
    // Подсчет количества последней цифры
    if (digit === parseInt(numberStr.slice(-1))) {
      countLastDigit++;
    }
  
    // Подсчет количества четных цифр
    if (digit % 2 === 0) {
      countEven++;
    }
  
    // Подсчет суммы цифр, больших пяти
    if (digit > 5) {
      sumDigitsGreaterThan5 += digit;
    }
  
    // Подсчет произведения цифр, больших семи
    if (digit > 7) {
      prodDigitsGreaterThan7 *= digit;
    }
  
    // Подсчет количества встреч цифр 0 и 5
    if (digit === 0 || digit === 5) {
      count05++;
    }
  }
  
  // Вывод результатов
  alert('Количество цифр 3: ' + count3 + '\n'
    + 'Сколько раз встречается последняя цифра: ' + countLastDigit + '\n'
    + 'Количество четных цифр: ' + countEven + '\n'
    + 'Сумма цифр, больших пяти: ' + sumDigitsGreaterThan5 + '\n'
    + 'Произведение цифр, больших семи: ' + prodDigitsGreaterThan7 + '\n'
    + 'Количество встреч цифр 0 и 5: ' + count05);
}

function func18() {
  let resultt=document.getElementById('ff')
  let num = prompt("Введите натуральное число, в котором все цифры различны:");
  // Считывание числа и преобразование его к массиву цифр
  let digits = Array.from(String(num), Number);
  // Определение максимальной цифры и ее порядкового номера, считая номера от конца числа
  let maxDigit = Math.max(...digits);
  let maxIndexFromEnd = digits.reverse().indexOf(maxDigit);
  // Определение порядкового номера максимальной цифры, считая номера от начала числа
  let maxIndexFromStart = digits.length - maxIndexFromEnd - 1;
  // Определение минимальной цифры и ее порядкового номера, считая номера от конца числа
  let minDigit = Math.min(...digits);
  let minIndexFromEnd = digits.reverse().indexOf(minDigit);
  // Определение порядкового номера минимальной цифры, считая номера от начала числа
  let minIndexFromStart = digits.length - minIndexFromEnd - 1;
  // Вывод результатов в alert
  alert("Порядковый номер максимальной цифры (от конца числа): " + maxIndexFromEnd + "\n" +
        "Порядковый номер максимальной цифры (от начала числа): " + maxIndexFromStart + "\n" +
        "Порядковый номер минимальной цифры (от конца числа): " + minIndexFromEnd + "\n" +
        "Порядковый номер минимальной цифры (от начала числа): " + minIndexFromStart);
}
function func19() {
  let resultt=document.getElementById('fff')
  var number = prompt("Введите натуральное число:");
  var isPrime = true;
  
  if (number <= 1) {
    isPrime = false;
  } else {
    for (var i = 2; i < number; i++) {
      if (number % i === 0) {
        isPrime = false;
        break;
      }
    }
  }
  
  if (isPrime) {
    alert(number + " - простое число");
  } else {
    alert(number + " - не является простым числом");
  }
}

function func20() {
  let resultt=document.getElementById('ffff')
  var number = prompt("Введите натуральное число:");

  // Преобразуем число в строку и разбиваем его на отдельные цифры
  var digits = String(number).split("");
  
  // Проверяем, является ли последовательность цифр упорядоченной по возрастанию
  var isAscending = true;
  for (var i = 0; i < digits.length - 1; i++) {
    if (parseInt(digits[i]) > parseInt(digits[i + 1])) {
      isAscending = false;
      break;
    }
  }
  if (isAscending) {
    alert("Последовательность цифр является упорядоченной по возрастанию.");
  } else {
    alert("Последовательность цифр не является упорядоченной по возрастанию.");
  }
}

function func21() {
  let resultt=document.getElementById('w')
var n = parseInt(prompt("Введите число n:"));

// Упорядоченная последовательность, оканчивающаяся числом 10000
var sequence = [ 10000];

// Индекс первого числа, большего заданного n
var index = -1;

// Поиск индекса первого числа, большего заданного n
for (var i = 0; i < sequence.length; i++) {
  if (sequence[i] > n) {
    index = i;
    break;
  }
}

// Вывод результата
if (index === -1) {
  alert("В последовательности нет чисел, больших заданного " + n);
} else {
  alert("Порядковый номер первого числа, большего " + n + ": " + index);
}
}

function func22() {
  let resultt=document.getElementById('ww')
  var number = parseInt(prompt("Введите натуральное число:"));
  var aCount = 0;
  var bCount = 0;
  
  var numberString = number.toString();
  
  // Перебор каждого символа в строке числа
  for (var i = 0; i < numberString.length; i++) {
      var digit = parseInt(numberString[i]);
  
      if (digit === 2) {
          aCount++;
      } else if (digit === 3) {
          bCount++;
      }
  }
  

  if (aCount < bCount) {
      alert("Цифра 2 встречается реже, чем цифра 3");
  } else {
      alert("Цифра 2 чаще, чем цифра 3");
  }
}


function func23() {
  let resultt=document.getElementById('www')
  var num = 10;
  var message = "";
  while (num <= 30) {
    message += num + "\n"; 
    num++;
 }
  alert(message);

}

  
  </code>
    <h2 style="text-align: center">ВЫВОД</h2>
  JavaScript – это язык программирования, который добавляет интерактивность на ваш веб-сайт (например: игры, отклик при нажатии кнопок или при вводе данных в формы, динамические стили, анимация). Эта статья поможет вам начать работать с этим захватывающим языком и даст вам представление о том, на что он способен.

Хотя PHP, главным образом, предназначен для работы в среде веб-серверов, область его применения не ограничивается только этим. Читайте дальше и не пропустите главу Возможности PHP либо, начните непосредственно с Вводного руководства, если вас интересует исключительно веб-программирование.

