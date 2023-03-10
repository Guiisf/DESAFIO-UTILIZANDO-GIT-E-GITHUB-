# <h1 align="center"> funcionalidades que será implementada no PI lll</h1>


<p>Spring</p>
<p>MySQL</p>
<p>HTML/CSS/JavaScript (ou algum framework de front-end)</p>

<h2>Definição de requisitos:</h2>
Com base no tema de sistema para cafeteria,  
<p>requisitos para a aplicação:</p>

<li>Cadastro de clientes</li>
<li>Cadastro de fornecedores</li>
<li>Cadastro de produtos (bebidas, alimentos, etc.)</li>
<li>Controle de estoque</li>
<li>Controle de vendas (realizadas pelos clientes)</li>

<h2>Criação do banco de dados:</h2>

Com base nos requisitos definidos, modelo de banco de dados para a aplicação:

<li>Tabela "clientes" (id, nome, email, telefone, endereço)</li>
<li>Tabela "fornecedores" (id, nome, email, telefone, endereço)</li>
<li>Tabela "produtos" (id, nome, descrição, preço, quantidade em estoque)</li>
<li>Tabela "vendas" (id, cliente_id, data, valor_total)</li>
<li>Tabela "itens_venda" (id, venda_id, produto_id, quantidade, valor_unitário)</li>
<li>Desenvolvimento da aplicação:</li>

<h2>funcionalidades:</h2>

<li>Implementar os CRUDs (Create, Read, Update, Delete) para os clientes, fornecedores e produtos</li>
<li>Implementar o controle de estoque, com validação de estoque mínimo e máximo para cada produto</li>
<li>Implementar o registro de vendas, atualizando o estoque dos produtos vendidos e calculando o valor total da venda</li>
<li>Desenvolvimento do front-end:</li>

<h3>Por fim,  a interface do usuário (UI) utilizaremos HTML/CSS/JavaScript ou algum framework de front-end, como React Native. Algumas sugestões de páginas para a aplicação são:</h3>

<li>Página inicial com informações sobre a cafeteria e opções de navegação</li>
<li>Página de cadastro/edição de clientes, fornecedores e produtos</li>
<li>Página de listagem de clientes, fornecedores e produtos</li>
<li>Página de controle de estoque, com opção de adicionar/retirar produtos do estoque</li>
<li>Página de registro de vendas, com opção de adicionar/remover produtos da venda e cálculo do valor total</li>

