# Sistema de Controle de Atendimentos e Recepção (Client Care Center)

## Visão Geral

O sistema de controle de atendimentos e recepção tem o propósito de gerenciar eficientemente as interações entre os clientes e o suporte técnico, otimizando o processo de recepção e atendimento em um ambiente corporativo. O sistema permite que a recepcionista identifique rapidamente o cliente e a área de atuação do indivíduo que está chamando, direcionando a ligação para o analista de suporte disponível mais adequado.

## Funcionalidades


* **Identificação e Registro de Chamadas:** Quando um cliente liga, a recepcionista identifica e registra quem está chamando, a qual cliente pertence, e em que área de atuação.
* **Distribuição de Chamadas:** O sistema permite à recepcionista buscar um analista de suporte que trabalhe na área requisitada e que esteja disponível, para direcionar a chamada.
* **Gestão de Chamadas Não Atendidas:** Caso não haja analistas disponíveis, a recepcionista registra a chamada para retorno posterior, garantindo que todas as chamadas sejam atendidas.
* **Consulta e Finalização de Atendimentos:** O analista de suporte, ao receber a chamada, tem acesso ao histórico e pode adicionar informações após o atendimento. Analistas podem também consultar chamadas pendentes e assumi-las quando estiverem disponíveis.
* **Relatórios Diários para Gestão:** No final do dia, o gerente pode consultar relatórios detalhados sobre as chamadas realizadas, áreas mais procuradas, desempenho dos analistas, entre outros.

## Regras de Negócio


1. **Identificação do Cliente e Área de Atuação:** Fundamental para a correta alocação de recursos e especialistas para resolver ou tratar a demanda do cliente.
2. **Distribuição Baseada em Disponibilidade e Área de Especialidade:** Assegura que as chamadas sejam sempre direcionadas para o analista mais capacitado e disponível, otimizando o tempo de resposta e a eficiência do atendimento.
3. **Registro e Tratamento de Chamadas Não Atendidas:** Garante que nenhuma solicitação seja perdida, melhorando a satisfação do cliente.
4. **Acesso e Segurança:** O sistema é acessado mediante autenticação (email e senha), assegurando que apenas pessoal autorizado possa operar o sistema.

## Tecnologias Utilizadas

### Backend:
* PHP: Versão 8.3.6
* Laravel: Versão 11.1.1

## Frontend:
* Vue.js: Versão 4.3.6

## Banco de Dados:
* PostgreSQL