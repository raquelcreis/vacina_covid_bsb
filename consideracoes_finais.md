# Considerações Finais

+ Os pontos de vacinação do DF que não são UBS não foram cadastrados na base de dados. Por exemplo, algumas universidades, shoppings, igrejas foram usadas pelo GDF como postos de vacinação. Provavelmente, esses pontos foram cadastrados como UBS, mas não tem registro. Não dá para calcular qual foi a perda de precisão no cálculo da distância devido ao não cadastramento desses postos.

  

+ 30% dos vacinados do dataset não tem o CEP da residência cadastrado. Isso acarretou uma perda considerável de dados no estudo.

  

+ A haversine, biblioteca usada para calcular distância entre coordenadas, calcula uma rota em linha reta (diferente do que acontece na realidade). Uma conexão com API do Google Maps seria a melhor opção para traçar rotas.



+ A análise da variável "distância" mostra que o valor médio de distância percorrido até o posto de vacinação é de 10km em linha reta. Considerando o trajeto completo de ida e volta, dá pelo menos 20km. É uma "meia maratona" para ir até o posto de vacinação. Isso mostra a relevância de um estudo para acesso de pessoas que dependem de transporte público até o posto de vacinação.

