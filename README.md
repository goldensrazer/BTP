# BTP Connect

Projeto elaborado no evento de tecnologia HACKATHON DOS PORTOS

## Getting Started

Siga todos os passos.

### Pre-requisitos
APIKEY = Gerar chave api no google maps https://developers.google.com/maps/documentation/javascript/get-api-key
local:Servidor xampp.
banco de dados:MYSQL
npm

```
Descompacte o arquivo na pasta xampp\htdocs\"Nome da pasta"
```

### Instalação


Instale o bower.

```
execute npm install -g bower
```


Instale as dependências na pasta do projeto.

```
execute bower install admin-lte
```

Criar Banco de dados, importar arquivo script DB e executar.

```
sistema\BD\db_btp
```

inicie o servidor e acesse a pasta

```
http://localhost/sistema/
```

Nos arquivos dashboard.php e admin.php dentro da pasta admin/

```
dashboard.php linha 311: inserir api key=API&callback //admin.php linha 319 o mesmo.
```
Resultado Tela de Login.

## Dentro do arquivo de dashboard.php e admin.php

Existe uma variavel: $mare = 1.5; //exemplo do elerta, esté valor é para mostrar o alerta no sistema caso o dados da API estejá realmente assim.

### O Sistema se divide em dois níveis de acesso "Funcinário" e "Líder"

Escolha Qual o tipo de nível é Através da caixa de seleção

```
[SELECIONE TIPO DE USUÁRIO]
```

## Built With

* [Admin LTE](https://adminlte.io/) - Painel de administração do open source e tema do painel de controle. Construído sobre o Bootstrap 3, o AdminLTE fornece uma variedade de componentes responsivos, reutilizáveis ​​e usados ​​com frequência.

## Authors

* **Kelvin Rodrigues** - *Initial work* - [goldensrazer](https://github.com/goldensrazer)

## Agradecimentos

* Deus
* café
* Code

