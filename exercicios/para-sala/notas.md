QA - Quality assurance

Vai assegurar a qualidade do software, produto, projeto através de testes, melhoria de processos, melhoria do software. 

Objetivo dos testes:
- garantir a entrega em acordo com a expectativa do cliente mantendo a credibilidade da empresa
- entregar com segurança protegendo informações sensíveis
- entregar com o menor número de erros possível

Benefícios dos testes:
- redução de bugs e erros (quanto mais cedo testar, mais rápido acha os bugs)
- melhoria de qualidade do software ()
- economia de tempo e recursos no longo prazo

Ciclo de vida dos testes
1. Análise: Definindo os requisitos para os testes
2. Planejamento: Definindo o plano de testes e ferramentas a serem utilizadas
3. Execução: Realização dos testes em acordo com o planejado
4. Relatório: Documentação dos testes realizados

Pirâmide de testes

Base da piramide - Teste unitário [Testa a menor parte possível do sistema - uma função, uma classe, etc.]
São usados para garantir que o código funcione de acordo com as especificações
Ex: Uma calculadora - Soma, Divisão, Subtração, Multiplicação - Cada uma cabe um teste unitário

Meio da piramide - Teste de integração [Testa o funcionamento entre as pequenas partes]
São usados para garantir que as diferentes unidades de software funcionam bem juntas
Ex: Uma calculadora - Testar todas as funções juntas 

Topo da piramide - E2E Testing (teste de ponta a ponta, teste de aceitação)
Teste de ponta a ponta, simulando o uso do cliente, testar o projeto todo.
São usados para garantir que o software esteja funcionando de acordo com as especificações do projeto e necessidades do usuário
Último teste, teste mais caro. É melhor achar lá do que no usuário. Mas é muito melhor achar no teste unitário.

Boas práticas de testes unitários
- Nova funcionalidade = novos testes
  Ao construir uma nova funcionalidade, construir um teste para essa funcionalidade. Garante que novas funções não quebrem o software.

- Crie testes simples
  Testes devem ser curtos e específicos para garantir que o comportamento esperado da função ou classe está ocorrendo corretamente

- Executar testes com frequência

Unittest (ver no slide depois)

TDD - Test Driven Development

Cenários de teste
Prever possíveis falhas no código para testar estas diferentes situações

Code coverage - o quanto do código está sendo testado 

Test coverage - quais são os tipos de testes que estão sendo realizados
