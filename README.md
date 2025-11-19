## Preservativo x Idade - Uma Análise Direta
Este notebook foi criado para responder de forma clara e objetiva à pergunta: Qual faixa etária demonstra o maior comprometimento com a prevenção sexual?

Ele processa dados de pesquisa para identificar os padrões de uso de preservativo entre diferentes grupos de idade, transformando respostas textuais em um indicador numérico e fácil de visualizar.

# 🎯 A Resposta que Buscamos
O resultado central deste notebook é um gráfico que compara a Média da "Nota de Prevenção" entre os participantes, de acordo com a idade.

Ao final da execução, você terá a visualização imediata de qual grupo etário tem a média de prevenção mais alta (próxima de 4) e qual tem a mais baixa (próxima de 0).

Faixas Etárias Analisadas (segmentação utilizada no script):

Até 20 anos

21 a 25 anos

26 a 30 anos

Mais de 30 anos

# 📊 Nossa Metodologia (O Caminho Rápido para a Resposta)
Utilizamos o pandas para manipulação de dados e o matplotlib para a visualização, trabalhando com o arquivo de dados de entrada trabalho_final.csv.

1. Nota de Prevenção: Transformando Texto em Fato (0 a 4)
Para sermos assertivos, criamos uma escala numérica ("Nota de Prevenção") para a coluna uso_preservativo, permitindo um cálculo de média limpo por idade:

# 👥 Autores

Luiz Henrique Appelt Weller - 1138930

Pedro Henirque Polita - 1138911

Trabalho desenvolvido para a disciplina de Pensamento Computacional, sob orientação do Professor Fernando Posser.
