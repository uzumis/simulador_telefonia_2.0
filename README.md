# simulador_telefonia_2.0

Trabalho final para o módulo Projeto de Algoritmos 2

# Simulador de Telefonia #

# Sobre
Um demonstrador em Java de como um fluxo de ligações, chamadas em espera funcionam em um ambiente com antenas, simulando, pro fim, uma telefonia ativa.


# Software usado e testado

Windows:

IntelliJ e Gitbash (para log).

Ubuntu:

IntelliJ e Terminal (para log).

# Comandos existentes:

## O output dos comandos estão disponíveis no Terminal preferido através do comando tail -f antenas.log localizado na pasta deste repositório. O arquivo log é incrementado conforme as informações registradas durante a simulação.

## Ligações manuais:

**ligar x y** - Onde x é o número que vai efetuar a ligação e y é o número ao qual recebe a ligação;

**desligar x** - Onde x é o número que está em ligação. O comando encerra a ligação.

## Antena: 

**status x** - Onde x é a Antena. Esse comando retorna o log de chamadas da Antena, incluindo a sua lista de espera;

**espera x** - Onde x é a Antena. Retorna a lista de espera da antena;

**proximo x** - Onde x é a Antena. Retorna o primeiro número a sair da antena (com base na prioridade dos números).

## Simulação:

**startDiscadores** - Comando onde inicia o processo automático do simulador de antenas;

**pauseDiscadores** - Pausa a simulação.

**resumeDiscadores** - Retorna a simulação.

## Sistema:
Exit - Encerra o programa. 
