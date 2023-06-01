# 5G Huawei hackathon

O avanço do 5G é uma das transformações mais significativas no mundo da tecnologia nos últimos anos, e o Brasil não está ficando para trás nessa corrida. Com uma latência e velocidade de transmissão de dados sem precedentes, o 5G promete revolucionar a conectividade e comunicação humana, além de possibilitar infinitas novas oportunidades para a inovação e empreendedorismo em diversas áreas como a saúde, a agricultura, a indústria e muito mais.

Nessa apresentação seram definidos duas etapas para nossa formação do Hakaton. Primeiramente seram apresentados alguns dados de redes de 5G que estão disponibilizados gratuiatamente em repositorios do Github facilmente clonaveis para uso de simulações projeções e sistemas de previsão sobre os usuarios.

As equipes poderão desenvolver seus projetos em diversas linhas, como, por exemplo, análise exploratória de dados, desenvolvimento de insights inovadores usando 5G e os conjuntos de dados disponibilizados, modelos de Aprendizado de Máquina para predição, classificação, agrupamento, suporte à decisão, desenvolvimento de modelos de desempenho de aplicações no contexto de 5G e muito mais.

# Requisitos para participar

Para desenvolver soluções para a Hackathon, é conhecimento para Aprendizado de Máquina no Jupyter Notebook.

Além disso, é desejável que os participantes tenham conhecimentos (basico) nos seguintes assuntos:

* Análise de dados;
* Métodos de Aprendizado de Máquina, tais como regressão, clusterização, entre outros; 
* Time-Series
* Programação em Python; e
* Jupyter Notebook.

# 1. Etapa 1
Para os participantes mostrem que dominam as aréas mais basicas solicitadas nos iremos conceder acesso de um arquivo jupyter com instruções e explicações em cima dos dados extraidos disponiveis aqui mesmo neste GitHub para isso os alunos devem:
1. Clonar este git;
2. abrir o jupyter;
3. extrair os dados já separados;
4. Analisar as descrições do arquivo jupyter;
5. Aplicar os desafios em jupyter ou artigo .py;

# 2. Entrega do arquivo
As equipes devem submeter os arquivos do Jupyter Notebook (ou caso usem serviços no colab ou jupyterHub do servidor GERCOM) produzidos em cada solução, que devem conter um storytelling dos dados cobrindo a descrição do que foi realizado pela equipe, os insights obtidos, o pré-processamento, os modelos de Aprendizado de Máquina desenvolvidos, a avaliação de desempenho dos modelos, a escolha do modelo de Aprendizado de Máquina, entre outros tópicos que as equipes julguem pertinente.

Atente-se ao roteiro dos desafios, aos critérios de avaliação e a entrega diferenciada de alguns desafios. Garanta que os avaliadores da comissão organizadora da Hackathon GERCOM tenham acesso a todos os arquivos da sua submissão. As equipes devem se assegurar de fornecer todos os demais conjuntos de dados que utilizaram. Dê preferência para baixar os dados necessários:
```python
# ✅ Recomendável
# > clonar um repositório do GitHub. Exemplo:
!git clone https://github.com/chsantos234/5G_Huawei_hackathon.git
```

# 3. Desafios a serem avaliados:

A edição mais recente do Relatório de Mobilidade Ericsson apontou que, no ano de 2022, 71% do tráfego da rede móvel mundial foi constituído por transmissão de vídeo e até 2028 esta demanda deverá aumentar em 9%. Nesse cenário, o gerenciamento e análise de redes móveis se mostram elementos fundamentais para promover uma melhor experiência de uso desse tipo de serviço, fator este que tende a proporcionar novas oportunidades de negócio e pesquisa à medida em que o uso da rede 5G se expande.


## 1. Visualização usando PathsViewer
A ferramenta: PathsViewer é uma interface para visualização de dados espaço-temporais em tempo real ou pós-eventos. Essa ferramenta busca suprir a demanda por ferramentas de visualização de trajetórias de objetos, em vista do grande interesse em pesquisas nesse tipo de dado.

É possível utilizar conjuntos de dados variados, com estruturas diversas, tais como traces de 5G georreferenciados e trajetórias de veículos.

O desafio: Esse desafio tem como objetivo usar a ferramenta PathsViewer para apresentar os conjuntos de dados fornecidos (não é necessário utilizar todos eles).

As equipes devem explorar as funcionalidades do PathsViewer, como ajuste de escala, visualização em mapa 2D ou satélite, envio de múltiplos conjuntos de dados, entre outras. Com isso, é possível gerar visualizações claras e informativas que ajudem os usuários a visualizar as informações contidas nos dados de trajetórias de objetos.

## 2. Predição de qualidade de sinal

As equipes poderão utilizar modelos estatísticos e/ou técnicas de aprendizado de máquina, como modelos de predição mono e multivariados, para inferir os valores de um indicador de qualidade de sinal de escolha, tal como QUAL, CQI e SNNR. O objetivo deste desafio é inferir a qualidade do sinal com base nos atributos fornecidos na base g-nettrack. As equipes podem combinar os dados fornecidos com informações presentes em outros conjuntos com o intuito de complementar e enriquecer os dados disponíveis.

## 3. Predição do tipo de mobilidade
Esse desafio consiste em utilizar métodos não-supervisionados de aprendizado de máquina para prever o tipo de mobilidade (pedestre, veículo, metrô/trem) de um dispositivo móvel com base nos dados de localização não rotulados fornecidos pelo conjunto de dados. Essa tarefa pode ser abordada de diversas formas, como, por exemplo, na forma de um problema de classificação baseada em clusterização (classificação não-supervisionada), onde o modelo de aprendizado de máquina deve classificar cada registro do conjunto de dados em uma das classes de mobilidade possíveis.

# Critérios de Avaliação:
-Os participantes devem resolver o maior número possível dos desafios fornecidos;
-Pré-processamento dos dados;
-Representação dos dados e estratégia de composição de atributos;
-Estratégia de seleção do modelo escolhido;
-Estratégia de validação;
-Qualidade do modelo em relação às métricas de qualidade (tal como acurácia, precisão, revocação e F1-score);
-Interpretabilidade do modelo sugerido;
-Storytelling dos dados, incluindo conclusões;
-Potencial impacto e viabilidade da solução apresentada; e
-Criatividade da solução e apresentação.

