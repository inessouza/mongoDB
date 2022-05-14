<h3>Principais Entidades do MongoDB</h3>
<li>Database: é onde ficam as nossas collections e dados;</li>
<li>Collections: são como as tabelas nos bancos relacionais, nelas vamos inserir os dados;</li>
<li>Documents: são dados, no MongoDB tem esta nomeclatura;</li>
<li>Collections podem ser criadas livremente a qualquer momento e não possuem colunas fixas para os dados.</li>

<h3>MongoDB e JSON</h3>
<li>O tipo de dado inserido na collection (tabela) é o BSON, uma variação do JSON;</li>
<li>O BSON é semelhante ao JSON, porém com recursos a mais;</li>
<li>A forma de criar um BSON é igual ao JSON, exemplo:</li>
{
    nome: "Inês",
    idade: 33
}

<li>Documentação BSON: https://www.mongodb.com/docs/manual/reference/bson-types/</li>

<h3>Comandos MongoDB:</h3>
<li>show dbs: Mostra todos os databases que tem no banco</li>
<li>use: serve para criar um banco de dados e mudar do banco atual para outro banco</li>
mas esse banco só será de fato criado após ser inserido dados nele.</li>
<li>insertOne(): comando de inserção de dados, exemplo: db.nomedacollection.insertOne({ nome: "Inês", idade: 33 })</li>
<li>findOne(): comando para encontrar dados.</li>
<li>db: mostra o banco de dados que está selecionado no momento
db.nomedacollection.insertOne({ dado inserido }): serve para criar uma collection e insetir um dado</li>

<h3>Criação de Collections</h3>
<li>Não precisamos explicitamente criar uma collection, basta inserir um dado em alguma e automaticamente ela será criada.</li>
<li>Comando: db.nomedacollection.insertOne({ dado inserido })</li>
