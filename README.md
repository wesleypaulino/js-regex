# js-regex

# quantifier
? - zero ou uma vez.
* - zero ou mais vezes.
+ - uma ou mais vezes.
{n} - exatamente n vezes.
{n,} - no mínimo n vezes.
{n,m} - no mínimo n vezes, no máximo m vezes.

# Classes de letras
## Para descrever o mês, devemos usar uma nova classe de letras, seguem alguns exemplos:

[A-Z] significa de A até Z, sempre maiúscula.
[a-z] significa de a até z, sempre minúscula,
[A-Za-z] significa A-Z ou a-z.
[abc] significa a, b ou c.


# Trabalhando com espaços
A definição do \s pode variar um pouco entre as implementações, mas normalmente é um atalho para [ \t\r\n\f] onde:

O primeiro caractere é um espaço branco.
\s significa whitespace.
\t é um tab.
\r é carriage return.
\n é newline.
\f é form feed.

# Ancora
Âncoras marcam uma posição específica no alvo, por isso não é possível combiná-las com um quantifier.
Econtrar uma conjuento de caracteres mais facilmente.
Devolve uma posição dentro do meu texto.
Existem várias âncoras predefinidas, mas as mais comuns são ^, $ e \b. Lembrando também que os caracteres ^ e $ são meta-chars.


\b word boundary (limite de caracteres)
\baaa\b

Não pode conter word char
\w - word Char [A-Za-z0-9_]

# Grupos

(\w+)   -  grupo de word chars
(\w+)?  -  grupo opcional
(?:\w+) -  non-capturing group