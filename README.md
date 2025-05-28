# DIO - Trilha .NET - Banco de Dados
www.dio.me

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de banco de dados, da trilha .NET da DIO.

## Contexto
Você é responsável pelo banco de dados de um site de filmes, onde são armazenados dados sobre os filmes e seus atores. Sendo assim, foi solicitado para que você realize uma consulta no banco de dados com o objetivo de trazer alguns dados para análises.

## Proposta
Você precisará realizar 12 consultas ao banco de dados, cada uma retornando um tipo de informação.
O seu banco de dados está modelado da seguinte maneira:

![Diagrama banco de dados](Imagens/diagrama.png)

As tabelas sao descritas conforme a seguir:

**Filmes**

Tabela responsável por armazenar informações dos filmes.

**Atores**

Tabela responsável por armazenar informações dos atores.

**Generos**

Tabela responsável por armazenar os gêneros dos filmes.

**ElencoFilme**

Tabela responsável por representar um relacionamento do tipo muitos para muitos entre filmes e atores, ou seja, um ator pode trabalhar em muitos filmes, e filmes
podem ter muitos atores.

**FilmesGenero**

Tabela responsável por representar um relacionamento do tipo muitos para muitos entre filmes e gêneros, ou seja, um filme pode ter mais de um gênero, e um genêro pode fazer parte de muitos filmes.

## Preparando o banco de dados
Você deverá executar o arquivo **Script Filmes.sql** em seu banco de dados SQL Server, presente na pasta Scripts deste repositório ([ou clique aqui](Script%20Filmes.sql)). Esse script irá criar um banco chamado **Filmes**, contendo as tabelas e os dados necessários para você realizar este desafio.

## Objetivo
Você deverá criar diversas consultas, com o objetivo de retornar os dados a seguir. Abaixo de cada pedido tem o retorno esperado. O seu retorno deve ser igual ao da imagem.

## 1 - Buscar o nome e ano dos filmes

![image](https://github.com/user-attachments/assets/0c7cbcec-4c35-485a-9ed8-f13704955c16)

## 2 - Buscar o nome e ano dos filmes, ordenados por ordem crescente pelo ano

![image](https://github.com/user-attachments/assets/3280ea72-f59c-46ce-8790-631b61633c8d)

## 3 - Buscar pelo filme de volta para o futuro, trazendo o nome, ano e a duração

![image](https://github.com/user-attachments/assets/49543280-6c79-4e94-99cd-c53dad4a9ccf)

## 4 - Buscar os filmes lançados em 1997

![image](https://github.com/user-attachments/assets/8212af85-1605-497e-ae69-01f8f5e0f952)

## 5 - Buscar os filmes lançados APÓS o ano 2000

![image](https://github.com/user-attachments/assets/3dc917f0-88d7-4cc0-a8cf-bbb61f75d3d3)

## 6 - Buscar os filmes com a duracao maior que 100 e menor que 150, ordenando pela duracao em ordem crescente

![image](https://github.com/user-attachments/assets/fcbe76c3-64df-4f81-a335-45bb08288edf)

## 7 - Buscar a quantidade de filmes lançadas no ano, agrupando por ano, ordenando pela duracao em ordem decrescente

![image](https://github.com/user-attachments/assets/7d6e7772-92fe-47cf-a9d9-c06a6afc2377)


## 8 - Buscar os Atores do gênero masculino, retornando o PrimeiroNome, UltimoNome

![image](https://github.com/user-attachments/assets/a9dc04d6-108b-427c-9171-3bb4ae2564ce)

## 9 - Buscar os Atores do gênero feminino, retornando o PrimeiroNome, UltimoNome, e ordenando pelo PrimeiroNome

![image](https://github.com/user-attachments/assets/79f97512-c506-4df9-b904-a0fb599007ce)

## 10 - Buscar o nome do filme e o gênero

![image](https://github.com/user-attachments/assets/7af7500c-2a01-4ab0-8bb3-49cfcd829853)

## 11 - Buscar o nome do filme e o gênero do tipo "Mistério"

![image](https://github.com/user-attachments/assets/5e16b370-8bdb-4f0e-801c-930786260492)

## 12 - Buscar o nome do filme e os atores, trazendo o PrimeiroNome, UltimoNome e seu Papel

![image](https://github.com/user-attachments/assets/19292add-0f52-4a80-948a-3f3083188bd6)

