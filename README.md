Um Version Control System (VCS), ou Sistema de Controle de Versão, é uma ferramenta que permite o gerenciamento de alterações em um conjunto de arquivos ao longo do tempo. Ele registra todas as modificações feitas nos arquivos, permitindo que os desenvolvedores acompanhem as alterações, restaurem versões anteriores e trabalhem em conjunto de forma eficiente.
Essa série de modificações serve como uma trilha de auditoria. Isso ajuda a acompanhar o andamento de cada atualização. Ele também funciona como uma plataforma de melhoria ou culmina em uma versão final.
O controle de versão é benéfico no desenvolvimento de ativos digitais, arquivos binários e código de versão. Ele desempenha um papel particularmente importante ao gerenciar e acompanhar as mudanças. Ele permite que todos os membros de uma equipe colaborem a partir da versão atualizada mais recentemente.


5 Vantagens de Utilizar um VCS:
Colaboração entre equipes: facilita a colaboração entre membros da equipe, permitindo que várias pessoas trabalhem simultaneamente no mesmo projeto, sem interferirem negativamente no trabalho uns dos outros. 

Rastreamento de histórico: outro benefício é a capacidade de rastrear o histórico de alterações e recuperar versões anteriores do software. Isso é essencial para a solução de problemas e a correção de bugs, permitindo que as pessoas

Gerenciar lançamentos e versões: além disso, o versionamento fornece uma maneira eficaz de gerenciar lançamentos e versões, facilitando a identificação das versões estáveis para usuários finais e a entrega de atualizações consistentes e confiáveis. 


Segurança dos dados
Um VCS garante a segurança dos dados do projeto, uma vez que todas as alterações são armazenadas em um repositório centralizado. Isso evita a perda de código fonte em caso de falhas no sistema ou erros humanos. Além disso, o VCS permite que os desenvolvedores restaurem versões anteriores do projeto, caso ocorra algum problema.
Controle de acesso
O VCS permite que os desenvolvedores controlem o acesso aos arquivos do projeto. É possível definir permissões de leitura e escrita para cada membro da equipe, garantindo que apenas as pessoas autorizadas possam fazer alterações no código fonte



3 Exemplos de VCS:

VCS centralizado
O VCS centralizado é baseado em um repositório central, onde todas as alterações são armazenadas. Os desenvolvedores precisam se comunicar com o servidor central para obter a versão mais recente do código e enviar suas alterações. Exemplos de VCS centralizados incluem o CVS (Concurrent Versions System) e o Subversion.


VCS distribuído
O VCS distribuído não depende de um repositório central. Cada desenvolvedor tem uma cópia completa do projeto em seu próprio computador, incluindo todo o histórico de alterações. Isso permite que os desenvolvedores trabalhem offline e sincronizem suas alterações com outros membros da equipe posteriormente. Exemplos de VCS distribuídos incluem o Git e o Mercurial.

VCS híbrido
O VCS híbrido combina características do VCS centralizado e do VCS distribuído. Ele permite que os desenvolvedores trabalhem com um repositório central, mas também tenham cópias locais do projeto em seus computadores. Exemplos de VCS híbridos incluem o Bazaar e o Fossil.



# Desafio 2

A programação orientada a objetos surgiu como uma alternativa a essas características da programação
estruturada. O intuito da sua criação também foi o de aproximar o manuseio das estruturas de um
programa ao manuseio das coisas do mundo real, daí o nome "objeto" como uma algo genérico, que
pode representar qualquer coisa tangível.Esse novo paradigma se baseia principalmente em dois
conceitos chave: classes e objetos. Todos os outros conceitos, igualmente importantes, são construídos
em cima desses dois.
A POO trabalha utilizando classes, ela é quem dá a vida ao objeto, pois nela é que são criadas as
funcionalidades através dos métodos, dizendo se o objeto vai andar parar rodar, etc., e suas
especificidades através dos atributos, sua cor, seu nome, etc.. a classe não é o objeto, ela é utilizada
para construí-lo.
O objeto é uma abstração de software que pode ser algo representado por algo real ou virtual, que é
formado por um conjunto de propriedades (variáveis) e procedimentos (métodos), onde as variáveis
possuem um tipo que define os possíveis valores que pode representar um número inteiro, real ou string
e, os métodos são rotinas que, quando executadas realizam algumas tarefas como alterar o conteúdo
de uma variável do objeto. A classe é a abstração do objeto. Na realidade ao programarmos um objeto,
definindo suas características e funcionalidades, estamos programando uma classe.

