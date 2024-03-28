# Transposição de Linhas para Colunas em Arquivo CSV e Conversão para Excel

Este script em Python lê um arquivo CSV, transpõe as linhas para colunas, converte os dados para um arquivo Excel (XLSX) e adiciona um cabeçalho específico às colunas.

## Requisitos

- Python 3.x
- Bibliotecas:
  - `openpyxl`
  - `pandas`

## Funcionamento

1. **Obtenção da Data Atual:**
   - O script obtém a data atual e a formata no padrão YYYYMMDD.

2. **Leitura e Conversão do CSV para Excel:**
   - O script lê o arquivo CSV com o nome formatado pela data obtida.
   - Os dados do CSV são convertidos para um DataFrame do `pandas`.
   - Em seguida, os dados são escritos em um arquivo Excel (XLSX) com o mesmo nome do CSV.

3. **Adição de Cabeçalho ao Excel:**
   - Um cabeçalho específico é definido para as colunas do Excel.
   - O script carrega o arquivo Excel recém-criado usando `openpyxl`.
   - O cabeçalho é inserido na primeira linha da planilha.

4. **Salvamento do Excel com Cabeçalho:**
   - A planilha do Excel é salva com o novo cabeçalho.

5. **Remoção de Arquivos Temporários:**
   - Os arquivos temporários criados durante o processo são removidos do sistema.

## Utilização

1. Certifique-se de ter Python instalado no seu ambiente.
2. Instale as bibliotecas necessárias executando `pip install openpyxl pandas`.
3. Execute o script Python. Ele lerá o arquivo CSV, realizará as operações descritas e salvará o resultado no mesmo diretório.
4. Verifique os arquivos resultantes com os dados transpostos e convertidos para Excel.

Este script simplifica o processo de transpor linhas para colunas em um arquivo CSV e convertê-lo para Excel, fornecendo um cabeçalho específico para as colunas.
