# Computacao em Nuvem
Professor: Pedro Pisa  
Aluno: Rodrigo Prado

# Lista de Exercícios
Documentação:
- Explicação do passo a passo utilizado no código:
Utilizei o colab e o spark para resolver os problemas apresentados. Como o dataset de 'customers_ratings.csv' é grande, eu preferi utilizar o spark para realizar as computações de merge, join, groupBy, devido ao ótimo processamento dessa tecnologia.
A explicação da resolução está descrito em cada questão

- Explicação de como executar o código do zero:
Para executar o notebook, voce vai precisar do colab, o arquivo do notebook 'ComputacaoEmNuvem-RodrigoPrado.ipynb' e os arquivos csv (movies e customers_ratings). Como foi utilizado o pyspark, é necessário fazer a instalação das dependencias, mas essa instalação já está no primeiro passo do notebook.

Passo-a-passo:
1. Acessar o colab, https://colab.research.google.com/
2. Abrir (Importar) o notebook 'ComputacaoEmNuvem-RodrigoPrado.ipynb'
3. Na seção 'Arquivos' do colab, criar uma pasta chamada 'data' 
4. Fazer o upload dos arquivos movies.csv e customers_ratings.csv na pasta 'data' (aguardar o upload completeo)
5. Executar o notebook.

O notebook está dividido em algumas seções: (1) Instalação e import de lisbs, (2) Leitura dos arquivos csv's e (3) resolução dos exercícios

Sobre os dados

O arquivo CSV 'movies' contém o identificador e o nome do filme. O arquivo 'customers_rating' contém informações sobre ID do cliente, nota dada ao filme, qual a data da avaliação e o ID do filme.

Descrição das colunas:

Base 1:  
ID do filme  
título e ano de lançamento  

Base 2:  
Cust_Id: ID do customer que fez a avaliação  
Rating: avaliação (nota)  
Date: data da avaliação  
Movie_Id: ID do filme  

Amostra:  
movies:  
1;(Dinosaur Planet, 2003)  
2;(Isle of Man TT 2004 Review, 2004)  
3;(Character, 1997)  

customers_rating:  
1488844;3.0;2005-09-06;1  
822109;5.0;2005-05-13;1  
885013;4.0;2005-10-19;1  

Nome do arquivo CSV:  
data/movies.csv  
data/customers_rating.csv  
Sobre as questões  

Base1 - Movies: https://drive.google.com/file/d/1gLsCjaMrL91ECdThq58cZAzB9tPxG18g/view?usp=sharing

Base2 - Ratings: https://drive.google.com/file/d/1C_T1w8fc7Oa8MeTo4LMTEcv90IfEOS-6/view?usp=sharing
