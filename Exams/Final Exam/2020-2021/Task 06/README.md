# Task: Цикли в граф (Medium) - [HackerRank](<https://www.hackerrank.com/contests/exam-2020-02-06-sda/challenges/challenge-2856>)


### Statement:

Даден е ненасочен претеглен граф. Вашата задача е да проверите дали в графа има цикли, като ако има такива да намерите минималната сума на рабра, които трябва да бъдат премахнати така, че графа да няма цикли. 


### Input format

N M - брой на върхове и ребра в графа

xi xj wi - M на брой тройки които показват, че между два върха има ребро със съответното тегло.


### Constraints

$0 \lt N,w \lt 10^5$
$0 \lt M \le 6 \cdot 10^5 $

### Output format

едно число, което показва сумата на ребрата които трябва да бъдат премахнати, ако няма цикли тази сума е 0


### Samples


#### Sample Input 0
```
4 6
0 1 2
0 2 1
0 3 1
1 2 3
1 3 1
2 3 4
```

#### Sample Output 0
```
3
```