# CUSTOMER & MEDIA ANALYTICS

![plot](./images/rentacar.png)
Ilustração por Abhishek.

## DESAFIO 1: ANÁLISE DE CHURN EM ALUGUÉIS DE CARRO
#### Contexto: Validação da hipótese “O churn de novos clientes é maior do que o churn de clientes ativos”.
Com frequência, o indicador de churn é relacionado ao 'downgrade' ou cancelamento de uma assinatura. Nesse case, o negócio da empresa é aluguéis de carros, onde existe um contrato em que o seu encerramento é bem definido. Dessa forma, a grande questão do desafio é encontrar uma metodologia para se mensurar o churn dos clientes ativos e o churn dos clientes novos.

A autonomia dada no case técnico faz com que seu problema tenha várias resoluções. A metodologia utilizada nessa análise é verificar se os clientes que alugaram carros em um ano, voltaram a alugar no ano seguinte. Essa métrica caracterizará o Churn de Clientes ativos. Da mesma forma, será analisado se os novos clientes conquistados em um ano, voltaram a alugar carros no ano que o sucede. Aqui, temos o Churn de Clientes Novos.

Portanto, um cliente que alugou um veículo pela primeira vez em 2015 e só voltou a alugar novamente em 2019, será considerado como um cliente novo, ou reconquistado.

Encontrados os churnes de cada ano, é feito uma média do churn de ativos e do churn de novos nesse período analisado. Finalmente, as métricas são comparadas a fim de se aceitar ou rejeitar a hipótese.

Os passos utilizados para validar a hipótese foram:

- 0.0 Importações
  - Bibliotecas, funções de suporte e dataset.
- 1.0 Descrição dos Dados
  - Verificação da tipagem de dados e valores faltantes.
- 2.0 Modelagem de Dados
  - Manuseio para a obtenção da taxa de churn anual de clientes ativos e novos.
- 3.0 Conclusão
  - Consolidação dos resultados, teste de normalidade, análise de correlação e formas de se diminuir o churn de novos clientes.

Durante todo o notebook Churn.ipynb os códigos foram comentados para que ficasse mais claro o que estava sendo executado.

_________________________


![plot](./images/businessmeeting.jpg)
Ilustração por Unblast.

## DESAFIO 2: INTERVALOS DISPONÍVEIS EM DUAS AGENDAS
#### Contexto: Encontrar quais horários disponíveis duas pessoas teriam em comum para fazerem uma reunião.
Neste desafio, foi utilizado o próprio exemplo dado na questão para desenvolver o meu código. Como primeiro ato, foram encontrados os intervalos que a pessoa A teria para fazer uma reunião de 30 minutos. Em seguida, foi feito o mesmo para a pessoa B. Finalmente, é realizado um cruzamento dos horários disponíveis para encontrar quais aqueles que são comuns para as duas agendas.

Esse desafio poderia ter sido resolvido de muitas formas, mas tentei utilizar meu raciocínio lógico, de uma forma simples e mais clara.

Os passos utilizados:

- 0.0 Importações
- 1.0 Definindo o tempo da reunião
- 2.0 Encontrando intervalos disponíveis
  - 2.1 Pessoa A
  - 2.2 Pessoa B
  - 2.3 Intervalos disponiveis em ambas as agendas

A resolução está no arquivo Agendas.ipynb.





