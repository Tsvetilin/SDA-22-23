# Task 2. Турнири (Medium) - [HackerRank](<https://www.hackerrank.com/contests/sda-hw-3-2022/challenges/challenge-3669>)

## Statement:

От другата седмица започват турнирите по бокс във ФМИ. Тъй като има твърде много записани студенти организаторите решават за всеки турнир да има ограничение за теглото на участниците. Всеки от турнирите има минимум $min_j$ и максимум $max_j$ , а всеки от записаните студенти, има тегло $w_i$ и ще участва в дадения турнир ако $min_j \le w_i \le max_j$, затова организаторите трябва да знаят колко чифта ръкавици да вземат.

Вашата задача е при подаден списък от теглата на записаните студенти и ограниченията за всеки турнир да намерите колко участници ще има на всеки от турнирите.


**Input Format**

От първия ред се въвеждат $N$ и $P$ броя записани студенти и броя турнири.

От следващия ред се въвеждат  числа $w_i$ теглата на записаните студенти.

От следващите  реда се въвеждат по 2 числа $min_j$ и $max_j$ - минималото и максималното тегло за турнира.

**Constraints**

$1 \le N \le 10^6$

$1 \le w_i \le 10^9*$

$1 \le Q \le 10^5$

$1 \le min_j, max_j \le 10^9*$

**Output Format**

За всеки турнир изведете по 1 число, броя на участниците в него.

---

**Sample Input 0**

```
5 2
70 80 60 100 30
60 80
70 100
```

**Sample Output 0**

```
3
3
```

**Explanation 0**

На първия турнир ще участват 60, 70, 80

На втория турнир ще участват 70, 80, 100