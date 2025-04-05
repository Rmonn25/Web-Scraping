# Web Scraper Empresas Certificadas B

Este projeto foi desenvolvido por mim durante meu trabalho na empresa onde atuo, com o objetivo de automatizar a coleta de dados de empresas certificadas no site oficial da B Corporation. Utilizei Python + Selenium para realizar esse processo de forma eficiente e automática, resultando na extração de mais de 9 mil registros.

## Objetivo

Automatizar a navegação e extração de informações do diretório de empresas certificadas B Corp, coletando dados relevantes de cada empresa e salvando em uma planilha Excel.

## O que o código faz

- Acessa o site oficial da B Corporation
- Percorre todas as páginas do diretório de empresas
- Clica em cada empresa para abrir sua página individual
- Coleta os seguintes dados:
  - Nome da empresa
  - Localização
  - Data do certificado
  - Indústria
  - Setor
  - Tipo de operação
  - Site da empresa
  - Descrição/Missão
- Retorna para a página inicial e continua com a próxima empresa
- Após a coleta completa (mais de 9 mil empresas!), os dados são organizados em uma tabela (pandas.DataFrame)
- Exporta os dados para um arquivo Excel .xlsx

## Tecnologias Utilizadas

- Python
- Selenium
- Pandas
- WebDriver (Chrome)

## Saída

Ao final do processo, o script gera um arquivo chamado: "Empresas_B.xlsx" contendo todos os dados extraídos de forma organizada.

## Como usar

Instale os pacotes necessários:
pip install selenium pandas

## Observações

Esse codigo serve para qualquer ocasisão de Web Scraper basta apenas ajustar para cada ocasião que seja necessario!

