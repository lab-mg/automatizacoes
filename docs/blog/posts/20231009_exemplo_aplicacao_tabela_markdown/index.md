---
draft: true
date: 2023-10-09
authors: [andrelamor]
comments: true
categories:
  - ferramentas - tabelas
---

# Exemplo de aplicação de tabela via markdown

| Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |

{{ read_csv('dados/sample-2.csv') }}

<!-- more -->

Demonstração de tabela[^1]

| ID | Nome ou breve descrição do robô                                                                                                                                                                                                                                                                                                   | Humano: número de ocorrências | Robô: número de ocorrências |
|----|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|-----------------------------|
| 1  | Baixa documentos do CRM, envia por e-mail e salva no sharepoint.                                                                                                                                                                                                                                                                  | 2                             | 30                          |
| 2  | Alimentação do EFD-REINF (INSS)                                                                                                                                                                                                                                                                                                   | 114                           | 114                         |
| 3  | elaboração e tramitação de documentos no SEI                                                                                                                                                                                                                                                                                      | 30                            | 200                         |
| 4  | geração guias FGTS                                                                                                                                                                                                                                                                                                                | 10                            | 150                         |
| 5  | Empenho, liquidação e pagamento - PTE (transporte escolar)                                                                                                                                                                                                                                                                        | 120                           | 1600                        |
| 6  | Regularização/transferência de patrimônio no SIAD                                                                                                                                                                                                                                                                                 | 200                           | 3000                        |
| 7  | Robô para consulta no SIAFI; Robô de empenho de RPV no SIAFI; Robô de   liquidação de RPV no SIAFI; Robô de Pagamento de RPV no SIAFI                                                                                                                                                                                             | 50                            | 150                         |
| 8  | Marcação consulta IPSEMG. Monitora o site até surgir uma   vaga/desistência. Quando aparece, ele marca a consulta.                                                                                                                                                                                                                | 1                             | 1                           |
| 9  | Transferência de patrimônio SIAD. A SEEMG compra milhares de equipamentos   e mobiliário para distribuição às escolas todos os anos e fazer a   transferência desse patrimônio para as escolas manualmente é muito demorado.   Este Robô é capaz de realizar a transferência de 2000 patrimônios a cada 20   minutos.             | 500                           | 48000                       |
| 10 | Pagamento de Folha. O realiza todo processo desde emissão de guias, e   pagamento. Construção em andamento.                                                                                                                                                                                                                       | 1                             | 1                           |
| 11 | Descentralização Financeira para Unidades da SEE. É realizada a   descentralização de todos os valores liquidados no dia anterior a certa de 80   unidades executoras. O robô recebe os arquivos do BO por email, cria uma   planilha de descentralização e realiza a descentralização, com um eficiente   tratamento de exceção. | 1                             | 10                          |
| 12 | Empenhos, liquidação e pagamentos diversos. O robô é capaz de realizar 7   pagamentos de uma única vez.                                                                                                                                                                                                                           | 100                           | 5000                        |
| 13 | Cadastramento solicitação e pedido de compras no Portal de Compras.   Estamos utilizando esse robô para cadastramento das solicitações e pedidos do   Trilhas.                                                                                                                                                                    | 50                            | 500                         |
| 14 | Robô de empenho de RPV                                                                                                                                                                                                                                                                                                            | 30                            | 100                         |
| 15 | Empenho de liquidação de RPVs                                                                                                                                                                                                                                                                                                     | 50                            | 170                         |
| 16 | Robô de pagamento de RPVs                                                                                                                                                                                                                                                                                                         | 40                            | 130                         |
| 17 | Robô de consulta no SIAFI                                                                                                                                                                                                                                                                                                         | 100                           | 350                         |

[^1]: configuração em https://squidfunk.github.io/mkdocs-material/reference/data-tables/