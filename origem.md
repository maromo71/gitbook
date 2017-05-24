# Origem e Histórico

---

PHP \(um acrônimo recursivo para "PHP: Hypertext Preprocessor"\) é uma linguagem de script Open Source de uso geral, utilizada para o desenvolvimento de aplicações Web dentro do HTML.  
Apesar de ser uma linguagem de fácil aprendizado e de uso para pequenos scripts dinâmicos simples, o PHP é uma linguagem orientada a objetos.

Surgiu no ano de 1995 como um subconjunto de scripts Perl criados por Rasmus Lerdof.  
Em 1997 com as adições de Zeev Suraski e Andi Gutmans que reescreveram o parser, era lançada a versão 3, primeira versão estável e parecida com a linguagem atual. Ao reescrever o parser, foi criado o Zend Engine, que é mantido oficialmente pela empresa Zend em conjunto com a comunidade PHP.

No mês de maio de 2000 foi lançada a versão 4. A versão 5 foi lançada no de 2004, a prinicpal mudança foi uma nova API para Orientação a Obejtos providas pelo Zend Engine 2. Em 2015 foi lançada a versão 7 do PHP, atual versão do sistema.

Uma entre as várias modificações realizadas é que PHP 7 pemite definir um tipo de retorno de uma função ou método, como exemplos abaixo:

Sintaxa anterior a versão 7:

```
function nomeDaFuncao()
{
    // corpo da função
}
```

Sintaxe atual:

```
function nomeDaFuncao() : tipo
{
    // corpo da função
}
```

Ou seja,

```
function calcularDobro($x) : float
{
    return $x * 2;
}
```

Outra novidade é o operador spaceship \(&lt;=&gt;\) que como em outras linguagens é utilizado para comparação numérica. Na prática o operador &lt;=&gt; retorna um dos 03 valores possíveis:


