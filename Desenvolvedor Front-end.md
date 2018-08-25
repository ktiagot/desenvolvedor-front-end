# Desenvolvedor Front-end

1 - Para uma melhor otimização no site se faz necessária a divisão de alguns arquivos css, a melhor maneira de integrá-los, seria separá-los por padrões de páginas ou módulos do site, fazendo com que um arquivo chame o outro quando necessário, para não sobrecarregar o carregamento de cada página que o usuário acessa.

2 -
Utilizar ferramentas que verificam e compactam os arquivos js, css, e outros;
Inserir os links para o CSS no início do código;
Inserir os Scripts no final do código;
Otimizar as imagens;
Utilizar armazenamento em cache para próximos carreagmentos;

3 - GTMetrix e Test My Site (Think With Google)

4 - Configuração do arquivo (DocType e HTML), Configuração da página (links e referências externas como scripts e css), o Corpo do site (body) onde contém: Cabeçalho (header), Seções e Divisões (section e div), e o rodapé (footer).

5 - Ambos são utilizados na requisição FTP, sendo o GET requisitado pela URL, com uma string amostra no endereço, já o POST é encapsulado com a requisição e não é visível ao usuário.

6 -
display: inline;
display: block;
display: inline-block;
display: table;
display: inline-table;
display: table-cell;
display: table-column;
display: table-row;
display: grid;
display: inline-grid;
display: flex;
display: inline-flex;
display: inherit;

7 - "display: inline" não aceita definições de espaçamento ou tamanho, utilizando o espaço necessário pra sua exibição, já o "display: inline-block" inclui a propriedade do "display: block" que permite essa alteração.

8 - 
Relativa: é o posicionamento que podem ser modificadas as propriedades da posição (top bottom left right);
Fixa: é o posicionamento onde não importa o local em que o usuário estará na página, o elemento vai ficar "preso" ali, mesmo que ele desça a página, ele está fixo no mesmo lugar;
Absoluta: é o posicionamento onde o elemento vai ser colocado imediatamente após o elemento relativo anterior à ele;
Estática: é um posicionamento que não é alterado pelas propriedades da posição. É o posicionamento padrão do HTML;

9 - Ambos chamam funções, efetuando a chamada com o primeiro argumento passado, onde o .call recebe os argumentos seguintes em ordem, e o .apply recebe como segundo argumento um array com todos os outros argumentos a serem passados.

10 - "==" é usado para comparação entre valores da variável, transformando ambas num mesmo tipo de variável, enquanto o "===" leva em consideração o tipo dessa variável, somente retornando um valor sendo usado em duas variáveis do mesmo tipo
