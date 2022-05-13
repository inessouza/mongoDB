<h3>Principais Entidades do MongoDB</h3>
- Database: é onde ficam as nossas collections e dados;
- Collections: são como as tabelas nos bancos relacionais, nelas vamos inserir os dados;
- Documents: são dados, no MongoDB tem esta nomeclatura;
- Collections podem ser criadas livremente a qualquer momento e não possuem colunas fixas para os dados.

<h3>MongoDB e JSON</h3>
- O tipo de dado inserido na collection (tabela) é o BSON, uma variação do JSON;
- O BSON é semelhante ao JSON, porém com recursos a mais;
- A forma de criar um BSON é igual ao JSON, exemplo:
{
    nome: "Inês",
    idade: 33
}

- Documentação BSON: https://www.mongodb.com/docs/manual/reference/bson-types/

<h3>Comando MongoDB:</h3>
- show dbs: Mostra todos os databases que tem no banco
- use nomedobanco: cria um banco de dados
mas esse banco só será de fato criado após ser inserido dados nele.
- insertOne(): comando de inserção de dados, exemplo: db.nomedacollection.insertOne({ nome: "Inês", idade: 33 })
- findOne(): comando para encontrar dados.

<h3>Exercício 1:</h3>
- Inserir um dado na collection:
    Script dado inserido: db.nomedacollection.insertOne({ nome: "Débora", idade: 33 })
- Fazer seleção de dados para ver o novo dado inserido na collection:
    Script busca de dados: db.nomedacollection.find()
