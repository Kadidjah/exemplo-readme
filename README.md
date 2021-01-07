# exemplo-readme

## Nivelamento: back end, front end, padrão camadas, MVC, REST

[![Image]("Vídeo no Youtube")]

## Modelo conceitual
![Image](https://raw.githubusercontent.com/devsuperior/sds2/master/assets/modelo-conceitual.png "Modelo conceitual")

## Padrão camadas adotado

![Image](https://raw.githubusercontent.com/devsuperior/sds2/master/assets/camadas.png "Padrão camadas")

## Checklist

- Setup inicial do projeto
  - Dependências
  - Arquivos .properties
  - Configuração de segurança
- Modelo de domínio
  - Entidades e relacionamentos
  - Mapeamento objeto-relacional
  - Seed
- Criar endpoints
  - [GET] /products
  - [GET] /orders
  - [POST] /orders
  - [PUT] /orders/{id}/delivered
- Validar perfil dev
  - Base de dados Postgres local
  - Testar todos endpoints
- Preparar projeto para implantação
  - Arquivo system.properties
  - Profile prod -> commit
- Implantar projeto no Heroku
  - Criar app e provisionar Postgres
  - Criar base de dados remota
  - Executar comandos no Heroku CLI

**ATENÇÃO: O PROJETO NÃO RODA LOCALMENTE NO PROFILE PROD! Se você quiser rodar o projeto localmente depois, mude para o profile test.**

```bash
heroku login
heroku git:remote -a <nome-do-app>
git remote -v
git subtree push --prefix backend heroku main
```


## Dependências Maven

```
```

## Classe de configuração de segurança

```

```

## Arquivos .properties de cada profile do projeto

### application.properties
```

```

### application-test.properties
```

```

### application-dev.properties
```

```

### application-prod.properties
```
spring.datasource.url=${DATABASE_URL}
```

## Script SQL de instanciação da base de dados
```sql

```
