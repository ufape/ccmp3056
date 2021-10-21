# Conceitos básicos de eletrônica digital

## Circuitos digitais

- Os circuitos digitais (e suas técnicas) estão presentes em quase todas as áreas.

    - Computadores;
    - Automação;
    - Robôs;
    - Ciência médica;
    - ...

## Sistemas analógicos

- Contém dispositivos que manipulam quantidades físicas que são representadas de forma analógica.

## Sistemas Digitais

- Combinam dispositivos projetados para manipular informação lógica ou quantidades físicas que são representadas no formato digital.
    - Calculadoras e computadores digitais;
    - Relógios digitais;
    - Controladores de semáforos de tráfego;
    - ...

## Vantagens das técnicas digitais vs analógicas

- Mais fáceis (simplicidade) de serem projetadas:
    - circuitos digitais são circuitos de chaveamento e apenas uma faixa de tensão interessa:
        - ALTA
        - BAIXA
- Fácil armazenamento de informação:
    - podem manter uma informação pelo tempo necessário.
- Maior precisão e exatidão:
    - A precisão e exatidão podem ser obtidos através do acrescimo de mais circuitos de chaveamento.
- Podem ser facilmente programados:
    - As operações de um circuito digital podem ser controladas por um conjunto de instruções armazenadas.

## Vantagens das técnicas digitais vs analógicas

- São menos afetados por ruídos:
    - flutuações aletórias na tensão (ruído) não são tão críticas em sinais digitais, pois este utiliza faixas de tensão distintas e muito específicas.
- Circuitos integrados digitais contendo grandes quantidades de dispositivos internos:
    - É mais economicamente viável produzir circuitos digitais contendo grandes quantidades de dispositivos internos.

## Sistemas de Numeração

(conteúdos da aula passada aqui)

## O campo da eletrônica digital:

- Lógica combinacional
    - Saídas dependentes única e exclusivamente das variáveis de entrada;
- Lógica sequencial
    - Saídas dependentes das variáveis de entrada ou dos estados anteriores que permanecem armazenados;
    - Geralmente, são sistemas pulsados, ou seja, dependem de um sinal de clock.

## Álgebra de Boole

- São definidas algumas operações elementares na álgebra de Boole:
    - Inversora (Not) (CI7404 - seis inversores)
    - E (And) (CI7408 - quatro portas AND de duas entradas) 
    - Ou (Or) (CI 7432 - quatro portas Or de duas entradas)
    - Nand (CI 7400 - quatro portas NAND de duas entradas)
    - Xor (CI 7486 - quatro portas XOR de duas entradas)
    - Nor (CI 7428 - quatro portas NOR de duas entradas)
    - Xnor (CI 74266: quatro portas XNOR de duas entradas com coletor aberto)

Mais informações sobre:

- [Portas lógicas e tabelas verdade](https://pt.wikipedia.org/wiki/Porta_l%C3%B3gica)
- [CI da série TTL 7400](https://pt.wikipedia.org/wiki/TTL_7400)

### Teoremas booleanos

Para uma única variável

(1) $x \cdot 0 = 0$

(2) $x \cdot 1 = x$

(3) $x \cdot x = x$

(4) $x \cdot \overline{x} = 0$

(5) $x + 0 = x$

(6) $x + 1 = 1$

(7) $x + x = x$

(8) $x + \overline{x} = 1$

Para mais de uma variável

(9) $x + y = y + x$

(10) $x \cdot y = y \cdot x$

(11) $x + (y + z) = (x + y) + z = x + y + z$

(12) $x(yz) = (xy)z = xyz$

(13a) $x(y + z) = xy + xz$

(13b) $(w + x)(y + z) = wy + wz + xy + xz$

(14) $x + xy = x$

(15a) $x +\overline{x}y = x + y$

(15b) $\overline{x} + xy = \overline{x} + y$

## Bibliografia

- Ivan V. Idoeta e Francisco G. Capuano, Elementos de Eletrônica Digital, 40. Ed. EditoraÉrica, 2009.

- Ronald J. Tocci e Neal S. Widmer, Sistemas Digitais: Princípios e Aplicações, 11. Ed. Pearson - Prentice Hall, 2015.
