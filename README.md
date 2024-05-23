<h1 align="center">
  📰 Portal de Notícias Agetran 📰
</h1>

<p align="center">
<a href="#-projeto">Resumo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;  
  <a href="#-layout">Contato</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<br>

## 💻 Resumo

Repositório para o protótipo de um portal de notícias para a Agetran, desenvolvido durante o meu ensino médio no curso de Técnico em Informática no IFMS - Campus Dourados. 
Este projeto foi criado utilizando Node.js, Express, MySQL Workbench e Bootstrap para o front-end.


## ⚙️: Execução do Projeto

### 
Instale as dependências
```bash
yarn
# or
npm install
```

### Configuração do Banco: Copie o texto do arquivo banco.txt e cole no Aplicativo MySQL Workbench
Modifique o arquivo dbConnection.js configurando com suas informações do MySQL
```bash
const connMySQL = function(){
  return mysql.createConnection({
    host : 'localhost',
    user : '', // Modifique com o seu user do Workbench
    password : '', // Modifique com a sua senha do Workbench
    database : '' // Modifique com o nome que você declarou o seu banco no Workbench
  });
}
```

### Inicie o aplicativo no modo de desenvolvimento
```bash
nodemon app
```

## :telephone: Contato

Meu e-mail: pedro.hmota.goncalves@gmail.com
