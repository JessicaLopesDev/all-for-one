# All For One

## :page_with_curl: Sobre

O projeto All For One utiliza o banco de dados relacional MySQL, e para manipulá-lo construímos queries utilizando conceitos de SELECT, INSERT, UPDATE, DELETE, entre outros. Foi um desafio que consolidou a utilização do Docker, conceitos de SQL e a manipulação de tabelas utilizando MySQL Workbench.

## :man_technologist: Habilidades desenvolvidas

- Docker
- MySQL
- Manipulação de tabelas
- Filtragem de dados

## 🛠️ Ferramentas Utilizadas

- Docker
- MySQL

## ⚙️ Como Executar

> :warning: &nbsp; _Para executar este projeto é necessário ter o Docker e o MySQL Workbench instalados_

<details>
  <summary> Como iniciar </summary>
  <br>

1. Clone o repositório em uma pasta

```
git clone git@github.com:JessicaLopesDev/all-for-one.git
```

2. Entre na pasta raíz do projeto e instale as dependências

```
npm install
```

3. Para rodar o projeto é necessario executar o comando abaixo no diretório raiz do projeto. Isso fará com que os containers docker sejam orquestrados e o banco de dados esteja disponível

```
docker-compose up -d
```

4. No MySQL Workbench, crie o banco de dados a partir dos comandos do arquivo <code>northwind.sql</code>

5. Para testar as queries, copie os comandos dos arquivos <code>challenges/desafio1...27.sql</code> no MySQL Workbench
