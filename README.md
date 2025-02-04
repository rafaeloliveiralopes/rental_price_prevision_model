# Introdução
## Sobre o Desafio
Este desafio tem por objetivo desenvolver um modelo de previsão de preços de aluguéis a partir do dataset oferecido pela empresa Indicium e avaliar o modelo
utilizando as métricas de avaliação que mais façam sentido para o problema.

## Questões que este desafio visa responder

- [x] 1- Faça uma análise exploratória dos dados (EDA), demonstrando as principais características entre as variáveis e apresentando algumas hipóteses de negócio relacionadas.
- [x] 2- Responda também às seguintes perguntas:
- a. Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?
- b. O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?
- c. Existe algum padrão no texto do nome do local para lugares de mais alto valor?
- [x] 3- Explique como você faria a previsão do preço a partir dos dados.
- [x] 4- Quais variáveis e/ou suas transformações você utilizou e por quê?
- [x] 5- Qual tipo de problema estamos resolvendo (regressão, classificação)?
- [ ] 6- Qual modelo melhor se aproxima dos dados e quais seus prós e contras?
- [x] 7- Qual medida de performance do modelo foi escolhida e por quê?
- [x] 8- Supondo um apartamento com as seguintes características:

{'id': 2595,
 'nome': 'Skylit Midtown Castle',
 'host_id': 2845,
 'host_name': 'Jennifer',
 'bairro_group': 'Manhattan',
 'bairro': 'Midtown',
 'latitude': 40.75362,
 'longitude': -73.98377,
 'room_type': 'Entire home/apt',
 'minimo_noites': 1,
 'numero_de_reviews': 45,
 'ultima_review': '2019-05-21',
 'reviews_por_mes': 0.38,
 'calculado_host_listings_count': 2,
 'disponibilidade_365': 355}
 
Qual seria a sua sugestão de preço?

## Como executar o projeto

Este projeto foi executado com o uso do JupyterLab no ambiente Anaconda Navigator para a distribuição Linux.
Você pode executar este projeto com a versão online do JupyterLab ou Jupyter Notebook: https://jupyter.org/try
Mas se desejar esperimentar o uso no ambiente local, poderá fazer o download de instalação de acordo com o sistema operacional de sua máquina clicando <a href="https://docs.anaconda.com/anaconda/install/" target="_blank" rel="noopener noreferrer">aqui</a>! 

Após concluir a instalação digite no terminal - se estiver usando uma distribuição Linux:

```
anaconda-navigator
```
Sugiro criar um novo ambiente para manter o seu ambiente de teste isolado dos outros ambientes. Pois, isso vai previnir o conflito de versões de bibliotecas instaladas.
![anaconda-navigator](https://github.com/user-attachments/assets/d4a9ebcd-5cbd-4cee-b9e4-a8725848f6af)

### Ecolha o Jupyterlab ou o Jupyter Notebook
Eu particularmente prefiro o Jupyterlab porque é possível visualizar as pastas e arquivos que estão sendo criados ou utilizados.

### Clone este repositório usando o terminal de sua preferência
```
git clone https://github.com/rafaeloliveiralopes/rental_price_prevision_model.git
```
### Use o terminal para navegar até o repositório baixado
```
cd nome-do-repositorio-clonado
```

### Instale as dependências usadas neste projeto
Este projeto possui um documento chamado requirements.txt. Todas as bibliotecas e frameworks com as versões correspondentes para este projeto, serão instaladas no seu ambiente com o comando abaixo.
```
pip install -r requirements.txt
```
### Dê dois cliques no arquivo `ret_price_model_pred.ipynb`
Após abrir o notebook execute as células com o atalho `shift+enter` ou se desejar executar todas as cécluas de uma vez, clique na aba run (executar) e escolha executar todas as celulas.

## Contato

Dúvidas ou sugestões? Entre em contato:

- **Email:** rafaellopes.dev@gmail.com
- **LinkedIn:** [Rafael Lopes](https://www.linkedin.com/in/rafael-lopes-desenvolvedor-fullstack/)
