1. Processo escolhido

Cenário A - Conciliação bancária diária

O processo consiste em comparar o extrato bancário em formato .csv com as baixas registradas no sistema ERP.

A comparação será feita usando:

- CNPJ

- Valor da transação

2. O processo pode ser automatizado?

Sim.
O processo é adequado para RPA porque: Ele é realizado diariamente, possui regras claras, usa dados estruturados,
não possui tarefas variadas (e sim mais repetitivas), e não depende de decisão subjetiva.

3. Regras do processo

O robô deverá: 
//
3.1. Baixar o extrato bancário.

3.2. Ler o arquivo .csv.

3.3. Acessar o sistema ERP.

3.4. Consultar as baixas do período.

3.5. Comparar CNPJ e valor.

3.6. Identificar os registros que correspondem.

3.7. Separar os registros que possuem divergências.

3.8. Gerar um resultado da conciliação.

3.4. Entradas
//

5. Saídas

Registros conciliados.

Registros com divergências.

Relatório com o resultado.

6. Possíveis erros

Alguns problemas podem acontecer:
//
Arquivo .csv não encontrado, arquivo com formato incorreto, CNPJ não encontrado no ERP, valor diferente entre o banco e o ERP, ou sistema ERP indisponível.

Quando ocorrer uma dessas situações, o robô deve registrar o erro e deixar o caso para análise!
//
7. Avaliação

As regras estão claras o suficiente, com dados estruturados e processos repetitivos.
A Necessidade de decisão humano está baixa, e por fim, a viabilidade para RPA está adequada.

8. Conclusão

O robô pode realizar as tarefas repetitivas de leitura, consulta e comparação dos dados. Os casos que apresentarem erros ou divergências podem ser analisados por um funcionário. 