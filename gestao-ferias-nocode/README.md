# 🏖️ Sistema de Gestão de Férias (No-Code)
 ## 📝 Descrição do Projeto
Este projeto consiste em uma plataforma para gerenciamento de solicitações de férias, desenvolvida utilizando a ferramenta No-Code **Bubble**. O sistema permite que colaboradores solicitem períodos de descanso enquanto gestores revisam e aprovam os pedidos através de um fluxo de governança estruturado.

O foco do projeto foi implementar regras de privacidade robustas e workflows automatizados para garantir a segurança dos dados e a fluidez do processo administrativo.

---
### 🔗 Links do Projeto
* **[Aplicação em Produção (Bubble)](https://pedro200508441.bubbleapps.io/version-test?debug_mode=true)**
* **[Rascunho do Banco de Dados (Notion)](https://www.notion.so/Gest-o-de-Ferias-34db3ba6b3d3808caffac3b2df66d5e4?source=copy_link)**

---

 ## 🚀 Tecnologias e Governança
* **Plataforma:** Bubble (No-Code) 
* **Segurança de Dados:** Implementação de *Privacy Rules* para o tipo `LeaveRequest`, garantindo que apenas usuários autorizados e gestores diretos visualizem dados sensíveis.
* **Documentação de Workflow:** Uso de notas detalhadas no editor para mapear a lógica de cada botão e funcionalidade.

 ## ⚙️ Workflows e Funcionalidades
O sistema utiliza processos automatizados para gerenciar as solicitações:

* **Cálculo Automático:** A lógica de gravação de pedidos inclui o cálculo de dias úteis entre as datas selecionadas.
* **Validação de Saldo:** O sistema valida se o usuário possui saldo disponível antes de permitir a abertura do formulário de solicitação.
* **Fluxo de Aprovação:** Gestores possuem popups dedicados para revisar datas e detalhes antes de tomar uma decisão de aprovação ou rejeição.

 ## 📊 Estratégia de Saída e Portabilidade
Como parte da boa prática de desenvolvimento, foi definida uma estratégia de saída para evitar o *vendor lock-in*:
* **Exportação via API:** Habilitação da *Data API* para exportar facilmente tabelas de usuários, solicitações e saldos de férias.
* **Documentação Logística:** As notas criadas nos workflows permitem replicar a responsabilidade de cada componente em outras plataformas, caso necessário.

 ## 🔧 Como Executar
1. Acesse o link da aplicação no [Bubble](https://pedro200508441.bubbleapps.io/version-test?debug_mode=true).
2. Utilize as credenciais de teste para navegar entre os perfis de Colaborador e Gestor.
3. Consulte o rascunho no [Notion](https://www.notion.so/Gest-o-de-Ferias-34db3ba6b3d3808caffac3b2df66d5e4?source=copy_link) para entender a arquitetura original do banco de dados.

---
[Voltar ao início](https://github.com/Pedro234L/portfolio-Pedro-Martins-Rodrigues-Alves)
