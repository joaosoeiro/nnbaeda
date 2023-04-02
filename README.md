# Exploratory Data Analysis baseada em dataset da NBA.

![2k](https://user-images.githubusercontent.com/54710426/229376839-7d245a75-d6ee-4ab6-a397-6d0b60fb9082.png)


## Introdução
E.D.A. feita em cima de dados de jogadores da NBA no game "NBA 2K" para a aula de I.A na Fatec SJC, com objetivo de tratar dados e trazer insights interessantes sobre o assunto.

## Tecnologias Utilizadas: 

```Python e módulos (Pandas, matplotlib, plotly, numpy)``` 


## Abaixo temos uma visão generalista da tabela, que contém informações diversas sobre os jogadores.

![dataset](https://user-images.githubusercontent.com/54710426/229376356-20434752-3587-49e6-81ee-adecdbf3d1f9.png)

Após tratar algumas inconsistências nos dados, começamos a conseguir extrair informações interessantes, a iniciar pela distribuição de jogadores por suas respectivas nacionalidades, notando grande diferença entre USA e outros por exclusividade do país nas escolhas anuais:


## Jogadores por País:

![player_by_ctr](https://user-images.githubusercontent.com/54710426/229376382-37c4ba14-715c-4b7b-9ad7-14d0b26c11c2.png)


## Nacionalidades por time:

![teaam_nationnanlities](https://user-images.githubusercontent.com/54710426/229376409-da6b9e40-eab1-4a59-b7de-cebfabe7558e.png)


## Jogadores com Escolaridade superior (nota-se que a maioria dos jogadores teve educação superior):

![college](https://user-images.githubusercontent.com/54710426/229376437-127e562b-8b77-4371-86a4-cfaf09c3b52e.png)


## Distribuição de jogadores por idade:

![por_idade](https://user-images.githubusercontent.com/54710426/229376455-8b5ea4a2-a6b1-496b-9f82-154b0752f1d0.png)


## Relação entre o ranking dos jogadores (no game) pela idade (notamos maior classificação em jogadores mais velhos):

![rating_x_idade](https://user-images.githubusercontent.com/54710426/229376510-fb402a24-b28b-4929-b717-d4648b150e47.png)


## Relação diretamente proporcional entre salário e ranking:

![salario_x_rating](https://user-images.githubusercontent.com/54710426/229376518-98b1730a-649e-4380-9f3e-307f11e53deb.png)


## Relação diretamente proporcional entre experiência e ranking:

![rating_x_experiencia](https://user-images.githubusercontent.com/54710426/229376531-c84afb86-3a43-44ac-bd41-8b6368351fb5.png)


## Mapa de correlações feito a partir dos dados:

![correlations](https://user-images.githubusercontent.com/54710426/229376536-7ef81343-39ba-4821-8a3d-28c0a71f1bb0.png)
A partir deste histograma de calor, vemos uma forte correlação entre:
1) Salário e classificação
2) Idade e experiência


E algumas correlações médias entre:
1) Experiência e avaliação
2) Salário e experiência

Além de uma correlação lógica entre altura e peso


## Posição dos jogadores com relação aos grupos etários:

![posicao_x_grupodeidade](https://user-images.githubusercontent.com/54710426/229376567-f2476826-325e-4ba5-a0b8-c3b8c9b6d710.png)
A partir deste gráfico de barras, podemos ver os jogadores mais velhos e, portanto, experientes, escolhendo a posição de centro ou de defesa, considerados os papéis mais dependentes de habilidade na comunidade do basquete.


## Quantidade de jogadores escolhidos nas duas primeiras rodadas:

![jogadores_draft_1_2](https://user-images.githubusercontent.com/54710426/229376598-fc5b509b-1139-4849-8029-60bd57ef93c7.png)


## Relação entre a posição de escolha e o ranking dos jogadores:

![rating_x_draftpos](https://user-images.githubusercontent.com/54710426/229376617-d2fec324-6706-4661-afdf-08d492e2e008.png)
A partir deste gráfico, vemos que os primeiros jogadores escolhidos têm maior probabilidade de sucesso na carreira, os jogadores não draftados (0) são jogadores com a pior classificação










