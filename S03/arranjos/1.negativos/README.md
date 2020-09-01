# POO2020N
Programaçao Orientada a Objetos

Função que recebe como parâmetro um vetor de números reais de tamanho n definido e retorna a quantidade de ítens negativos.

Código separa a declaração e definição da função "negativos" em arquivos distintos do "main".

Compilar usando:

// para compilar e linkar os arquivos ao mesmo tempo
g++ main.cpp negativos.cpp -o negativos  

// para compilar primeiro e linkar a seguir
g++ -c main.cpp                         //compila main
g++ -c negativos.cpp                    //compila negativos
g++ main.o negativos.o -o negativos     //linka os diversos arquivos
