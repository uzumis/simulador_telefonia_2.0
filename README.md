# simulador_telefonia_2.0
Final assignment for Algorithm Project 
Etapas:

-Uma central guarda todos os números válidos.

-Cada antena guarda um grupo dos números existentes.

-Ao solicitar uma ligação, um número pode ativar mais de uma antena, mas não pode receber mais de uma chamada.

-Ligações tem uma duração d.

-Um n° desocupado (number.online = false) disca para um n° qualquer.

-Caso o número esteja desocupado e as antenas tenham vaga, a ligação é iniciada (number.online = true).

-Cada antena só pode realizar n ligações simultaneamente.

-Se uma antena atingir o número máximo de ligações, a próxima ligação entrará em uma “fila de espera de solicitações”.

-Os números também são divididos em classes de prioridades. As solicitações de ligação, cuja SOMA das prioridades entre solicitante e recebedor forem mais altas, são conectadas primeiro pelas antenas.

REQUISITOS

RF001 – Iniciar uma chamada.

RF002 – Aceitar uma chamada.

RF003 – Encerrar uma chamada.

RNF001 – A fila de espera será definida pela última antena ativada (aquela que possuir o número de destino).

-Feito: Classes definidas;

Decisão de chamadas por thread;

-A fazer: Vincular a chamada com as classes envolvidas:

Contabilizar as chamadas por antena;

Criar condição se a ligação exceder o limite das chamadas da antena, entrar na fila de prioridade ( o que entra é a soma das categoria dos números);,

A chamada seria : 1 número X com classe Y usa a Antena A para ligar para o 2 com o número Z com a classe P e usa a antena B. A soma da classe Y com o P determina a sua fila de prioridade caso nenhuma antena esteja disponível.

Se os números estiverem na mesma antena para se ligarem, a antena ocupará apenas 1 slot de chamada.

Caso estiverem em antenas distintas, cada antena ocupará 1 slot de chamada correspondente ao seu número.
