# Projeto de Análise de Big Data com PySpark

Este projeto realiza uma análise de dados de músicas usando PySpark, manipulando um conjunto de dados que contém informações sobre streams e popularidade de músicas em diversas plataformas, como Spotify, YouTube e TikTok. O objetivo é explorar as tendências de audição, identificar os artistas e álbuns mais populares, e gerar gráficos comparativos.

## Funcionalidades

- Configuração do ambiente do Apache Spark no Google Colab.
- Carregamento e pré-processamento de dados de um arquivo CSV.
- Limpeza e conversão de colunas para tipos adequados.
- Análise de dados, incluindo:
  - Total de streams por artista e por álbum.
  - Artistas com maior média de popularidade.
  - Músicas lançadas de 2020 a 2024 mais ouvidas.
  - Comparação de streams e visualizações entre artistas.

## Tecnologias Utilizadas

- **Apache Spark**: Framework para processamento de dados em larga escala.
- **PySpark**: Interface Python para o Apache Spark.
- **Pandas**: Biblioteca para manipulação de dados em Python.
- **Matplotlib**: Biblioteca para criação de gráficos em Python.

## Requisitos

- [Google Colab](https://colab.research.google.com/)
- Acesso à internet para baixar dependências e o arquivo CSV de dados.

## Estrutura do Código

O código é organizado em seções:

1. **Configuração do Ambiente**: Instalação do Java e do Spark, configuração das variáveis de ambiente.
2. **Leitura e Exibição de Dados**: Carregamento do arquivo CSV em um DataFrame e exibição dos dados.
3. **Limpeza e Conversão de Dados**: Conversão de colunas para os tipos apropriados e remoção de caracteres indesejados.
4. **Análises**:
   - Total de streams por artista.
   - Top 10 álbuns mais ouvidos.
   - Artistas com maior média de popularidade.
   - Músicas mais ouvidas lançadas nos últimos anos.
   - Comparação entre artistas (Bad Bunny, Taylor Swift e The Weeknd).
5. **Visualização de Dados**: Geração de gráficos comparativos das visualizações/streams.

## Como Executar o Código

1. Acesse o Google Colab e crie um novo notebook.
2. Cole o código no notebook.
3. Execute cada célula sequencialmente para configurar o ambiente, carregar os dados e realizar as análises.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
