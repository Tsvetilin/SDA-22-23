# Task: Най-продаван артикул (Hard) - [HackerRank](<https://www.hackerrank.com/contests/sda-exam-20222023-part-2/challenges/challenge-3881>)


### Statement:

Вие сте data engineer за голям онлайн магазин. Разполагате с информaция за закупените артикули и времето, в което са закупени. Вашата задача е да напишете програма, която по дадено време да може да връща, кой е най-продаваният артикул до момента.


### Input format

На първия ред на стандартния вход ще получите цяло число $N$. 

На следващите $N$ реда ще получите по две числа $ID$ и $TIME$, съответно: номера на закупеният артикул и времето, в което е закупен. Наредени са хронологично(сортирани според $TIME$)

На следвашия ред ще получите едно число $T$.

На следващте $T$ реда на стандартния вход ще получите заявки състоящите се от едно число $Q$.


### Constraints

Няма две покупки с еднакъв  $TIME$.

$1 \lt ID \le N$

При 50% от случайте

$1 \lt N \le 5000$

$1 \lt TIME\le 40000$
 
При останалите

$1 \lt N \le 10^5$

$1 \lt TIME\lt 10^10$

$1 \lt T \lt N$


### Output format

За всяка заявка върнтете на стандартния изход, най-продаваният артикул за време $Q$.


### Samples


#### Sample Input 0
```
6
1 3
0 12
1 22
0 24
0 29
1 38
4
34
40
21
2
```

#### Sample Output 0
0
1
0
-1

#### Explanation 0
По време 34 най-продаваният артикул е 0, понеже е продаден 3 пъти, докато 1 е продаден само 2 пъти.
По време 40 артикул 1 и артикул 0 са закупени еднакъв брой пъти (3), но правилният отговор е 1, понеже е закупен последно.
По време 21 всеки от двата артикула е закупен само веднъж, но отговора е 0 понеже време 12 е по-близко от време 3.
По време 2 няма все още закупени артикули(най-ранният закупен артикул е по време 3) за това отговора е -1