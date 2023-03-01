<h1 align="center">
Modelagem-de-Banco-de-dados
</h1>

![image](https://user-images.githubusercontent.com/115082857/222164566-900bb469-00f3-41ea-8d3a-5a83e5517036.png)


<h2 align="center">
Modelagem de banco implementação de um banco de dados posteriormente.
<h2>

### Existem outras entidades além dessa dessas três ?
Sim. Instituição_ensino, diretor, unidade e professor.

### Quais são os principais campos e tipos?
Id de iedentificação de cada tabela, nome, informações pessoais como cpf e data de nacimento, e capos de endereço como cep, bairro,etc. Os principais tipos de dados sâo int para ids, date para nascimento e varchar(), as vezes com limitação de tamanho para recber infomações especificas, por exemplo: cpf, cep, etc.

### Como essas entidades estão relacionadas?

<ul>
<li>Ainstiuição de ensino possui o curso e a unidade(onde o curso é aplicado).Ambas relações 1:n</li>
<li>O diretor rege a instiruição e a unidade. como ele pode reger mais de uma as relações são 1:n</li>
</ul>