O Conceito de Abstração em POO
A abstração é um princípio fundamental da Programação Orientada a Objetos que envolve a
identificação e a modelagem das características e comportamentos essenciais de um objeto, ignorando
os detalhes irrelevantes ou secundários para o contexto em questão. Em essência, a abstração permite
aos desenvolvedores criar modelos simplificados de entidades complexas do mundo real, focando
apenas nos aspectos que são importantes para a aplicação sendo desenvolvida.
Aplicando Abstração em Java
Java, sendo uma das linguagens de programação mais populares para a implementação de conceitos
de POO, fornece recursos robustos para aplicar a abstração. Vamos ilustrar isso com um exemplo
prático, retomando o cenário da clínica veterinária.


Encapsulamento

Encapsulamento é um princípo de design de código, geralmente ligado a programação orientada, que
nos orienta a esconder as funcionalidades e funcionamento do nosso código dentro de pequenas
unidades (normalmente métodos e funções). Isso possibilita que modificações no sistema possam ser
feitas de maneira mais cirurgicas, sem que uma funcionalidade esteja espalhada por diversas partes do
sistema.

Exemplo de Encapsulamento em Java
Imagine que estamos criando um sistema simples para gerenciar uma conta bancária. Para garantir que
os dados da conta sejam manipulados de forma segura, usamos o encapsulamento.

No Cenario de Herança as classes compartilhem seus atributos, métodos e outros membros da classe
entre si. Para a ligação entre as classes, a herança adota um relacionamento esquematizado
hierarquicamente.

Na Herança temos dois tipos principais de classe:

Classe Base: A classe que concede as características a uma outra classe.
Classe Derivada: A classe que herda as características da classe base.

O fato de as classes derivadas herdarem atributos das classes bases assegura que programas
orientados a objetos cresçam de forma linear e não geometricamente em complexidade. Cada nova
classe derivada não possui interações imprevisíveis em relação ao restante do código do sistema.
Com o uso da herança, uma classe derivada geralmente é uma implementação especifica de um caso
mais geral. A classe derivada deve apenas definir as características que a tornam única. Por exemplo:
uma classe base que serviria como um modelo genérico pode ser a classe Pessoa com os campos
Nome e Idade. Já uma classe derivada poderia ser Funcionário com os campos Nome e Idade herdados
da classe Pessoa, acrescido do campo Cargo.


O Polimorfismo é um mecanismo por meio do qual selecionamos as funcionalidades utilizadas de forma
dinâmica por um programa no decorrer de sua execução .
Com o Polimorfismo , os mesmos atributos e objetos podem ser usados em objetos diferentes, porém,
com implementações lógicas diferentes. Por exemplo: podemos assumir que uma bola de futebol e uma
camisa da seleção brasileira são artigos esportivos, mas que o cálculo deles em uma venda é calculado
de formas diferentes.

Outro exemplo: podemos dizer que uma classe chamada Vendedor e outra chamada Diretor podem ter
como base uma classe chamada Pessoa , com um método chamado CalcularVendas . Se este método
(definido na classe base) se comportar de maneira diferente para as chamadas feitas a partir de uma
instância de Vendedor e para as chamadas feitas a partir de uma instância de Diretor , ele será
considerado um método polimórfico, ou seja, um método de várias formas.


5 Vantagens da POO

1 Unificação de dados e processos

Os dados são identificados por meio dos atributos das classes. Já os processos são identificados pelos
métodos. A interação entre os objetos é definida pelo relacionamento entre os objetos e suas classes.
Com isso, nesse modelo de programação, existe total coerência entre dados e processos do mundo
real, e atributos e métodos do mundo da programação.

2 Consistência entre análise e desenvolvimento

A análise tradicional busca mapear, isoladamente, as estruturas de dados e os processos que tratam e
alteram tais dados. Normalmente, isso é feito com ferramentas como o Modelo de Entidades e
Relacionamento (MER ou ER) e o Diagrama de Fluxo de Dados (DFD). A análise tradicional é um tipo
de modelagem exclusivamente conceitual. Não existe relação direta entre as entidades conceituais e as
entidades físicas a serem implementadas. Com isso, é praticamente impossível identificar o processo de
DFD que está sendo implementado em um programa qualquer – a não ser que isso esteja claramente
indicado.

3 Reutilização do código já implementado
Uma vez que já temos os métodos e os atributos declarados e funcionando, podemos criar novas
classes que herdem essas funcionalidades. Em outras palavras, podemos atribuir novas funções a partir
das funções já existentes, sem precisar modificar nada do que já está pronto – herança, polimorfismo e
associação.

4 Multidesenvolvimento
Os desenvolvedores podem programar partes do sistema a ser desenvolvido simultaneamente. Isso
pode ser feito a partir de um conjunto de bibliotecas disponíveis de comum acordo. Cada uma dessas
partes será acrescida ao projeto final do sistema.

5 Facilidade de manutenção

Quando necessitamos modificar ou corrigir uma classe, estamos dizendo que é possível identificar qual
classe está com problemas em seus métodos e atributos. Isso também indica que podemos criar novas
classes, métodos, atributos e relacionamentos facilmente, para atender as novas demandas do sistema.
