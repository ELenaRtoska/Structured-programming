# Structured-programming

## Променливи, оператори, влез-излез
### Аритметички операции
Да се напише програма која ќе ги изведува основните математички операции (+, -, *, /, %) врз два броја кои се читаат од стандарден влез.

### Индекс на телесна маса
Да се напише програма која вчитува од стандарден влез два децимални броја (маса во кг и висина во цм) и пресметува и печати на стандарден излез индекс на телесна маса по формулата:

BMI=masa/(visina∗visina)
Висината претходно треба да се претвори од сантиметри во метри.

### Секунди во време 
Да се напише програма коjа за даден цел броj секунди коj се чита од стандарден влез, ќе ги отпечати на екран соодветните вредности во часови, минути и секунди.

### Просек 
Да се напише програма која пресметува просечна оцена во семестар. Програмата чита 5 цели броја. Треба да се испечати еден реален број на две децимали, просек на прочитаните броеви.

### Банкноти и монети
Да се напише програма која за дадена сума на пари, ќе испечати со колку најмалку банкноти и монети може да се исплати. На влез се чита еден цел број. На излез се печатат 9 редови, по колку банкноти или монети од секој апоен ни се потребни за да ја исплатиме сумата. Пример 1583 денари, најдобро е да се исплати како:

0*5000

1*1000

1*500

0*100

1*50

3*10

0*5

1*2

1*1

## Контролни структури за избор 
### Број палиндром
Да се напише програма која за трицифрен број прочитан од стандарден влез ќе проверува дали е палиндром. Ако бројот е палиндром, на екран треба да се испечати порака "Palindrom", во спротивно - "Ne e palindrom". Доколку внесениот број не е трицифрен треба да се испечати порака "Nevaliden vlez".

### Правоаголник и квадрат
Да се напише програма во која од стандарден влез се читаат два броја што претставуваат должини на страни на правоаголник, како и еден број што претставува должина на страна на квадрат. Програмата треба да испечати "Pravoagolnik" ако правоаголникот има поголем периметар, или "Kvadrat" ако квадратот има поголем периметар. Ако имаат ист периметар да се испечати "Isti se".

### Телефонски претплатник
Да се напише програма во која од стандарден влез се чита мобилен број во следниот формат XXYYYZZZ (пр. 71298486). Програмата треба да го испечати во формат XXX/YYY-ZZZ (пр. 071/298-486). Дополнително, треба да го испечати и името на иницијалниот оператор: - 070/071/072 - T-mobile, - 075/076 - One, - 077/078 - Vip.

## Циклуси
### Благ број 
Благ број е број што е составен само од парни цифри (0, 2, 4, 6, 8). Во зададен опсег (почетокот m и крајот на опегот n се цели броеви чија вредност се внесува од тастатура), да се најде и испечати најмалиот „благ број“. Ако не постои таков број, да се испечати NE.

### Парови цели броеви
Да се напише програма во која од стандарден влез прво се внесува еден позитивен цел број z, а потоа последователно се внесуваат парови цели броеви (a, b). Внесувањето на парови цели броеви треба да заврши кога корисникот ќе го внесе парот (0, 0). Треба да се пресмета колку пати z е еднаков на збирот на секој внесен пар броеви a и b, како и колкав процент од вкупниот број внесени парови (a, b) даваат збир z (ЗАБЕЛЕШКА: парот (0, 0) не се зема во предвид при извршувањето на пресметките!).

### Интересен број
Eден природен e „интересен“ ако неговиот обратен број е делив со неговиот број на цифри. Обратен број е бројот составен од истите цифри, но во обратен редослед (на пример, 653 е обратен број на бројот 356). Од тастатура се внесува природен број n ( n > 9). Да се најде и отпечати најголемиот природен број помал од n кој што е „интересен“. Ако внесениот број не е валиден, да се отпечати соодветна порака (Brojot ne e validen).

### Најди го збирот
Од стандарден влез се читаат знаци се додека не се прочита извичник. Во вака внесениот текст се скриени цели броеви (помали од 100). Да се напише програма што ќе ги прочита сите знаци и на излез ќе го испечати збирот на сите броеви скриени во текстот.

##  Еднодимензионални низи 
### Генерирање низа
Да се напише програма која од два дадени реални броеви генерира низа од N (N < 100) реални броеви. Првите елементи на низата се двата дадени броеви, а останатите елементи од низата се добиваат како половина од збирот на сите претходни елементи од низата. Бројот на елементи од низата и двата почетни елементи се читаат од СВ.

### Циклично поместување
Да се напише програма која извршува циклично поместување на елементите на дадена низа А од N (N < 100) цели броеви, за K-места во лево и во десно. Елементите на низата, нивниот број N и бројот на поместувања K се читаат од СВ.

Забелешка: Ако бројот K е позитивен поместувањето се извршува во десно, а ако е негативен во лево.

### Огледални броеви
Од стандарден влез се чита цел број N. Потоа се вчитуваат N низи од цели броеви (со максимална должина од 100 елементи), при што за секоја прво се внесува должината на низата, а потоа сите елементи на низата.

Да се напише програма која за секоја низа ќе ја отпечати сумата на сите еднакви огледални броеви во низата (огледални броеви се првиот и последниот, вториот и предпоследниот, итн…).

пример влез:
```
3
5 7 2 5 2 8
6 1 2 3 3 1 1
8 8 4 8 3 2 1 4 8
```
излез:
```
4   (2 + 2)
8   (1 + 1 + 3 + 3)
24  (8 + 8 + 4 + 4)
```
