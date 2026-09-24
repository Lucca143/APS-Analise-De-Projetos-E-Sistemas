
# 📋 Projeto de APS — Sistema FaculResolve

## 🔗 Link do Board
[📌 Acessar o Board do projeto no Miro]()

## Levantamento e Priorização de Requisitos

**Etapa:** Levantamento de Requisitos  
**Técnica de Priorização:** MoSCoW  
**Data:** 17/09/2026  
**Turma:** Engenharia de Software — UDF

---

# 👥 1. Identificação do Grupo

| Nº | Integrante |
|---:|---|
| 1 | [Lucca Cavalcante](https://github.com/Lucca143) |
| 2 | [João Gabriel](https://github.com/Jotagegmf) |
| 3 | [Luan Reis](https://github.com/r31s) |
| 4 | [João Victor Montalvão](https://github.com/joaovictorcode7) |

---

# 2. Identificação do Projeto

**Nome do projeto:**

> FaculResolve

**Descrição resumida do projeto:**

> Proposta de uma plataforma digital centralizada que permita aos estudantes resolver demandas acadêmicas, solicitar atendimento, acompanhar o status de requerimentos e solucionar problemas burocráticos junto à faculdade de forma ágil e sem a necessidade de deslocamentos presenciais desnecessários.

---

# 3. Problema Identificado

## 3.1 Qual problema será resolvido?

**Resposta:**

> Os estudantes enfrentam dificuldades e burocracia para solucionar pendências acadêmicas, administrativas e financeiras junto à instituição. A falta de um canal centralizado e ágil causa perda de tempo, filas de atendimento, falta de clareza sobre o andamento dos pedidos e atrasos na resolução de problemas essenciais para a vida acadêmica.
>
> Além disso, muitas solicitações simples exigem deslocamento físico ou geram dezenas de e-mails desencontrados, sobrecarregando os canais de atendimento tradicionais.

---

## 3.2 Quem é afetado pelo problema?

**Resposta:**

> O problema afeta principalmente os alunos da faculdade, que perdem tempo buscando suporte, além dos atendentes da secretaria, coordinadores e o setor administrativo, que lidam com fluxos manuais e repetitivos de solicitações.

---

## 3.3 Como o problema é resolvido atualmente?

**Resposta:**

> Atualmente, os estudantes precisam recorrer a e-mails institucionais dispersos, portais legados confusos ou comparecer presencialmente à secretaria nos horários de pico. O acompanhamento do protocolo costuma ser manual e pouco transparente, gerando ansiedade e retrabalho.

---

## 3.4 Principais dificuldades encontradas

1. Falta de centralização dos canais de atendimento ao estudante.
2. Demora e falta de transparência no acompanhamento do status de solicitações.
3. Necessidade de deslocamento presencial para resolver burocracias simples.
4. Excesso de intermediários e fluxos de comunicação confusos.
5. Falta de uma base de dúvidas frequentes estruturada e acessível.

---

# 🎯 4. Objetivo do Projeto

**Objetivo:**

> Nosso projeto pretende otimizar e centralizar o suporte ao estudante por meio do FaculResolve, oferecendo uma plataforma intuitiva para abertura de chamados, acompanhamento de protocolos em tempo real e acesso rápido a soluções acadêmicas, reduzindo burocracias e o tempo de espera.

---

# 👤 5. Stakeholders

| ID | Stakeholder | Papel | Necessidade/Interesse | Influência |
|---|---|---|---|---|
| ST01 | Estudantes | Usuários principais | Abrir chamados, acompanhar status e resolver pendências | Alta |
| ST02 | Atendentes da Secretaria | Operadores do sistema | Triar, responder e gerenciar os chamados dos alunos | Alta |
| ST03 | Coordenação e Professores | Apoiadores técnicos | Resolver demandas pedagógicas e emitir pareceres | Média |
| ST04 | Administração da Instituição | Responsável estratégico | Monitorar a eficiência do atendimento e a satisfação | Alta |
| ST05 | Equipe de TI | Responsável técnico | Garantir a estabilidade e segurança da plataforma | Média |

---

## Stakeholder principal

**Stakeholder:**

> Estudantes da faculdade.

**Por que ele foi considerado o principal stakeholder?**

> Os alunos são os usuários diretamente afetados pelas barreiras burocráticas e pela lentidão no suporte atual. São eles que experimentam a fricção ao tentar resolver problemas de matrícula, notas, documentos e secretaria.

---

# 🗣️ 6. Levantamento de Informações

| Pergunta | Resposta |
|---|---|
| O que o usuário precisa fazer? | Abrir solicitações, anexar documentos, acompanhar o andamento e consultar FAQs. |
| Qual problema enfrenta atualmente? | Falta de transparência, lentidão e dispersão nos canais de atendimento. |
| Quais informações precisa consultar? | Status do chamado, histórico de solicitações e prazos de resposta. |
| Quais informações precisa cadastrar ou alterar? | Dados cadastrais básicos, tipo de ocorrência e descrição detalhada do problema. |
| Quais tarefas são repetitivas? | Enviar o mesmo e-mail várias vezes ou perguntar o status na secretaria. |
| Quais tarefas consomem mais tempo? | Esperar atendimento presencial ou aguardar retorno de e-mails genéricos. |
| Quais erros acontecem atualmente? | Envio de documentos incorretos ou perda de prazos por falta de visibilidade do protocolo. |
| Precisa receber notificações? | Sim, alertas por e-mail ou na plataforma a cada mudança de status do chamado. |
| Precisa gerar documentos ou relatórios? | A administração precisará de relatórios de volumetria e tempo de atendimento. |
| Existem informações que precisam ser protegidas? | Sim. Dados pessoais e documentos acadêmicos sigilosos. |
| O sistema precisará se comunicar com outros sistemas? | Integração futura com o sistema de gestão acadêmica da faculdade. |
| Existem regras obrigatórias que precisam ser respeitadas? | Sim. LGPD (Proteção de Dados) e prazos legais/institucionais de resposta. |

---

# 💡 7. Necessidades Identificadas

| ID | Stakeholder | Necessidade identificada | Problema relacionado |
|---|---|---|---|
| N01 | Estudantes | Centralizar todos os pedidos em um único painel | Canais de atendimento dispersos |
| N02 | Estudantes | Acompanhar o status do protocolo em tempo real | Falta de transparência no andamento |
| N03 | Estudantes | Enviar documentos digitais de forma segura | Necessidade de deslocamento presencial |
| N04 | Atendentes | Organizar e filtrar chamados por categoria e prioridade | Sobrecarga de solicitações manuais |
| N05 | Estudantes | Consultar uma base de conhecimento/FAQ antes de abrir chamado | Dúvidas repetitivas na secretaria |
| N06 | Administração | Visualizar métricas de tempo de resposta e satisfação | Falta de indicadores de atendimento |

---

# ⚙️ 8. Requisitos Funcionais

## Requisitos Funcionais do Projeto

| ID | Requisito funcional | Stakeholder/Fonte | Necessidade | Prioridade |
|---|---|---|---|---|
| RF01 | O sistema deve permitir que o estudante abra novos chamados informando categoria, descrição e anexando arquivos. | ST01 | N01 e N03 | Must Have |
| RF02 | O sistema deve fornecer um painel de acompanhamento exibindo o status atualizado dos chamados (Ex: Aberto, Em análise, Resolvido). | ST01 | N02 | Must Have |
| RF03 | O sistema deve permitir que os atendentes da secretaria filtrem, respondam e alterem o status dos chamados. | ST02 | N04 | Must Have |
| RF04 | O sistema deve disponibilizar uma seção de Perguntas Frequentes (FAQ) para autiatendimento. | ST01 | N05 | Should Have |
| RF05 | O sistema deve enviar notificações automáticas ao aluno sempre que houver atualização no seu chamado. | ST01 | N02 | Should Have |
| RF06 | O sistema deve gerar relatórios gerenciais de volume e tempo médio de resolução para a administração. | ST04 | N06 | Could Have |

---

# ⭐ 9. Requisitos de Qualidade

## Requisitos de Qualidade do Projeto

| ID | Característica | Requisito | Como será verificado? |
|---|---|---|---|
| RQ01 | Desempenho | O carregamento das páginas e o envio de chamados devem ocorrer em até 2 segundos. | Testes de desempenho e simulação de carga |
| RQ02 | Segurança | Os documentos e dados pessoais dos alunos devem ser criptografados e protegidos conforme a LGPD. | Auditoria de segurança e verificação de criptografia |
| RQ03 | Usabilidade | O estudante deve conseguir abrir um novo chamado em no máximo três cliques a partir da tela inicial. | Testes de usabilidade com alunos reais |
| RQ04 | Disponibilidade | A plataforma deve operar com disponibilidade de 99% durante os dias úteis. | Monitoramento contínuo de uptime |
| RQ05 | Compatibilidade | O sistema deve ser responsivo, funcionando perfeitamente em computadores e celulares. | Testes em diferentes tamanhos de tela e navegadores |

---

# 🚧 10. Restrições

| ID | Categoria | Restrição | Justificativa/Fonte |
|---|---|---|---|
| RES01 | Escopo | A versão inicial não incluirá integração automática com o ERP acadêmico legado. | Limitação de tempo de desenvolvimento da disciplina |
| RES02 | Legal | O tratamento de dados e documentos sensíveis deve obedecer estritamente à LGPD. | Exigência legal para sistemas educacionais |
| RES03 | Tecnológica | O projeto deve ser desenvolvido com tecnologias web padrão alinhadas ao escopo da matéria. | Diretrizes pedagógicas |

---

# 📜 11. Regras de Negócio

| ID | Regra de negócio | Fonte |
|---|---|---|
| RN01 | Apenas estudantes com matrícula ativa na instituição podem abrir chamados no FaculResolve. | Regimento Acadêmico |
| RN02 | Um chamado fechado pelo aluno só poderá ser reaberto em até 48 horas; após esse prazo, deve-se criar um novo protocolo. | Diretriz de Atendimento |
| RN03 | Anexos enviados nos chamados devem ter limite máximo de tamanho e extensões permitidas (PDF, PNG, JPG). | Equipe de TI / Segurança |

---

# 🔗 12. Rastreabilidade Inicial

| Necessidade | Stakeholder | Requisito(s) relacionado(s) |
|---|---|---|
| N01 | ST01 | RF01, RQ03, RQ05 |
| N02 | ST01 | RF02, RF05, RQ01 |
| N03 | ST01 | RF01, RQ02 |
| N04 | ST02 | RF03, RQ04 |
| N05 | ST01 | RF04, RQ03 |
| N06 | ST04 | RF06 |

---

# 🏷️ 13. Priorização dos Requisitos — Técnica MoSCoW

| Categoria | Significado |
|---|---|
| 🔴 **M — Must Have** | Requisito indispensável |
| 🟠 **S — Should Have** | Muito importante, mas pode esperar temporariamente |
| 🟢 **C — Could Have** | Desejável se houver tempo e recursos |
| ⚪ **W — Won't Have Now** | Não será implementado nesta entrega |

## Matriz de Priorização

| ID | Requisito | MoSCoW | Justificativa |
|---|---|---|---|
| RF01 | Abertura de chamados com anexos | M | É o núcleo funcional da proposta |
| RF02 | Painel de acompanhamento de status | M | Resolve a principal dor de falta de transparência |
| RF03 | Painel de gestão para atendentes | M | Permite que a secretaria opere o sistema |
| RF04 | Seção de FAQ / Autoatendimento | S | Reduz volume de chamados repetitivos |
| RF05 | Notificações automáticas | S | Melhora a experiência, mas pode ser simulada manualmente no início |
| RF06 | Relatórios gerenciais avançados | C | Útil para gestão, mas não bloqueia o uso inicial |
| RQ01 | Desempenho rápido (até 2s) | M | Garante fluidez na experiência |
| RQ02 | Conformidade com a LGPD | M | Proteção obrigatória de dados acadêmicos |
| RQ03 | Usabilidade simplificada | M | Essencial para adoção rápida pelos alunos |
| RQ04 | Alta disponibilidade | M | Garante acesso constante aos protocolos |
| RQ05 | Responsividade mobile | M | A maioria dos alunos acessará via celular |

---

# 🚀 14. Requisitos da Primeira Versão

| Ordem | ID | Requisito | Por que deve estar na primeira versão? |
|---:|---|---|---|
| 1 | RF01 | Abertura de chamados | Permite ao aluno relatar seu problema |
| 2 | RF02 | Acompanhamento de status | Dá visibilidade imediata ao protocolo |
| 3 | RF03 | Painel de atendimento da secretaria | Possibilita a triagem e resposta interna |
| 4 | RQ02 | Segurança e LGPD | Protege os dados dos estudantes |
| 5 | RQ05 | Responsividade mobile | Garante acesso fácil por smartphones |

---

# ⏭️ 15. Requisitos para Versões Futuras

| ID | Requisito | Motivo para adiar | Impacto |
|---|---|---|---|
| RF04 | Base de Conhecimento / FAQ | Pode ser inserido após a estabilização dos fluxos básicos | Médio |
| RF05 | Notificações automáticas avançadas | Exige configuração de servidor de disparo de e-mails/push | Médio |
| RF06 | Relatórios gerenciais detalhados | Demanda maior volume histórico de dados operacionais | Baixo |

---

# 🔍 16. Revisão por Pares

**Grupo responsável pela revisão:** A definir após a realização da revisão por pares.

| ID do requisito | Problema encontrado | Sugestão de melhoria |
|---|---|---|
| RF01 | Definir tamanhos máximos de arquivos | Especificar limites claros para upload de anexos |
| RF02 | Padronizar os nomes dos status | Definir estados fixos (Aberto, Em análise, Concluído) |
| RQ01 | Medir requisições sob estresse | Realizar testes com concorrência simulada de usuários |

---

# ✅ 17. Checklist de Qualidade dos Requisitos

- [x] Os requisitos estão completos?
- [x] Os requisitos estão corretos em relação às necessidades?
- [x] Cada requisito representa uma capacidade ou característica?
- [x] Os requisitos são necessários?
- [x] As dependências de viabilidade foram identificadas?
- [x] Todos possuem prioridade?
- [x] Termos ambíguos foram reduzidos?
- [x] Os requisitos podem ser verificados ou testados?
- [x] A fonte ou stakeholder está identificado?
- [x] As necessidades estão relacionadas aos requisitos?
- [x] Os requisitos de qualidade são mensuráveis sempre que possível?
- [x] As prioridades MoSCoW possuem justificativa?
- [ ] A revisão por outro grupo ainda deverá ser realizada.

---

# 💭 18. Reflexão do Grupo

## 18.1 Qual requisito gerou mais discussão durante o levantamento? Por quê?

> O requisito de notificações automáticas gerou debate, pois embora seja ótimo para a experiência do usuário, ele adiciona complexidade técnica na infraestrutura de envio que poderia atrasar a entrega da primeira versão.

---

## 18.2 Qual necessidade inicialmente parecia simples, mas gerou vários requisitos?

> A necessidade de anexar documentos parecia simples, mas exigiu desdobramentos sobre segurança de dados (LGPD), limites de tamanho e formatos aceitos para evitar falhas no sistema.

---

## 18.3 O grupo identificou algum requisito implícito durante a discussão?

> Sim. A responsividade para dispositivos móveis (celulares) surgiu como implícita e fundamental, visto que grande parte dos estudantes prefere resolver demandas acadêmicas diretamente pelo smartphone.

---

## 18.4 Qual requisito foi mais difícil de priorizar utilizando MoSCoW? Por quê?

> A seção de FAQ / Autoatendimento foi difícil de posicionar. Ela reduz drasticamente o trabalho da secretaria, mas não impede diretamente que um aluno abra um chamado urgente, por isso ficou como Should Have.

---

## 18.5 Houve algum requisito inicialmente considerado Must que mudou de prioridade?

> Sim. Os relatórios gerenciais avançados para a administração começaram como Must Have, mas foram reclassificados para Could Have para focar os esforços iniciais na experiência de ponta do estudante e no atendimento básico.

---

# 📝 19. Conclusão

**Conclusão:**

> O projeto FaculResolve aborda diretamente a burocracia e a falta de centralização nos canais de suporte acadêmico da instituição. Os principais beneficiados são os alunos, que ganham transparência e agilidade, e a secretaria, que otimiza sua operação interna.
>
> A aplicação da técnica MoSCoW permitiu focar a primeira versão nas funcionalidades essenciais de abertura, rastreio e resposta de chamados, garantindo segurança via LGPD e acessibilidade móvel. As melhorias de automação e relatórios avançados foram planejadas para versões futuras.

---

# 📦 Entregável

O repositório apresenta:

- [x] Identificação do projeto e dos integrantes;
- [x] Descrição do problema;
- [x] Objetivo do projeto;
- [x] Identificação dos stakeholders;
- [x] Levantamento das necessidades;
- [x] Requisitos funcionais essenciais;
- [x] Requisitos de qualidade mensuráveis;
- [x] Restrições e regras de negócio;
- [x] Rastreabilidade entre necessidades e requisitos;
- [x] Priorização utilizando MoSCoW;
- [x] Definição dos requisitos da primeira versão;
- [x] Reflexão e conclusão do grupo;
- [ ] Revisão por pares.

---

**Disciplina:** Análise e Projetos de Sistema  
**Projeto:** FaculResolve  
**Profª:** Kadidja Valéria  
**Repositório:** [GitHub — APS](https://github.com/Lucca143/APS-Analise-De-Projetos-E-Sistemas)
