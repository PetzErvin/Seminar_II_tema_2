Exercițiul 1:

Acest exercițiu desenează un punct q și n alte puncte pe o formă. Distanța dintre q și fiecare dintre celelalte puncte este calculată, iar dacă distanța este mai mică sau egală cu o valoare constantă dconst, punctul este desenat în verde. În caz contrar, punctul este desenat în roșu. Valoarea dconst este setată la 200 în cod.

Exercițiul 2:

Acest exercițiu desenează n puncte pe o formă și le conectează trei dintre ele pentru a forma un triunghi cu cea mai mică suprafață. Pentru aceasta, punctele sunt sortate în ordine crescătoare după valoarea lui x*y. Apoi, fiecare combinație de trei puncte este testată, iar suprafața triunghiului este calculată folosind formula de încălțare. Punctele care formează triunghiul cu cea mai mică suprafață sunt apoi desenate în verde, iar liniile care le conectează sunt desenate, de asemenea.

Exercițiul 3:

Acest exercițiu desenează n puncte pe o formă și găsește cel mai mic cerc care conține două sau mai multe dintre puncte. Pentru aceasta, fiecare pereche de puncte este testată, iar cercul care le conține este calculat. Cercul cu cel mai mare raza este apoi ales, iar centrul și raza sa sunt folosite pentru a desena un cerc verde pe formă.

Rețineți că evenimentul Form1_Paint este utilizat pentru a declanșa desenarea exercițiilor. În funcție de exercițiul care este în prezent activ, metoda corespunzătoare este apelată.
