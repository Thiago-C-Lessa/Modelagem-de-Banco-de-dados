<h1 align="center">
Modelagem-de-Banco-de-dados
</h1>

![image](https://user-images.githubusercontent.com/115082857/222164566-900bb469-00f3-41ea-8d3a-5a83e5517036.png)


<h2 align="center">
Modelagem de banco para uma implementação de um banco de dados posteriormente.
<h2>

### Existem outras entidades além dessa dessas três ?
> Sim. Instituição_ensino, diretor, unidade e professor.

### Quais são os principais campos e tipos?
> Id de iedentificação de cada tabela, nome, informações pessoais como cpf e data de nacimento, e capos de endereço como cep, bairro,etc. Os principais tipos de dados sâo ``int`` para ids, ``date`` para nascimento e ``varchar()``, as vezes com limitação de tamanho para recber infomações específicas, por exemplo: cpf, cep, etc.

### Como essas entidades estão relacionadas?

> <ul>
> <li>
> Ainstiuição de ensino <strong><em>possui</em></strong> o curso e a unidade(onde o curso é aplicado). Ambas relações 1:n
> </li>
> <li>
> O diretor <strong><em>rege</em></strong> a instiruição e a unidade. Como ele pode reger mais de uma as relações são 1:n
> </li>
> <li>
> A unidade <strong><em>possui</em></strong> a turma. A unidade pode ter mais de uma turma relação 1:n
> </li>
> <li>
> O professor <strong><em>leciona</em></strong> a turma. Assim como professor pode ter mais de uma turma, uma turma pode ter mais de um professor, assim essa relaçâo é n:m
> </li>
> <li>
> A turma <strong><em>recebe</em></strong> o aluno. Como a turma pode receber mais de um aluno é uma relação 1:n
> </li>
> </ul>
