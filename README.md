# 🧮 Terminal Math: Soma Dinâmica com Node.js

Este projeto marca o meu início no desenvolvimento **Backend** utilizando **Node.js**. O objetivo foi criar uma ferramenta de CLI (Command Line Interface) que interage com o usuário diretamente pelo terminal para processar operações matemáticas simples.

> **Status:** ✅ Concluído (Primeiros passos no Node.js)

---

### 📝 Descrição do Projeto
O script foi desenvolvido para exercitar a captura de dados via fluxo de entrada do sistema. Ele solicita o nome do usuário e três valores numéricos, realiza o tratamento desses dados e entrega a soma total em uma mensagem personalizada no console.

### 🛠️ Tecnologias e Conceitos Aplicados

- **Node.js:** Ambiente de execução para rodar JavaScript no servidor.
- **Interface Readline:** Utilização do módulo nativo `readline` para gerenciar a entrada (`stdin`) e saída (`stdout`) de dados.
- **Assincronia (Callbacks):** Aplicação de funções de callback para controlar o fluxo de perguntas e respostas de forma sequencial.
- **Tipagem Dinâmica e Conversão:** Tratamento de dados com `parseInt()` para garantir a integridade das operações aritméticas entre Strings e Inteiros.

### 🏗️ Arquitetura do Fluxo

Para garantir que o Node.js aguardasse a resposta do usuário antes de seguir para a próxima linha, o código foi estruturado em camadas:

1.  **Configuração de I/O:** Inicialização da interface de leitura do terminal.
2.  **Captura de Input:** Sequenciamento de perguntas utilizando o método `.question()`.
3.  **Lógica Matemática:** Conversão de tipos e processamento da soma.
4.  **Gerenciamento de Memória:** Fechamento da interface com `.close()` para encerrar o processo no sistema operacional.


---

👨‍💻 Desenvolvedor
<table style="border: none;">
<tr>
<td align="center">
<a href="#">
<img src="https://github.com/alvesthzin-art.png" width="100px;" alt="Avatar"/><br />
<sub><b>@alvesthzin-art</b></sub>
</a>
</td>
</tr>
</table>

 
*Desenvolvido durante minha jornada de estudos no SENAI Jandira.*
