# apiFake

<h2>Install JSON Server</h2>

npm install -g json-server

git clone https://github.com/gustavoluisti/apiFake.git

<h2>Start JSON Server</h2>

json-server --watch db.json

{
  "lsProponentes" : [ {
    "nmCliente" : "Davi Luiz Antunes de Souza",
    "dtNascimento" : "2015-07-20",
    "idSexo" : 0,
    "nmCPF" : "12345678900",
    "nmCNPJ" : "16563200000192",
    "nmTipoCliente" : 0
  } ]
}

<h2>Consulta por sexo</h2>

http://localhost:5000/lsProponentes?idSexo=1

<h2>Consulta por Cpf</h2>

http://localhost:5000/lsProponentes?nmCPF=46642091507



