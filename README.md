[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/IDEzcQ6G)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23610829)
# :checkered_flag: Supremus Service

Sistema Fullstack para gestão de fluxo e automação operacional de assistências técnicas especializadas.

## :technologist: Membros da equipe

Felipe Feitosa Teixeira - Engenharia de Computação.

## :bulb: Objetivo Geral
Profissionalizar o fluxo de atendimento de assistências técnicas através de uma solução robusta que automatiza a geração de documentos e monitora o laboratório em tempo real.

## :eyes: Público-Alvo
Proprietários, gerentes e técnicos de assistências técnicas e laboratórios de eletrônicos/informática.

## :star2: Impacto Esperado
Otimização do tempo de reparo, eliminação de falhas de comunicação via dashboard em tempo real e maior credibilidade profissional através de documentos padronizados.

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

* **Administrador (Dono/Chefe):** Acesso total ao sistema, relatórios financeiros e gestão de permissões.
* **Gerente:** Controle de equipes e atribuição de prioridades no dashboard.
* **Técnico:** Preenchimento de diagnósticos, atualização de status e emissão de orçamentos.
* **Cliente (Não logado):** Consulta pública de status da Ordem de Serviço.

> Tenha em mente que obrigatoriamente a aplicação deve possuir funcionalidades acessíveis a todos os tipos de usuário e outra funcionalidades restritas a certos tipos de usuários.

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

* **Acessíveis a todos:** Consulta rápida de status de OS e landing page institucional.
* **Restritas (Logados):** Check-in de equipamentos com máscaras dinâmicas, Dashboard Laboratorial em tempo real, Geração de PDFs (Recibos e Orçamentos) via pdf-lib e gestão de diagnósticos técnicos.

## :spiral_calendar: Entidades ou tabelas do sistema

* Ordem de Serviço (OS)
* Usuário
* Cliente
* Equipe de Trabalho


----

:warning::warning::warning: As informações a seguir devem ser enviadas juntamente com a versão final do projeto. :warning::warning::warning:


----

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:**

React.js, Tailwind CSS, Lucide React e pdf-lib.

**Backend:**

FastAPI (Python), Firebase Firestore (GCP) e Render (Hosting).


## :shipit: Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Ordem de Serviço (OS) | X |  X  |  X | X |
| Usuário | X |  X |  X | X |
| Cliente | X |  X |  X |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| POST | /registrar-os |
| GET | /listar-os |
| PUT | /atualizar-os/{id} |
| POST | /login |
