# ExploratoryDataAnalysis_CourseProject01

Introdução

Esta atribuição usa dados do UC Irvine Machine Learning Repository , um repositório popular para conjuntos de dados de machine learning. Em particular, usaremos o "Conjunto de dados de consumo individual de energia elétrica residencial" que disponibilizei no site do curso:

- Conjunto de dados : Consumo de energia elétrica [20 Mb]
- Descrição : Medições de consumo de energia elétrica em uma residência com uma taxa de amostragem de um minuto durante um período de quase 4 anos. Diferentes grandezas elétricas e alguns valores de submedição estão disponíveis.

As seguintes descrições das 9 variáveis ​​no conjunto de dados foram retiradas do site da UCI :

1 - Data : Data no formato dd / mm / aaaa

2 - Hora : hora no formato hh: mm: ss

3 - Global_active_power : energia ativa média por minuto global da família (em quilowatt)

4 - Global_reactive_power : energia reativa média por minuto global doméstica (em quilowatt)

5 - Tensão : tensão média por minuto (em volt)

6 - Intensidade_global : intensidade de corrente média por minuto global da família (em ampere)

7 - Sub_metering_1 : sub-medição de energia No. 1 (em watt-hora de energia ativa). Corresponde à cozinha, que contém essencialmente uma máquina de lavar louça, um forno e um micro-ondas (a placa eléctrica não é eléctrica mas sim a gás).

8 - Sub_metering_2 : sub-medição de energia No. 2 (em watt-hora de energia ativa). Corresponde à lavanderia, contendo uma máquina de lavar, uma secadora, uma geladeira e uma luz.

9 - Sub_metering_3 : sub-medição de energia No. 3 (em watt-hora de energia ativa). Corresponde a um aquecedor elétrico de água e um ar condicionado.

Carregando os dados

Ao carregar o conjunto de dados em R, considere o seguinte:

- O conjunto de dados possui 2.075.259 linhas e 9 colunas. Primeiro, calcule uma estimativa aproximada de quanta memória o conjunto de dados exigirá na memória antes de ler em R. Certifique-se de que seu computador tenha memória suficiente (a maioria dos computadores modernos deve funcionar).

- Usaremos apenas dados das datas 01-02-2007 e 02-02-2007. Uma alternativa é ler os dados apenas dessas datas, em vez de ler todo o conjunto de dados e definir subconjuntos para essas datas.

- Você pode achar útil converter as variáveis ​​de Data e Hora em classes de Data / Hora em R usando as funções strptime()e as.Date().

- Observe que, neste conjunto de dados, os valores ausentes são codificados como ?.

Fazendo plotagens

Nosso objetivo geral aqui é simplesmente examinar como o uso de energia doméstica varia ao longo de um período de 2 dias em fevereiro de 2007. Sua tarefa é reconstruir os gráficos a seguir, todos construídos usando o sistema de plotagem de base.

Primeiro, você precisará bifurcar e clonar o seguinte repositório GitHub: https://github.com/rdpeng/ExData_Plotting1

Para cada parcela, você deve:

- Construa o gráfico e salve-o em um arquivo PNG com uma largura de 480 pixels e uma altura de 480 pixels.

- Nome cada um dos arquivos de plotagem como plot1.png, plot2.png, etc.

- Criar um ficheiro de código separado R ( plot1.R, plot2.R, etc.) que constrói a trama correspondente, isto é, código de plot1.Rconstruções a plot1.pngtrama. Seu arquivo de código deve incluir o código para a leitura dos dados para que o gráfico possa ser totalmente reproduzido. Você também deve incluir o código que cria o arquivo PNG.

- Adicione o arquivo PNG e o arquivo de código R ao seu repositório git

Quando você terminar com a atribuição, envie seu repositório git para GitHub para que a versão GitHub de seu repositório seja atualizada. Deve haver quatro arquivos PNG e quatro arquivos de código R.

