---

## Gabarito: 1000 pontos

Anotações sobre o resultado final:

- Não houve otimização das imagens, portanto o site perdeu pontos de performance (-10 pontos);
- Os botões não tem um nome acessível, ou seja, para leitores como o NVDA ou o TalkBack fica complicado para ler o site (-20 pontos);

### Subtotal: 970 pontos

## Anotações sobre o código:

- O site foi construído usando Styled Components, Porém o sistema de variáveis globais é feito com variáveis de css e não com as propriedades do styled components, o que causa um pequeno delay no Intellisense do VS Code e uma perca  (-10 pontos);
- As classes não possuem um nome semântico e é um pouco dificultada a leitura exemplo: “hstworighttextssecond (-20 pontos)”;
- Todos os componentes da página estão diretamente na Home.js, o que causa uma má organização no código e torna complicado o entendimento, já que não é todo separado por componentes (-20 pontos);
- No código não é usado nenhum tipo de estilização de código ou padronização, o que causa coisas como linhas com final de “;” e linhas sem final de “;” (-70 pontos)
Ex:

![code.png](https://media.discordapp.net/attachments/958883973096931348/965806221791748126/code.png?width=1440&height=510)

## Geral:

O desafio foi bem executado e a parte visual está perfeita, porém quando se trabalha em uma equipe o visual deve ser perfeito e o código também.

As questões sobre acessibilidade requerem um pouco mais de atenção, pois um site não é apenas o visual, temos que pensar também em pessoas com problemas de visão graves.]

O styled components é uma ferramenta incrível, quando você sabe dar uso as principais propriedades dela, como as props de componentes gerados pelo styled components.

A organização dos componentes deve se dar por 1 componente para cada seção do website, mesmo que a definição de componente seja algo que você use várias vezes, o código fica mais organizado se tiver 1 componente por seção.

O site foi feito usando ReactJS puro, uma das primeiras lições a serem aprendidas é a como trabalhar com o NextJS usando ele da melhor forma o possível.

A questão da estilização do código pode ser resolvida de uma maneira muito simples, apenas instalando o eslint e forçando o padrão de código standard.

As questões das classes “ilegíveis” podem ser resolvidas usando a cabeça para colocar um nome mais acessível, ou usando os seletores css de nth-child() para selecionar os elementos, deixando o HTML mais bonito.

## Pontuação total: 850 pontos
