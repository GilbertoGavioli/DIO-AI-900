Criei um Resource group
Logo apos criei um Create Azure AI services
Depois acessei o Studio do azure no link gerado(https://ml.azure.com?tid=24787ffc-c55f-40f7-9830-87ce829fa9c1&wsid=/subscriptions/4446048c-298b-4130-8d31-054a87258615/resourcegroups/az900/providers/Microsoft.MachineLearningServices/workspaces/Lab01)
Selecionei ML automatizado
Criei um Trabalho de treinamento aluguel-bicicletas 
SElecionei a tag Regressão
importei a url https://aka.ms/bike-rentals
coloquei as tags abaixo com os valores
Limits: Expand this section
Max trials: 3
Max concurrent trials: 3
Max nodes: 3
Metric score: 0.85 
Timeout: 15
Iteration timeout: 5
SElecionei o modelo e implantei um serviço WEB
Entrei 
selecionei a aba teste
e inseri os dados 
{
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }
