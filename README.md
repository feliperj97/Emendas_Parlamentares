#Análise de Emendas Parlamentares

# Análise de Emendas Parlamentares

## Descrição

Este projeto consiste em um dashboard interativo desenvolvido no Power BI que realiza uma análise das emendas parlamentares no Brasil. O dashboard permite a visualização das emendas por região, parlamentar e outras métricas relevantes. Ele foi criado a partir de um dataset consolidado em formato CSV, que contém informações detalhadas sobre as emendas, como valores alocados, beneficiários e status.

## Motivação

As emendas parlamentares são um instrumento importante para a distribuição de recursos públicos, mas muitas vezes o acesso e entendimento dos dados sobre essas emendas é limitado. Este projeto visa oferecer um meio acessível e visual para que cidadãos e outros interessados possam entender melhor como esses recursos são distribuídos e quais áreas são mais beneficiadas.

## Estrutura do Projeto

- `dataset/emendas.csv`: Base de dados das emendas parlamentares no formato CSV, contendo informações como:
  - Identificador da emenda
  - Parlamentar responsável
  - Estado/Município beneficiado
  - Valor pago
  - Valor liquidado
  - Valor empenhado

- `dashboard.pbix`: Arquivo do dashboard no Power BI, que apresenta as análises e visualizações geradas a partir dos dados.

## Tecnologias Utilizadas

- **Ferramenta de Visualização**: Power BI
- **Formato dos Dados**: CSV

## Como Utilizar

1. Baixe o arquivo CSV (`dataset/emendas.csv`) e o arquivo do Power BI (`dashboard.pbix`).
2. Abra o arquivo `.pbix` no Power BI Desktop para visualizar e explorar o dashboard interativo.
3. Caso deseje atualizar ou modificar os dados, substitua o arquivo CSV pela nova versão com as alterações desejadas e atualize o Power BI para refletir as mudanças.

## Dados

Os dados utilizados no projeto foram coletados de fontes públicas e incluem as seguintes informações:

- Identificação das emendas parlamentares
- Nome parlamentar
- Estado, município e região beneficiado
- Valor das emendas
- Tipo da emenda (Individual, bancada, comissão)


## Dashboard

O dashboard desenvolvido no Power BI oferece as seguintes visualizações e análises:
- **Valor Total empenhado, pago e liquidade**: Filtro interativo por autor, funç~çao e subfunção da emenda
- **Distribuição Geográfica**: Mapa interativo mostrando a alocação de recursos por estado e município.(em desenvolvimento)
- **Análise por Parlamentar**: Comparativo de emendas por parlamentar
- **Alocação de Recursos**: Análise das áreas mais beneficiadas pelas emendas (saúde, educação, infraestrutura, etc.).(em desenvolvimento)
- **Evolução Temporal**: Visualização da evolução das emendas ao longo dos anos.(em desenvolvimento)

## Licença

Este projeto está disponível sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

## Contato

Caso tenha dúvidas ou sugestões, entre em contato:

- **Nome:** Felipe Lamim
- **E-mail:** fclamim@gmail.com
- **LinkedIn:** www.linkedin.com/in/felipe-lamim


