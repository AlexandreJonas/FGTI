# Entrega 1

# Visão do produto:

## Contexto Do Produto:

Sistema de Controle e Monitoramento de Pequenos Serviços

Aplicação web responsiva para empreendedores que trabalham com serviços como salões de beleza, tatuagem, aulas particulares, manutenção técnica, etc. com funcionalidades como cadastro e visualização de agendamentos, responsável pelo serviço, satisfação e pagamento do cliente integradas em uma única base de dados de fácil acesso.

## Objetivo:

Desenvolver um sistema de agendamento online simples integrado. Voltado para pequenos negócios que, por exemplo, prestam serviços com hora marcada, o intuito desse serviço é otimizar a gestão do tempo, melhorar a experiência do cliente e reduzir quaisquer possíveis falhas ou problemas de comunicação nos agendamentos.

## Motivação:

Muitos pequenos empreendedores ainda dependem de métodos manuais para realizar o agendamento de seus serviços — como cadernos, agendas físicas ou troca de mensagens por WhatsApp sem controle. Aumentando o risco de problemas de comunicação, esquecimentos e retrabalho. Além disso, ao se usar um serviço com maior controle e organização, é possível também otimizar mais o tempo dos empreendedores a um custo menor.

# Project Model Canvas:

![Project Model Canvas](/ProjectModelCanvas.png)

# Personas Mapeadas

## Persona 1

**Nome:**  Roberto

**Cargo / Função:** Dono de barbearia com 3 funcionários

**Empresa (empresa onde o Persona atua, caso haja – pode ser fictícia):** Beto’s

**Gênero:** Masculino

**Formação/Educação:** Ensino médio completo

**Mídias (usadas pelo Persona descrito):** WhatsApp, Instagram, TikTok

**Objetivos (orientem-se por alguns dos benefícios e requisitos do PMC):** 

- Automatizar a agenda de cada profissional
- Permitir que o próprio cliente escolha o horário disponível
- Melhorar a organização e reputação do negócio

**Desafios (dificuldades e problemas enfrentados pelo Persona descrito):**

- Agenda compartilhada em papel causa confusões entre os barbeiros
- Perda de tempo com atendimentos que não aparecem
- Dificuldade para organizar escala de horários dos funcionários

**Como a empresa pode ajudá-lo (como o produto ou serviço do grupo
pode atender os objetivos do Persona):** 

- Agendas separadas para cada profissional
- Clientes escolhem o horário online
- Redução de buracos de tempo e aumento de faturamento

## Persona 2

**Nome:**  Carolina

**Cargo / Função:** Esteticista Autônoma

**Empresa (empresa onde o Persona atua, caso haja – pode ser fictícia):** Carol

**Gênero:** Feminino

**Formação/Educação:** Ensino médio completo + cursos técnicos de estética e beleza

**Mídias (usadas pelo Persona descrito):** WhatsApp, Instagram, Facebook

**Objetivos (orientem-se por alguns dos benefícios e requisitos do PMC):** 

- Ter um sistema simples e prático para agendar atendimentos
- Enviar lembretes automáticos para os clientes
- Melhorar a produtividade

**Desafios (dificuldades e problemas enfrentados pelo Persona descrito):**

- Muitos agendamentos feitos por mensagens que se perdem
- Clientes esquecem do horário e / ou desmarcam em cima da hora

**Como a empresa pode ajudá-lo (como o produto ou serviço do grupo
pode atender os objetivos do Persona):** 

- Envia lembretes automáticos antes dos atendimentos
- Organiza os horários de forma clara, com notificações e opções de remarcação, perfeito para quem não possui familiaridade com softwares de gestão

## Persona 3

**Nome:**  Júlia

**Cargo / Função:** Professora Particular

**Empresa (empresa onde o Persona atua, caso haja – pode ser fictícia):** NA

**Gênero:** Feminino

**Formação/Educação:** Licenciatura em Letras

**Mídias (usadas pelo Persona descrito):** YouTube (para aulas), WhatsApp, Google Meet

**Objetivos (orientem-se por alguns dos benefícios e requisitos do PMC):** 

- Ter um link para agendamento automático
- Ter uma agenda organizada por dia e aluno

**Desafios (dificuldades e problemas enfrentados pelo Persona descrito):**

- Marca aulas por WhatsApp e às vezes confunde horários
- Precisa de um sistema para que alunos marquem sem depender dela
- Quer evitar perder tempo com remarcações manuais

