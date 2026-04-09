Calculadora Interativa em Python
Uma calculadora baseada em terminal, desenvolvida em Python, que utiliza loops infinitos para permitir múltiplas operações sem precisar reiniciar o script manualmente. O projeto foca em uma interface amigável e simulação de processamento para melhorar a experiência do usuário.

## Funcionalidades:

Operações Matemáticas:
- Soma (+)
- Subtração (-)
- Multiplicação (*)
- Divisão (/)
- Potenciação (**)

Loop Contínuo: A calculadora permanece ativa até que o usuário decida sair ou reiniciar.
UX Aprimorada: Utiliza a biblioteca time para simular um tempo de "cálculo", tornando a interação menos mecânica.
Sistema de Reinício: Opção dedicada para limpar o fluxo atual e retornar ao menu principal.

## Tecnologias Utilizadas:

Python 3.x
Biblioteca math: (Importada para futuras expansões de funções complexas).
Biblioteca time: Utilizada para o método sleep().

## Como Executar

1. Certifique-se de ter o Python instalado.

2. Baixe o arquivo calculadora_python.py.

3. Abra o terminal ou prompt de comando na pasta do arquivo.

4. Execute o comando:
Bash
python calculadora_python.py

## Como Usar:

1. Ao iniciar, o programa exibirá um menu numerado:
2. Escolha a operação digitando o número correspondente (1 a 5).
3. Insira o primeiro e o segundo número quando solicitado.
4. Aguarde o "processamento" e veja o resultado.
5. Para recomeçar o menu sem realizar um cálculo, escolha a opção 6.

## Estrutura do Código (Lógica)
O código utiliza uma estrutura de repetição while True que envolve todo o processo.
Controle de Fluxo: O comando continue é acionado caso o usuário escolha a opção "Reiniciar", pulando as solicitações de input numérico e voltando ao topo do loop.
Tipagem: Os inputs numéricos são convertidos para float, permitindo operações com números decimais.

Criado Por: Gustavo Lima
