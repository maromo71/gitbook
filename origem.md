# Apresentação

---

PHP \(um acrônimo recursivo para "PHP: Hypertext Preprocessor"\) é uma linguagem de script Open Source de uso geral, utilizada para o desenvolvimento de aplicações Web dentro do HTML.  
Apesar de ser uma linguagem de fácil aprendizado e de uso para pequenos scripts dinâmicos simples, o PHP é uma linguagem orientada a objetos.

Surgiu no ano de 1995 como um subconjunto de scripts Perl criados por Rasmus Lerdof.  
Em 1997 com as adições de Zeev Suraski e Andi Gutmans que reescreveram o parser, era lançada a versão 3, primeira versão estável e parecida com a linguagem atual. Ao reescrever o parser, foi criado o Zend Engine, que é mantido oficialmente pela empresa Zend em conjunto com a comunidade PHP.

No mês de maio de 2000 foi lançada a versão 4. A versão 5 foi lançada no de 2004, a prinicpal mudança foi uma nova API para Orientação a Obejtos providas pelo Zend Engine 2. Em 2015 foi lançada a versão 7 do PHP, atual versão do sistema.

## Algumas novidades na versão 7

Uma entre as várias modificações realizadas é que PHP 7 pemite definir um tipo de retorno de uma função ou método, como exemplos abaixo:

Sintaxa anterior a versão 7:

```php
function nomeDaFuncao()
{
    // corpo da função
}
```

Sintaxe atual:

```php
function nomeDaFuncao() : tipo
{
    // corpo da função
}
```

Ou seja,

```php
function calcularDobro($x) : float
{
    return $x * 2;
}
```

Outra novidade é o operador spaceship \(&lt;=&gt;\) que como em outras linguagens é utilizado para comparação numérica. Na prática o operador &lt;=&gt; retorna um dos 03 valores possíveis:

1. Retorna o valor \(-1\) quando o primeiro operando é menor que o segundo;

2. Retorna o valor \(0\) quando os dois operandos são iguais; e

3. Retorna \(1\) quando o segundo operando é maior que o primeiro.

Para saber sobre as novas funcionalidades adicionadas, consulte o site [http://php.net/docs.php](http://php.net/docs.php).

## Versões

Existem versões do PHP disponíveis para os seguintes sistemas operacionais:

* Windows, 
* Linux, 
* Mac OS, 
* OS/2, 
* AS/400, 
* Novell Netware, 
* RISC OS, IRIX e Solaris. 

A Wikipedia, por exemplo, funciona sobre um software inteiramente escrito em PHP, usando bases de dados MySQL: o MediaWiki.

## PHP e o Javascript

O que distingue o PHP de Javascript é que enquanto nesse últimos os scripts são executados no lado do cliente \(client-side\)no PHP o código é executado no servidor \(server-side\).  
 O cliente recebe os resultados da execução de um script PHP, sem nenhum condição de determinar como é o código fonte.

## PHP e Banco de Dados

Construir uma página dinâmica baseada em bases de dados é simples com PHP, este provê suporte a um grande número de bases de dados:  
Oracle,  
Sybase,  
PostgreSQL,  
InterBase,  
MySQL,  
SQLite,  
MSSQL etc, podendo abstrair o banco com a biblioteca ADOdb, entre outras.

## Protocolos suportados

Vários protocolos conhecidos são suportados pelo PHP, como por exemplo: IMAP, SNMP,   
NNTP,   
POP3,   
HTTP,   
LDAP,   
XML-RPC,   
SOAP.  É possível abrir sockets e interagir com outros protocolos. Várias bibliotecas de terceiros expandem as funcionalidades suportadas.