**Como a empresa pode ajudá-lo (como o produto ou serviço do grupo
pode atender os objetivos do Persona):** 

- Fornece link personalizado para agendamentos
- Permite que alunos vejam horários disponíveis e agendem direto

# Entrega 2

# User stories:

### User Story 1

Como dono de negócio, desejo que meus clientes possam agendar horários online, para que eu não precise gerenciar manualmente minha agenda.

**Critérios de Aceitação**:

- O cliente consegue acessar um calendário com horários disponíveis.
- O cliente pode selecionar um horário, preencher nome/contato e confirmar o agendamento.
- O dono do negócio recebe uma notificação após o agendamento.
- O horário agendado fica bloqueado para outros usuários.

**Definition of Done (DoD)**:

- Tela de agendamento publicada e acessível por link.
- Dados do agendamento salvos corretamente no banco de dados.
- Notificações funcionando corretamente para o dono do negócio.
- Testes manuais realizados com sucesso em diferentes dispositivos.

### User Story 2

Como cliente, desejo que o sistema me envie lembretes automáticos, para reduzir o número de faltas e atrasos.

**Critérios de Aceitação**:

- Cliente recebe lembrete por e-mail ou WhatsApp antes do horário agendado.
- O horário e nome do profissional constam no lembrete.
- Os lembretes são enviados com uma antecedência configurável (ex: 1h, 24h).

**Definition of Done (DoD)**:

- Integração com serviço de envio (e-mail ou WhatsApp) implementada.
- Mensagens de lembrete personalizadas e testadas.
- Validação automática dos dados de contato.
- Registro de envios bem-sucedidos armazenado.
- Testes de envio concluídos com diferentes horários.

### User Story 3

Como dono de negócio, desejo que cada funcionário meu tenha sua própria agenda online, para que os clientes possam escolher com quem querem ser atendidos.

**Critérios de Aceitação**:

- O sistema permite cadastrar funcionários com suas agendas separadas.
- O cliente pode selecionar o funcionário antes de visualizar horários.
- Os agendamentos são atribuídos corretamente ao profissional selecionado.

**Definition of Done (DoD)**:

- Agendas individuais exibidas corretamente.
- Fluxo de agendamento testado com múltiplos profissionais.
- Validação de conflitos.

### User Story 4

Como dono de negócio, desejo que o sistema permita bloqueios de horários para folgas ou manutenção, para garantir uma organização eficiente.

**Critérios de Aceitação**:

- Profissionais podem bloquear horários diretamente na agenda.
- Os horários bloqueados não aparecem para os clientes.
- É possível desbloquear um horário manualmente.

**Definition of Done (DoD)**:

- Horários bloqueados ocultados da visualização pública.
- Testes realizados com bloqueios e desbloqueios.
- Interface validada com diferentes perfis de usuário.

### User Story 5

Como dono de negócio, desejo disponibilizar um link de agendamento para meus clientes, para que eles possam marcar agendamentos nos horários disponíveis sem precisar me contatar diretamente.

**Critérios de Aceitação**:

- O sistema gera um link público com acesso direto à agenda.
- O link pode ser compartilhado por WhatsApp, e-mail ou redes sociais.

**Definition of Done (DoD)**:

- Geração automática de link único funcional.
- Permissões de acesso validadas (visualização apenas).
- Testes feitos com compartilhamento do link em diferentes canais.
- Funcionalidade integrada com a agenda geral do sistema.

### User Story 6

Como dono de negócio, desejo poder reagendar ou cancelar agendamentos facilmente, para me adaptar a imprevistos sem complicações.

**Critérios de Aceitação**:

- Há opção de reagendar para outro horário ou cancelar.
- O cliente é notificado automaticamente sobre a alteração ou cancelamento.

**Definition of Done (DoD)**:

- Funcionalidade de escolha de novo horário funcionando sem erros.
- Mensagens de aviso ao cliente testadas e entregues corretamente.
- Logs de alterações armazenados no sistema.

### User Story 7

**Como dono de negócio**, desejo exportar os dados de agendamentos para planilhas, para que eu possa analisar informações e arquivar relatórios mensais.

**Critérios de Aceitação**:

