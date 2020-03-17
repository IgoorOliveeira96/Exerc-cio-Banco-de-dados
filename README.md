# Exerc-cio-Banco-de-dados

1 - SHOW DATABASES;
USE pokedex;

2- DESC pokemon;

3- SELECT * FROM pokemon; 

4- SELECT numero, nome, cor, altura_m, peso_kg 
FROM pokemon;

5- SELECT numero, nome 
FROM pokemon
WHERE geracao = 1;

6- SELECT numero, nome
FROM pokemon
WHERE cor = 'Amarelo' AND geracao = 1;

7- SELECT numero, nome, total
FROM pokemon
WHERE total >= 720;

8- SELECT numero, nome, tipo1
FROM pokemon
WHERE tipo1 = 'Fire';

9- Não existe a questão

10- SELECT numero, nome, defesa
FROM pokemon
ORDER BY numero DESC, nome DESC, defesa DESC;

11- SELECT nome, numero
FROM pokemon
WHERE taxa_captura <= 3;

12- SELECT numero, nome
FROM pokemon
WHERE  NOT tipo2 ;

13- SELECT numero, nome, tipo1, tipo2, peso_kg
FROM pokemon
WHERE peso_kg BETWEEN 100.00 AND 500.00;

14- SELECT numero, nome, velocidade
FROM pokemon
WHERE velocidade
LIMIT 10;

15- SELECT numero, nome, tipo1, tipo2, taxa_captura
FROM pokemon
WHERE taxa_captura > 100
ORDER BY taxa_captura DESC;

16- SELECT tipo1
FROM pokemon;

17- SELECT numero, nome, cor
FROM pokemon
WHERE nome LIKE 'd%';

18- SELECT numero, nome, total
FROM pokemon
WHERE total > 700;

19- SELECT numero, nome, defesa, ataque
FROM pokemon
WHERE defesa > 60 AND ataque <= 70
ORDER BY total DESC;

20- SELECT nome, tipo1, cor
FROM pokemon
WHERE tipo1 = 'planta' AND 'venenoso' AND cor <> 'green'
ORDER BY nome ASC;

21- SELECT nome 
FROM pokemon
WHERE nome LIKE '___y%'
ORDER BY nome ASC;

22- SELECT ataque_especial
FROM pokemon
WHERE ataque_especial > 150;

23- SELECT numero, nome, altura_m
FROM pokemon
WHERE altura_m > 2.10;

24- SELECT cor
FROM pokemon
ORDER BY cor ASC;

25- SELECT nome, velocidade FROM pokemon
WHERE velocidade BETWEEN 30 AND 70 
ORDER BY nome ASC, velocidade DESC;

26- SELECT numero, nome, lendario, total
FROM pokemon
WHERE lendario <> 0
ORDER BY total DESC;

27- SELECT numero, nome, geracao, taxa_captura
FROM pokemon
WHERE geracao = 1 AND taxa_captura = 255;

28- SELECT * FROM pokemon
WHERE nome in ('Pikachu', 'Squirtle', 'Bulbasaur', 'Charmander')
ORDER BY total DESC;

29- SELECT nome, total, geracao <> 0
FROM pokemon
WHERE nome LIKE 'd%'
ORDER BY taxa_captura ASC, total DESC;

30- SELECT numero, nome, total, taxa_captura
FROM pokemon
WHERE taxa_captura
LIMIT 5;

31- SELECT numero, nome, peso_kg
FROM pokemon
WHERE peso_kg BETWEEN 2 AND 3;

32- SELECT numero, nome, tipo1, tipo2
FROM pokemon
WHERE tipo1 = 'normal';

33- SELECT numero, nome, tipo1, tipo2, cor
FROM pokemon
WHERE tipo2 = 'water' AND cor <> 'blue'
ORDER BY nome ASC;

34- SELECT numero, nome, velocidade
FROM pokemon
WHERE velocidade < 25
LIMIT 10;

35- SELECT nome
FROM pokemon
WHERE nome LIKE 'a%a';

36- SELECT numero, nome, tipo1, tipo2, cor
FROM pokemon
WHERE tipo2 <> 'fire'
ORDER BY nome ASC;

37- SELECT peso_kg
FROM pokemon
ORDER BY peso_kg ASC;

38- SELECT numero, nome, hp
FROM pokemon
WHERE hp BETWEEN 0 AND 100
ORDER BY hp ASC, nome ASC;

39- SELECT numero, nome, hp, ataque, defesa, total
FROM pokemon
WHERE hp >= 100 AND ataque >= 100 AND defesa >= 100;

40- SELECT numero, nome, tipo1, tipo2
FROM pokemon
WHERE tipo1 = 'water' AND tipo2 = 'gelo'; 

