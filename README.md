Super Trunfo de Países em C

📌 Descrição

Este projeto é um jogo estilo Super Trunfo onde os jogadores podem comparar cartas de países usando dois atributos numéricos diferentes. O sistema permite a escolha de atributos e determina o vencedor baseado na soma dos valores comparados.

🚀 Como Compilar e Executar

Requisitos

Compilador GCC instalado

Terminal ou console para execução do programa

Passos

Clone este repositório:

git clone https://github.com/202503589593/Desafio-L-gica-Super-Trunfo.git
cd Desafio-L-gica-Super-Trunfo

Compile o programa:

gcc super_trunfo.c -o super_trunfo

Execute o programa:

./super_trunfo

📖 Regras do Jogo

O jogador escolhe duas cartas para a comparação.

O jogador escolhe dois atributos distintos entre:

População (vence o maior valor)

Área (vence o maior valor)

Densidade Demográfica (vence o menor valor)

O sistema compara os atributos e soma os valores.

A carta com a maior soma vence.

Em caso de empate, é exibida a mensagem "Empate!".

📊 Exemplo de Uso

Escolha a primeira carta:
1 - Brasil
2 - Estados Unidos
3 - Japão
> 1

Escolha a segunda carta:
2 - Estados Unidos
3 - Japão
> 2

Escolha o primeiro atributo para comparar:
1 - População
2 - Área
3 - Densidade Demográfica
> 1

Escolha o segundo atributo para comparar (diferente do primeiro):
1 - População
2 - Área
3 - Densidade Demográfica
> 2

Resultados:
Brasil - 213000000 + 8516000 = 221516000 pontos
Estados Unidos - 331000000 + 9834000 = 340834000 pontos
Vencedor: Estados Unidos!
