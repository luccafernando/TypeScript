# TypeScript

Muitas pessoas definiram como uma linguagem de programação, porem o próprio site do TypeScript disse que ele não é uma linguagem de programação, ele é um "superset" (um conjunto de ferramentas)  em cima do JavaScript definindo o tipo aplicado (tal variável vai ser sempre um numero ou sempre uma string, retorno de funções... etc)

O TypeScript adiciona essa parte de tipagem, comum em linguagens como "java"

A pergunta "adicionar tipagens dentro da minha aplicação eu perderia a produtividade e dinâmica do JavaScript?" e a resposta é sim. Temos essa desvantagem mas também temos de olhar os lados vantajosos de fazer isso... Um ganho com isso é se estiver usando uma IDE (exemplo: VSCODE) com  uma boa integração com o javascript, como o VSCode q é provavelmente a melhor IDE nos dias atuais, a gente ganha uma certa inteligência dando jus ao termo "IntelliSense" (q é um termo geral para uma variedade de recursos de edição de código, incluindo: conclusão de código, informações de parâmetros, informações rápidas e listas de membros. Os recursos intelliSense às vezes são chamados por outros nomes, como "conclusão de código", "assistência de conteúdo" e "dica de código".) e esses ganhos, são ganhos q superam as perdas.) completando os termos de forma inteligente 

 O TypeScript vai ajudar a gente em 2 principais coisas:

- Primeiro delas é inteligência da ide em si. então a gente consegue deixar o nosso editor muito inteligente e saber quais são as opções quais são os métodos, quais são as variáveis
- Segundo benefício que a gente tem com o typescript é evitar erros desnecessários já em ambiente de desenvolvimento sem a nossa aplicação ir para produção.

Vamos supor q a gente tem uma função de soma, a gente soma número a com número b e a partir de um certo momento a gente envia b como string, e o próprio editor já vai falar para gente que cara a função não tá esperando esse tipo de entrada por isso aqui você vai ter um erro suas e enviar para produção então ele bloqueia o nosso fluxo antes mesmo de enviar para produção

TypeScript vai ajudar principalmente o desenvolvedor na hora do ambiente de desenvolvimento, ele não tem a função de ajudar no seu código no ambiente de produção, tanto que o seu código no final quando você vai gerar a build pra produção ou o código final pra produção, você acaba tendo q gerar código JavaScript. O nosso navegador, o nosso node não lê código typescript por padrão ele lê código javascript, por isso que na hora da gente executar o código a gente sempre converte código para JavaScript por isso que ele vai ajudar somente em ambiente de desenvolvimento

Typescript não é um substituto do JavaScript, ele é uma ferramenta construída em cima do JavaScript. Então você precisa dominar muito bem o JavaScript caso você esteja necessitando sentindo necessidade de adicionar tipagem(typescript) na sua aplicação
