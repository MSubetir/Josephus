# Josephus


Técnica de indução

F0 (x) = (x + k) % i
Fn+1 = F0 ° Fn

Obs: O "i" é a variável do loop (for). É o número de pessoas na roda, o qual aumenta conforma a indução até o número total "n".
Substítui o "n-1" que seria utilizado no precesso reverso (mesmo resultado).
Optei pelo loop e pelo "n+1" porque é mais fácil de visualizar o processo.

Obs: F0 e F1 dão 0 por não ter ninguém ou somente 1 pessoa.

Exemplo: 

F1 = F0 ° F0 = (0 + k) % i1   
F2 = F0 ° F1 = (((0 + k) % i1) + k) % i2    
F3 = F0 ° F2 = (((((0 + k) % i1) + k) % i2) + k) % i3    

Aplicando-se os mesmo valores se obtem o mesmo resultado do programa.

Técnica da lista

Obs: É extremamente simples. Ele sempre segue somando o intervalo, posicionando a espada de acordo com a quantidade remanescente na roda.
Verifica se o index é maior que o tamanho da roda (lenght) para realizar um ou mais giros.

Acredito ser o método mais simples e mais útil, considerando o leque de possibilidades que abre.
