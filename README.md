# LAB---Trabalhando-com-Machine-Learning

<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/87d332d0-5198-4a2f-b159-38c8c2976954.png"></a>
    <span> Trabalhando com Machine Learning</span>
</h1>

## Criando modelo de previsão

No machine learn é preciso ter uma workspace criada no portal Azure. Apos criar sua workspace podemos criar nosso trabalho automatizado.

Quando worlspace for criado, acesse o ML studio, e crie um new Automated ML.

![Captura de tela 2024-02-25 145937](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/12b412ea-6b6d-443b-a383-27bb3ee5db7e)

## Seguindo a documentação, vamos criar um Job name: mslearn-bike-automl :

![Captura de tela 2024-02-25 150338](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/cb8d39cf-39f8-4cdc-9903-57c47091dcf0)


task type: Regression 

![Captura de tela 2024-02-25 150618](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/72bf1538-a2ff-495f-ab1d-a34a48fe769a)

![select data](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/eb40b791-2111-4f7b-9a58-c48a24b3dea9)

Data Source:
Select From web files:

![Captura de tela 2024-02-25 150853](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/08aaf070-ee8c-4f8c-9003-15705ae04f50)

![Captura de tela 2024-02-25 151019](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/5ae8ef09-b1bc-40d7-b1c8-44f66f6a75b6)

Settings: Segui as informaçoes da documentação.

![Captura de tela 2024-02-25 151250](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/9610e900-579f-437d-89d2-680af3be48c7)

Schema: Segui a documentação

![Captura de tela 2024-02-25 151410](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/2e1cc8bc-8cce-4517-8b07-ca69f2b65edf)


Review: Validar se tudo segue conforme a documentação antes de "Create"

![Captura de tela 2024-02-25 151507](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/331c1d37-c6d4-4ecf-86c0-d1d056b9523b)

Task settings: Segui a documentação

![additional configuration](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/e8ecca16-2ceb-40bc-a29e-dc13b325d0f5)

![Captura de tela 2024-02-25 152316](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/4894e1cd-7504-4cc9-be83-96950a73593e)

Compute:

![compute config](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/f137e24b-fe3e-4b17-ad89-334f0f8dd4d6)

Review the best model


![serviço completado](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/c203ed4f-700a-4f64-b28a-e07e1564f908)

![automated ML](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/5a1082b0-c3de-4460-84a0-bd8f8150e8c9)


Pipeline Jobs

![jobs run](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/15f8d3f6-f65a-409f-b125-24ff523c05ee)

## Deploy and test the model

![implantar serviço de web](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/51d1ac6a-bfb7-4248-bb9c-bfcf737d7a37)

![config Deploy test model](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/447696b2-ed62-4d19-8991-64f3273ec655)

Codigo Json

![test result](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/66283a26-f63f-4554-a70a-0fd0cc5e4d2c)

{
  "Inputs": {
    "data": [
      {
        "day": 0,
        "mnth": 0,
        "year": 0,
        "season": 0,
        "holiday": 0,
        "weekday": 0,
        "workingday": 0,
        "weathersit": 0,
        "temp": 0.0,
        "atemp": 0.0,
        "hum": 0.0,
        "windspeed": 0.0
      }
    ]
  },
  "GlobalParameters": 0.0
}


Results:

![resultado final](https://github.com/lsantos1820/LAB---Trabalhando-com-Machine-Learning/assets/75084857/871daf4e-d7f7-4ef5-ad00-336583affd4e)

