# 📱 Protótipo — FaculResolve

Protótipo mobile desenvolvido para representar a proposta do **FaculResolve — Central de Suporte e Atendimento Acadêmico**.

O aplicativo busca centralizar e agilizar o atendimento aos estudantes, permitindo a abertura de chamados, o acompanhamento de protocolos em tempo real, o envio de documentos e o acesso rápido a soluções acadêmicas e dúvidas frequentes.

[![Abrir no Figma](https://img.shields.io/badge/Abrir%20protótipo-Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/8sZfS0XjwaMhVcZYGXSvJT/UDF-PARKING?node-id=0-1&p=f&t=noq3KyzZw545d4aB-0)

---

## 🎯 Objetivo do protótipo

Demonstrar visualmente como os estudantes poderiam:

- abrir novos chamados informando categorias e descrições;
- anexar documentos e comprovantes de forma digital e segura;
- acompanhar o status dos protocolos em tempo real (Aberto, Em análise, Concluído);
- consultar uma base de conhecimento (FAQ) para respostas rápidas;
- receber notificações sobre atualizações de suas solicitações;
- visualizar o histórico completo de atendimentos anteriores.

---

## 📲 Telas desenvolvidas

### 1. Início / Painel Principal

A tela inicial apresenta uma visão geral das solicitações do aluno, incluindo:

- total de chamados ativos e resolvidos;
- atalho rápido para o botão de "Novo Chamado";
- lista rápida com os últimos protocolos abertos e seus respectivos status;
- menu de navegação inferior (Início, Meus Chamados, FAQ, Perfil).

### 2. Abertura de Novo Chamado

Formulário simplificado para o envio de novas demandas:

- seleção de categoria (Ex: Matrícula, Secretaria, Financeiro, Notas);
- campo de descrição detalhada do problema;
- botão para anexar arquivos e documentos (PDF, PNG, JPG);
- envio seguro com confirmação imediata de protocolo gerado.

### 3. Acompanhamento de Protocolos

Apresenta o detalhamento de um chamado específico, permitindo visualizar:

- número do protocolo e data de abertura;
- status atual com destaque visual (Ex: 🟡 Em análise, 🟢 Concluído);
- linha do tempo ou histórico de interações e respostas da secretaria;
- opção para reabrir o chamado (dentro do prazo de 48h) ou avaliar o atendimento.

### 4. Central de Ajuda (FAQ) & Autoatendimento

Reúne soluções rápidas para dúvidas comuns antes da abertura de chamados:

- perguntas frequentes categorizadas por assunto;
- barra de busca inteligente por palavras-chave;
- tutoriais rápidos sobre processos burocráticos da faculdade.

> Os fluxos apresentados no protótipo simulam a jornada completa do estudante desde o relato do problema até a solução final pela secretaria.

---

## 🔄 Fluxo principal

```text
Início → Abertura de novo chamado → Preenchimento de dados e anexos → Geração de protocolo
       → Painel de acompanhamento de status
       → Consulta à Base de Conhecimento (FAQ)
