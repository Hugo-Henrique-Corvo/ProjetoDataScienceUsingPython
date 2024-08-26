# Projetos Disciplina Data Science Using Python

## Projeto 1 - Decodificador Morse

Objetivo:

* Interceptar as mensagens de morse;
* Decodificar, sabendo que as letras estão espaçadas por um espaço;
* Salvar as mensagens em um arquivo em texto claro;
* Salvar o datetime da decodificação da mensagem;

Aspectos Obrigatórios do projeto:

* Recebe a mensagem como argumento;
* O "de-para morse" não deve estar hard coded;
* Path do arquivo não deve estar hard coded;
* Messagem deve ser passada através do keyboard.

Coniderações Finais:

* As letras devem ser separadas por um espaço
* As palavras devem ser separadas por dois espaços
* Executar com pelo menos 3 cenários diferentes, ou seja, 3 textos
* Você deve criar estes textos /frases de input

O projeto finalizado (arquivo .py e arquivo com as frases em texto claro) está [nesta pasta](Scripts) sendo:

* projeto_1_final.py = Script utilizando a estrutura de funções;
* projeto_1_v2.py = Script utilizando uma classe para o decodificador;
* frases_decod.csv = Arquivo com as frases traduzidas;

As frases que foram utilizadas como teste estão [nesta pasta](Docs) no arquivo de nome "Mensagens_morse.txt"


## Projeto 2 - Análise exploratória

Objetivo:

Realizar uma análise exploratória da base de voos de Nova Iorque para entender como se comportam os atrasos dos voos.

A base a ser explorada contém a seguinte estrutura:

* ano,mês,dia: Data de partida
* dep_time,arr_time: Horários de partida e chegada, formato HMM ou HHMM
* dep_delay,arr_delay: Atrasos de partida e chegada, em minutos. Tempos negativos representam partidas/chegadas antecipadas.
* hora,minuto: Hora de partida dividida em horas e minutos
* transportadora: abreviação de duas letras para transportadora
* tailnum: Número da cauda do avião
* voo: Número do voo
* origin,dest: Origem e destino.
* air_time: Quantidade de tempo gasto no ar
* distância: Distância voada

O projeto de desenvolvimento pode ser encontrado [nesta pasta](Scripts) , no arquivo de nome "projeto_2.ipynb"
