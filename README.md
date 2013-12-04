Exemplos PHP
============
Neste projetos estão alguns exemplos de pequenas aplicações PHP que usamos em sala de aula.  
A seguir eles são listados em ordem de complexidade (do mais simples ao mais complexo).

Algumas aplições requerem o database 'prog_web' criado no MySQL.
Esse database pode ser gerado a partir do seguinte script:

```sql
CREATE DATABASE prog_web DEFAULT CHARSET utf8;

CREATE TABLE pessoas (
  id int PRIMARY KEY,
  nome varchar(50),
  fone varchar(10),
  email varchar(100),
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```

soma
-----
Recebe dois números e exibe sua soma.

login
-----
Login simples usando PHP. Usuário e senha definidos no código-fonte da aplicação. 
   
crud
-----
CRUD simples em PHP.

mvc1
-----
Aplicação MVC usando um mini-framework feito com a aplicação.

mvc2
-----
Evolução do mvc1.

hello-ci
-----
Hello World com CodeIgniter.

hello2-ci
-----
Evolução do hello-ci.
