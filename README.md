# Análise Exploratória de Dados - Filmes Netflix dos Anos 90

## Sobre o Projeto
Este projeto analisa dados da Netflix, focando especificamente nos filmes lançados durante a década de 1990. O objetivo é realizar uma análise exploratória de dados para uma empresa de produção especializada em estilos nostálgicos.

## Projeto DataCamp
Este projeto faz parte de um estudo prático disponibilizado pela plataforma DataCamp, uma das principais plataformas de aprendizado de ciência de dados e análise de dados. O caso de estudo foi desenvolvido para proporcionar uma experiência hands-on com análise exploratória de dados reais da Netflix, permitindo a aplicação prática de conceitos de manipulação de dados e visualização usando Python.

## Conjunto de Dados
O projeto utiliza o arquivo `netflix_data.csv`, que contém as seguintes informações:

| Coluna | Descrição |
|--------|-----------|
| `show_id` | ID do programa |
| `type` | Tipo do programa |
| `title` | Título do programa |
| `director` | Diretor do programa |
| `cast` | Elenco do programa |
| `country` | País de origem |
| `date_added` | Data de adição à Netflix |
| `release_year` | Ano de lançamento na Netflix |
| `duration` | Duração do programa em minutos |
| `description` | Descrição do programa |
| `genre` | Gênero do programa |

## Objetivos da Análise
1. Identificar a duração mais comum dos filmes dos anos 90
   - Considerando 1990 como ano inicial
   - O resultado será armazenado como uma variável inteira `duration`

2. Contabilizar filmes de ação curtos dos anos 90
   - Filmes curtos são definidos como aqueles com menos de 90 minutos
   - O resultado será armazenado como uma variável inteira `short_movie_count`

## Requisitos
- Python
- Bibliotecas:
  - pandas
  - matplotlib

## Estrutura do Projeto
- `netflix_data.csv`: Arquivo com os dados da Netflix
- `notebook.ipynb`: Jupyter Notebook contendo a análise
- `redpopcorn.jpg`: Imagem ilustrativa do projeto