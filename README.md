# analista-de-dados
PostgreSQL, Python, Consulta SQL e soma de dados
## Objetivo
- Gerar um novo relatório de pagamento dos afiliados.
- Calcular a soma total de apostas do cliente no banco de dados de cada afiliado encontrado no arquivo CSV.
- Utilizando os totais das apostas e os dados da tabela limites, determinar a porcentagem aplicada ao pagamento final.
- Determine a porcentagem necessária para calcular o valor de acréscimo com base nas  informações fornecidas na tabela limites.
- Aplique a porcentagem encontrada ao valor na coluna "pagamentos" do CSV para obter o pagamento final.


## Resultado final
### Dados essenciais no relatório
```
ID de afiliado (affiliate_id) - CSV
ID do usuário (customer_id) - (obtida do banco de dados)
Valor do pagamento - CSV
Soma das apostas do cliente - (obtida do banco de dados)
Porcentagem do acréscimo - (calculada com base na tabela limits)
Pagamento final - (resultado da aplicação da porcentagem ao valor do pagamento do CSV)
```
