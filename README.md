🧮 Calculadora de Soma Simples com Node.js
Este é o meu primeiro exercício prático em JavaScript rodando no lado do servidor (Node.js). O objetivo foi aprender a interagir com o usuário através do terminal, recebendo dados e processando operações matemáticas.

📝 Descrição do Projeto
O script solicita o nome do usuário e três valores numéricos. Após a entrada dos dados, o programa realiza a soma desses valores e exibe o resultado final no console.

🛠️ Tecnologias e Conceitos Utilizados
- Node.js: Ambiente de execução JavaScript fora do navegador.

- Módulo readline: Biblioteca nativa do Node.js para ler dados de um fluxo (como o teclado).

- Funções de Callback: Técnica para garantir que uma pergunta só seja feita após a resposta da anterior.

- Manipulação de Tipos: Uso do parseInt() para converter textos (Strings) em números inteiros, permitindo a soma matemática.

🏗️ Como o Código Funciona
O fluxo do programa segue uma estrutura de "escada" (conhecida como Callback Hell, algo que aprenderei a simplificar no futuro!), garantindo a ordem das perguntas:

1 - Criação da Interface: Configuramos a entrada (stdin) e saída (stdout) de dados.

2 - Captura de Dados: O método .question() pausa a execução e espera o usuário digitar algo.

3 - Processamento: Os valores recebidos como texto são transformados em números.

4 - Encerramento: O método .close() finaliza a interface para que o programa não fique rodando infinitamente.
