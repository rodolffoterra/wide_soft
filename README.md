# wide_soft


Data: 22 de Janeiro de 2021


![Wide Pay](https://raw.githubusercontent.com/rodolffoterra/wide_soft/main/WidePay.png)


## 1 Objetivo

O objetivo deste documento é definir as regras para implementação do desafio no intuito de testar os conhecimentos do candidato, analisar a qualidade da entrega e apoiar no
enquadramento entre júnior, pleno e sênior.


## 2 Tecnologia

Não existem exigências quanto às tecnologias, todavia, orientamos que, caso sejam desenvolvidos scripts ou aplicações, sejam usadas as linguagens PHP, javascript, R ou Python. O Banco de dados pode ser no formato do excel, mysql ou outro relacional ou não relacional. As bibliotecas para geração de gráficos ficam à critério do candidato. Sugerimos utilizar as tecnologias descritas nos requisitos e também nos conhecimentos desejáveis descritos no anúncio.

## 3 Diretrizes

Caso o candidato opte por desenvolver uma aplicação ou scprits para busca de dados, orientamos que utilize as boas práticas do desenvolvimento da linguagem escolhida (PHP, javascript, R ou Python), observando-se padrões de projeto quando necessário, simplicidade da codificação, padrões arquiteturais, raciocínio lógico, etc.
Não é necessário desenvolver o frontend, porém, caso o faça, não elabore telas complexas.
Você tem total liberdade no desenvolvimento da solução, lembrando apenas que estamos focando nas informações de valor agregado levantadas durante o desafio e não em User interface.

Você não precisa concluir o desafio caso o tempo não possibilite. Também não é necessário analisar todas as hipóteses possíveis. Apenas sugerimos que as análises feitas realmente agreguem valor e transformem dados em informações úteis à tomada de decisão. Melhor uma análise bem elaborada do que várias que apresentem informações irrelevantes ou
inconclusivas.

## 4 Conclusão do Desafio

Para conclusão do desafio, esperamos receber:

● Acesso ao banco de dados usado e normalizado para o desafio.

● Acesso à análise realizada, scripts, dahboards, e todos os documentos gerados.

● Acesso à sua conclusão para a análise realizada;

● Se realizado desenvolvimento de aplicação, esperamos receber instruções para acesso ao sistema na plataforma cloud escolhida pelo candidato: AWS, Azure, GCP,
Linode, DigitalOcean, etc..

● Documento respondendo os seguintes questionamentos:

● Qual o tempo aproximado gasto por você neste desafio?

● Quais as dificuldades que você enfrentou no desafio?

● Quais soluções você tentou e não deram certo ou não foram viáveis de implementação?


## 5 Contextualização

Você acaba de ser contratado como Cientista de Dados para trabalhar em um projeto que visa melhorias na Câmara de Deputados do Brasil. Seu desafio será apoiar na redução de
custos e identificação de tendências para garantir melhor uso dos valores destinados aos gastos dos deputados. Para poder analisar o cenário atual dos gastos, o projeto usará como insumo a fonte de dados disponível no Brasil.io.
O site https://brasil.io/home/ é um repositório de dados público com dados acessíveis de diversas fontes. Para este desafio, utilizaremos a base de dados abaixo referente aos gastos dos deputados de todos os estados brasileiros:
https://brasil.io/dataset/gastos-deputados/cota_parlamentar/

## 6 Etapa 1

### 6.1 Base de dados:

1. Realize o download dos dados, limpe, normalize e ordene da melhor forma possível para que você compreenda com facilidade os dados dispostos para o desafio.

2. Você pode reduzir o tamanho da base para trabalhar de maneira mais rápida e eficiente.

3. Garanta que não há dados duplicados na base e renomeie as colunas se julgar necessário no intuito de melhorar o entendimento dos stakeholders sobre ao que
cada dado se refere.

4. Verifique se há dados nulos e defina o que fazer com eles. Pode -se preencher com NA, zero ou desconsiderar estes registros de sua análise.


### 6.2 Use sua criatividade!

1. Realize a mineração de dados e identifique cenários relevantes que possam ajudar a prever gastos com os deputados no decorrer deste ano.

2. Desenvolva um modelo preditivo que demonstre de maneira gráfica, através de um dashboard, ou/e de forma textual as previsões e conclusões que você obteve após
sua análise exploratória ou teste estatístico. Bibliotecas gráficas que podem ser usadas são: seaborn, ploty, Apexcharts ou outras.

3. Implemente scripts que possam ajudar na obtenção dos dados necessários para a análise desejada.

4. Encontre padrões de gastos e identifique formas de diminuir custos, assim será possível garantir o cumprimento do teto de gastos com os deputados, aproveitar
melhor a verba disponibilizada e prever problemas financeiros decorrentes de gastos indevidos ou abusivos.

5. Proponha soluções para contenção de gastos dos deputados, em especial para os gastos que representam um desvio na curva de dados.

### 6.3 Desenvolvimento Opcional

Fica à critério do candidato desenvolver um sistema que acesse a base parlamentar do brasil.io e que execute scripts, gere gráficos ou monte relatórios para apoiar gestores na
decisão sobre os gastos parlamentares.
A implementação pode ser feita em qualquer plataforma, AWS, Azure, Linode, etc, Quaisquer custos decorrentes da implementação desses sistemas, até o limite de R$ 100,00, será
reembolsado mediante comprovação de que o candidato realizou o teste.
É permitido ao usuário a utilização de qualquer framework ou tecnologia que facilite ou mesmo implemente exatamente o que está sendo requisitado no desafio. Por exemplo,
Laravel Queues (https://laravel.com/docs/5.5/queues)

### Dashboard

   ![Dashboard](https://raw.githubusercontent.com/rodolffoterra/Project_Marijuana_Legalization_TS/main/imagnes/Dashboard.png)



![Rodolfo Terra](https://raw.githubusercontent.com/rodolffoterra/wide_soft/main/logo.png)
