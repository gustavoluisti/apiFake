# apiFake

<h2>Install JSON Server</h2>

npm install -g json-server

git clone https://github.com/gustavoluisti/apiFake.git

<h2>Start JSON Server</h2>

json-server --watch db.json

{ <br />
  "lsProponentes" : [ {<br />
    "nmCliente" : "Davi Luiz Antunes de Souza",<br />
    "dtNascimento" : "2015-07-20",<br />
    "idSexo" : 0,<br />
    "nmCPF" : "12345678900",<br />
    "nmCNPJ" : "16563200000192",<br />
    "nmTipoCliente" : 0<br />
  } ]<br />
}<br />

<h2>Consulta por sexo</h2>

http://localhost:5000/lsProponentes?idSexo=1

<h2>Consulta por Cpf</h2>

http://localhost:5000/lsProponentes?nmCPF=46642091507

<h2>Consulta por data de nascimento</h2>

http://localhost:5000/lsProponentes?dtNascimento=2015-07-20

http://localhost:5000/lsProponentes?nmCliente_like=D

<h2>Criando paginação</h2>

http://localhost:5000/lsProponentes?_page=2&_limit=4


 
