# Trabalhando-com-Machine-Learning

### Processo passo a passo de como criar o modelo de previsão
#### Antes de iniciar o modelo de previsão tivemos que criar um recuso no portal, com tudo pronto, agora sim podemos iniciar o passo a passo do modelo de previsão

- Para criar um ML automatizado, selecione no menu a opção **ML automatizado**
<img width="929" alt="IA900 - ML automatizado" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/0ba16282-319b-4406-b4d2-2eb39dde3723">

- A criação desse aprendizado de maquina tem como objetivo nos passar a previsão de aluguel de bicicletas
<img width="952" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/e50f28b4-72d9-4016-97d4-e275fb6425da">

![IA900 - ML automatizado 2](https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/8b798a09-8f4a-4be9-91dd-d58c23017dac)

<img width="668" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/07626187-e7e6-47e8-a581-968030825de7">

<img width="952" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/0fc140fd-7f70-4516-a2dc-783c3e4b867c">

<img width="956" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/5b614893-14f9-439b-978c-ec5496b707bc">

<img width="945" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/05a66968-9e7c-4bcc-a653-e00159fa4a4c">

#### Aqui voce não precisa clicar em nada, apenas avançar mesmo
<img width="953" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/48d9c758-51fa-44d2-a0c9-8d49a6d968a4">

#### Aqui voce vai clicar em criar
<img width="950" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/8b1d42b6-a46f-4506-acfd-532797864cf7">

#### Foi criado com sucesso, selecione o nome e depois clique em seguinte
<img width="955" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/47713650-57bb-49e4-9fd6-9190baf46762">

#### Na coluna de destino voce vai selecionar o ultimo da lista
![IA900 - ML automatizado 5](https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/83c9ca51-dfdb-48e7-b135-7ef526dd81e4)

<img width="955" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/0fe63ca4-0d1c-4c41-8ad8-fd6f49d599fd">

<img width="952" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/b3c78f48-0c77-4384-9238-6b734035705f">

<img width="952" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/f17c3aab-b70c-4dcd-a4c9-3619a64055f4">

<img width="956" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/ed117999-0075-422c-ba55-3a34d308445f">

<img width="952" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/b7c9e70b-a15d-486d-bf2e-9afc708009dd">

#### Nesse momento ele está em execução, vamos aguardar ele finalizar

<img width="944" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/c5f3118b-ecd7-4ff3-99e1-c35fc1035a0f">

<img width="944" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/5d9bbe62-6d51-47b7-916c-672ab047f95d">

#### Pipeline com as etapas do processo de aprendizado e os testes realizados
<img width="955" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/fda005d6-1aeb-42ad-b3cb-af5718716a0d">

- Teste do modelo

#### Na página do modelo, cliquei na aba "Pontos de extremidade". Também é possível acessar pelo menu lateral em "Pontos de extremidade". Cliquei no ponto correspondente ao modelo gerado. Em seguida, acessei a aba "Testar".
``` JASON
{
  "input_data": {
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
  }
}
```

#### A previsão gerada foi: 361.95

<img width="451" alt="image" src="https://github.com/SuellenlLima/DP01---Trabalhando-com-Machine-Learning/assets/125047720/7c882120-7433-4b81-a30c-3316c80dd435">





