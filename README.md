## Análise Exploratória: O Que Torna um Filme Bem Avaliado no Rotten Tomatoes?

Este repositório contém uma análise exploratória de dados realizada em Python, com o propósito de investigar os fatores que contribuem para que um filme seja bem avaliado no renomado site de críticas de cinema, Rotten Tomatoes. A análise se baseia na extração de informações relevantes do site e na aplicação de técnicas de processamento e visualização de dados.

### Contexto
O Rotten Tomatoes é uma plataforma amplamente reconhecida para avaliações e críticas de filmes. Entender o que torna um filme bem avaliado neste site pode fornecer insights valiosos para a indústria cinematográfica, cineastas e amantes do cinema.

### Objetivos
Os principais objetivos desta análise exploratória são:

* Identificar as métricas de avaliação mais influentes no Rotten Tomatoes.
* Analisar a correlação entre as avaliações de críticos e do público.
* Investigar o impacto de gênero, elenco, direção e orçamento na avaliação dos filmes.

### Ferramentas Utilizadas
Para atingir esses objetivos, utilizamos uma variedade de ferramentas e bibliotecas em Python, incluindo:

Jupyter Notebook
Pandas
NumPy
Matplotlib

### Resultados
1. Relação entre notas: Existe uma tendência linear entre as notas da crítica e as notas do público, com algumas exceções em que as notas são inversas, indicando que, em geral, quando a crítica avalia positivamente um filme, o público também tende a fazê-lo. No entanto, existem alguns outliers.

2. Avaliação de palavras nos títulos: Palavras como "Movie," "Star," "Wars," "Man," "Story," "Love" são comuns em títulos de filmes. No entanto, quando analisamos os filmes mais bem avaliados pela crítica, surgem palavras diferentes, como "Woman," "King," "Galaxy," e "dark". No caso dos filmes mais bem avaliados pelo público, as palavras incluem "Episode," "King," "Avenger," e "Guy".

3. Gênero: Gêneros como Documentário, Ação, Anime e Ficção Científica são populares tanto na quantidade geral de filmes quanto nos filmes mais bem avaliados. O gênero Mistério e Terror se destaca nas notas da crítica, enquanto Aventura é mais popular entre o público em geral.

4. Valor de bilheteria: Não há uma conclusão definitiva sobre a relação entre a bilheteria e as avaliações, pois embora alguns filmes de alta bilheteria recebam altas notas, há uma variação considerável.

5. Diretores: Alguns diretores, como Steven Spielberg, Hayao Miyazaki, Anthony Russo e Joe Russo, obtêm boas avaliações tanto da crítica quanto do público. No entanto, Steven Spielberg tem a maior quantidade de filmes bem avaliados pela crítica, enquanto Guy Ritchie recebe boas avaliações do público.