- O sistema oferece um botão de exportação em formato .xlsx ou .pdf.
- Os dados exportados incluem: nome do cliente, serviço, profissional, data/hora do agendamento, status (realizado, cancelado, etc).
- O arquivo pode ser baixado diretamente pelo navegador.

**Definition of Done (DoD)**:

- Exportação funcionando com filtros por data e profissional.
- Testes manuais de abertura do arquivo em Excel e Google Planilhas.
- Verificação de integridade e precisão dos dados.

### User Story 8

**Como dono de negócio**, desejo receber feedback dos clientes após os atendimentos, para que eu possa melhorar meus serviços com base nas avaliações.

**Critérios de Aceitação**:

- O cliente pode avaliar com estrelas (1 a 5) e/ou comentário opcional.
- O feedback é armazenado e acessível ao dono do negócio.
- Os dados não são públicos, apenas internos.

**Definition of Done (DoD)**:

- Envio automático de link de avaliação após o agendamento.
- Armazenamento dos dados vinculado ao agendamento.

# Product Backlog **Distribuído**

**Considerando que o desenvolvimento do produto iniciar-se-á em 05/08/2024 e será trabalhado até 22/11/2024. O backlog foi distribuído em 7 sprints de duas semanas e 1 sprint de 9 dias úteis; dado os 79 dias úteis do cronograma.**

| User Story | Funcionalidade | Prioridade | Sprint |
| --- | --- | --- | --- |
| US01 | Cadastro de serviços e horários disponíveis | Alta | 1 |
| US01 | Visualização de agenda para o dono do negócio | Alta | 1 |
| US01 | Agendamento online por clientes | Alta | 2 |
| US03 | Cadastro de múltiplos profissionais com agendas individuais | Média | 3 |
| US03 | Seleção de profissional pelo cliente no momento do agendamento | Média | 4 |
| US06 | Reagendamento e cancelamento de compromissos | Média | 5 |
| US02 | Notificações para o dono do negócio sobre novos agendamentos | Média | 6 |
| US02 | Envio de lembretes automáticos por e-mail ou WhatsApp ao cliente | Baixa | 6 |
| US04 | Bloqueio de horários para folgas ou manutenção | Baixa | 7 |
| US08 | Feedback dos clientes após o atendimento | Baixa | 7 |
| US07 | Exportação de dados para planilhas | Baixa | 8 |

## Plano de Releases

### **Release 1 – MVP Funcional**

Atender à principal dor das personas (dificuldade em gerenciar agendamentos manualmente) e oferecer um fluxo de agendamento digital básico e funcional.

**Funcionalidades incluídas:**

- Cadastro de serviços e horários disponíveis
- Visualização da agenda pelo dono do negócio
- Cadastro de múltiplos profissionais com agendas individuais
- Agendamento online por clientes
- Seleção de profissional no momento do agendamento

**Data estimada de entrega:** Após a conclusão da Sprint 4

### **Release 2 – Gestão Avançada e Feedbacks**

Incrementar o sistema com funcionalidades voltadas à gestão de equipes além de feedbacks e análises.

**Funcionalidades incluídas:**

- Bloqueio de horários para folgas/manutenção
- Reagendamento e cancelamento de compromissos
- Envio de lembretes automáticos por WhatsApp e e-mail
- Coleta de feedback dos clientes após atendimento
- Exportação de dados para planilhas
- Notificações automáticas de confirmação
- Geração de link único para agendamento

**Data estimada de entrega:** Após a conclusão da Sprint 8

Roadmap Planejado – Agosto a Novembro 2024

|Sprint |	Período |	Entregas-Chave |	Release |
| --- | --- | --- | --- |
|Sprint 1 |	05/08 – 16/08 |	Cadastro de serviços + Visualização da agenda |	
|Sprint 2 |	19/08 – 30/08 |	Agendamento online pelo cliente	|
|Sprint 3	| 02/09 – 13/09 |	Cadastro de profissionais com agendas separadas |	
|Sprint 4 |	16/09 – 27/09 | Escolha do profissional pelo cliente |	Release 1.0 |
|Sprint 5 |	30/09 – 11/10	| Reagendamento e cancelamentos	|
|Sprint 6 |	14/10 – 25/10	| Notificações + Lembretes automáticos |	
|Sprint 7 |	28/10 – 08/11	| Bloqueios de horário + Coleta de feedbacks |	
|Sprint 8	| 11/11 – 22/11	| Exportação de dados + testes e ajustes finais |	Release 2.0 |
