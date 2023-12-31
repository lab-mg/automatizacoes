---
comments: true
hide:
  - navigation
tags:
  - PAE
---

# Triagem de documentos SEI


## Informações gerais

| **Responsável**  | Alessandro Campos  |
| ----------- | ------------------------------------ |
| **E-mail**  | alessandro.campos@meioambiente.mg.gov.br |
| **Desenvolvedora**| Isabela Romancini  |
| **e-mail**       | isabela.romancini@planejamento.mg.gov.br|
| **Ferramenta**    | Power Automate Desktop |
| **Arquivo(s) auxiliar(es)**    | [PAE2.xlsx](./assets/Pae2.xlsx){:download="PAE2.xlsx"} |

## Funções desenvolvidas pelo robô

- Realiza pesquisa por número do documento SEI! e baixa o documento.
- Descompacta arquivos e os salva no computador.
- Verifica se há arquivos (PDF, shapefile e tif) corrompidos.
- Verifica se há arquivos com formatos que não são aceitos para o PAE: KML, MPK e MXD;
- Preenche planilhas de controle com as informações verificadas.

??? note "**Clique e veja o fluxo do robô**"

    ```mermaid
            --8<-- "docs/robos/pae-2/assets/fluxo.md"
    ```

--8<-- "docs/partials/modelo_robo/montando_seu_proprio_robo.md"

??? note "**Clique para copiar e colar**"

        --8<-- "docs/robos/pae-2/assets/codigo_fonte.txt"

!!! note "**Importante:**"

    Antes de executar este robô em especial, é importante seguir os seguintes passos:

    1. Verificar se a máquina em que o robô vai ser executado possui os seguintes programas instalados:
        - Microsoft Power Automate;
        - Extensão do Google Chrome ("Microsoft Power Automate" - sem ser o legacy);
        - 7-zip;
        - QGis.
    2. Criar planilha-base no Excel: "Número do processo SEI" na célula 1A, "Número do documento SEI" na 1B e "Status" na 1C;
    3. Alterar configurações da pasta "download" para baixar arquivos numa pasta separada;
    4. Configurar como padrão:
        - Abrir arquivos em PDF no Adobe Acrobat;
        - Abrir arquivos shapefile no QGis;
        - Descompactar arquivos no 7-zip.

--8<-- "docs/partials/modelo_robo/ajuda.md"
