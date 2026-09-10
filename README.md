# calculadora-python-EBAC-PROJETO1

# Sobre o projeto

A Calculex 33.000 (Bom nome eu sei) é uma calculadora de linha de comando (terminal) que executa as 7 operações matemáticas mais comuns: soma, subtração, multiplicação, divisão, módulo (resto da divisão), potenciação e raiz quadrada.

É meu primeiro projeto e primeira vez utilizando tudo que necessita para chegar até essa etapa

# Como funciona

Boas-vindas: o programa pede o nome do usuário e explica como usar a calculadora, incluindo um exemplo de cálculo.

Validação dos números: usa dois loops while True com try/except — cada número digitado é convertido pra float(); se o usuário digitar algo que não seja número, o programa avisa e pede de novo, sem travar.

Escolha da operação: um dicionário (operacoes_disponiveis) guarda as opções (1 a 7) com seus nomes. Outro loop garante que só uma opção válida seja aceita, repetindo a pergunta até acertar.

Cálculo: uma cadeia de if/elif executa a operação escolhida e imprime o resultado formatado (ex: 8.5 x 9.3 = 79.05). No caso da raiz quadrada, calcula a raiz dos dois números digitados, não a raiz de um resultado.

Repetição: ao final de cada cálculo, pergunta se o usuário quer continuar (s/n). Um loop externo (while True) mantém o programa rodando até a resposta ser n, quando então se despede e encerra.

# Tratamento de erros

O código não quebra com entradas inválidas — nem números mal digitados, nem opções de operação fora do intervalo, nem respostas inesperadas na pergunta final. Tudo é revalidado com loops até o usuário acertar.

# Como rodar

No terminal, dê permissão com 'chmod + x calculadora.sh' e 'chmod 744 calculadora.sh', depois execute com './calculadora.sh'

# Tecnologias utilizadas

Python 3

# Autor

Desenvolvido por Jonathas Mrotzeck.