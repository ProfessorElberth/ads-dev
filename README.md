# Projetos ADS
> ADS - Fundamentos e desenvolvimento web com java

Apresentação dos projetos e introdução ao git.

## DESAFIO 01

> Organização no GIT
	
01. Crie o seu repositório: dev-ads-xxx (onde xxx é e-mail, tipo: elberth.moraes@). Assim: dev-ads-elberth-moraes
02. Crie um arquivo readme.md e apresente o enunciado do seu projeto, a ide que vc usou e a sua versão do java.
03. Trabalhe no arquivo exclude para eliminar os *.class.

> Crie uma classe com as seguintes features

01. Crie uma classe chamada App01 que tenha um método main.
02. Através dos argumentos receba 10 informações que serão utilizadas no sistema.
03. Implemente o método "valida" que receba a quantidade de argumentos e retorne true/false após teste.
04. A classe terá as seguintes informações do aluno: nome (texto), mensalidade (num), bolsista (bool).
05. Também terá as seguintes informações da escola: nome (texto), e-mail (texto), ano de criação (num).
06. E teremos também as informações de avaliação: notas da primeira e da segunda prova, notas dos trabalhos um e dois.
07. Implemente o método "construtor" para atribuir os valores dos argumentos às variáveis da classe (atributos).
08. Este método só será chamado se o "validar" retornar true; caso contrário, uma mensagem de erro será exibida.
09. Implemente a seguinte mensagem no método "exibir":
```
aa - aluno bb - paga R$cc de mensalidade em dd (ee) - fundada em ff - e foi gg com média hh.
```
Onde: 
* aa - nome do aluno;
* bb - bolsista/pagante; 
* cc - mensalidade; 
* dd - nome da escola; 
* ee - email da escola; 
* ff - ano de criação; 
* gg - aprovado/reprovado; 
* hh - média.

10. Para definir "bb - bolsista/pagante", implemente o método "getTipo".

	Se o campo que indica a bolsa for verdadeiro, "bolsista"; caso contrário, "pagante".

13. Para definir "cc - mensalidade", implemente o método "getMensalidade".
	
	Se o campo que indica a bolsa for verdadeiro, a mensalidade terá 50% de desconto.

14. Para definir "gg - aprovado/reprovado", implemente o método "getSituacao". 

	Se a média for superior a 8 (inclusive), "aprovado"; caso contrário, "reprovado".

15. Para definir "hh - média", implemente o método "calcularMedia". 
	
	A forma de cálculo é a seguinte: (prova1 + trabalho1) * 0.6 + (prova2 + trabalho2) * 0.4

16. Atualize o método "construtor" para tratar algumas regras de preenchimento: 

	a) as notas das provas precisam estar entre 0 e 7;
	
	b) os trabalhos entre 0 e 3.
	
	c) caso as notas sejam negativas, mude-as para 0 (zero); 
	
	d) caso sejam superiores ao valor máximo, mude-as para os valores máximos 7 ou 3.
