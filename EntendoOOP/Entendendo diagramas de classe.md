[[POO]]
###O que é um diagrama de classes?


Um diagrama de classes na Unified Modeling Language (UML) é um diagrama de estrutura estática que descreve a estrutura de um sistema mostrando suas classes, seus atributos, operações (ou métodos) e os relacionamentos entre objetos. Um diagrama de classes é um modelo para um sistema ou subsistema. Você pode usar diagramas de classe para modelar os objetos que compõem o sistema, mostrar os relacionamentos entre os objetos e descrever as funções desses objetos e os serviços que eles fornecem.

## A origem da UML

O objetivo da UML é fornecer uma notação padrão que possa ser usada por todos os métodos orientados a objetos e selecionar e integrar os melhores elementos de notações precursoras. A UML foi projetada para uma ampla gama de aplicações. Portanto, ele fornece construções para uma ampla gama de sistemas e atividades (por exemplo, sistemas distribuídos, análise, projeto e implantação de sistemas).

UML é uma notação que resultou da unificação de OMT de

1. [A Técnica de Modelagem de Objetos OMT](https://en.wikipedia.org/wiki/Object-modeling_technique)  [ [James Rumbaugh](https://en.wikipedia.org/wiki/James_Rumbaugh)  1991] – era a melhor para análise e sistemas de informação com uso intensivo de dados.
2. Booch [ [Grady Booch](https://en.wikipedia.org/wiki/Grady_Booch)  1994] – foi excelente para design e implementação. Grady Booch trabalhou extensivamente com a  linguagem [Ada](https://en.wikipedia.org/wiki/Ada_\(programming_language\))  e foi um dos principais atores no desenvolvimento de técnicas de Orientação a Objetos para a linguagem. Embora o método Booch fosse forte, a notação foi menos bem recebida (muitas formas de nuvens dominaram seus modelos – não muito organizadas)
3. OOSE (Engenharia de Software Orientada a Objetos [ [Ivar Jacobson](https://en.wikipedia.org/wiki/Ivar_Jacobson)  1992]) – apresentava um modelo conhecido como Casos de Uso. Casos de uso são uma técnica poderosa para entender o comportamento de um sistema inteiro (uma área onde OO tem sido tradicionalmente fraco).

Em 1994, Jim Rumbaugh, o criador do OMT, surpreendeu o mundo do software quando deixou a General Electric e se juntou a Grady Booch na Rational Corp. era de fato o “Método Unificado”).

![Histórico UML](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/01-uml-history.png)

### O propósito do diagrama de classes

Os diagramas de classes são úteis em muitas fases do projeto do sistema. Durante a fase de análise, os diagramas de classes podem ajudá-lo a entender os requisitos do domínio do problema e identificar seus componentes. Em projetos de software orientados a objetos, o diagrama de classes criado nos estágios iniciais do projeto contém classes que geralmente são convertidas em classes e objetos de software reais ao escrever o código.

Posteriormente, você pode refinar a análise inicial e os modelos conceituais em diagramas de classe para mostrar partes específicas do sistema, interfaces de usuário, implementações lógicas e assim por diante.

Os diagramas de classes são amplamente usados ​​na modelagem de sistemas orientados a objetos porque são os únicos diagramas UML que podem ser mapeados diretamente para linguagens orientadas a objetos. Durante a fase de implementação do ciclo de desenvolvimento de software, você pode usar diagramas de classes para transformar modelos em código e código em modelos.

## Exemplo de classe

Um cão tem estados – cor, nome, raça, bem como comportamentos – abanar, latir, comer. Um objeto é uma instância de uma classe.

![](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/img_6216dd4f9b3aa.png)

## Notação de classe UML

Uma classe representa um conceito que encapsula estado ( **atributos** ) e comportamento ( **operações** ). Cada atributo tem um tipo. Cada  **operação**  tem uma  **assinatura** . _O nome da classe é a  **única informação obrigatória**_ .

![](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/img_6216dd6d31d5b.png)

**Nome da classe:**

- O nome da classe aparece na primeira partição.

**Atributos de classe:**

- Os atributos são mostrados na segunda partição.
- O tipo de atributo é mostrado após os dois pontos.
- Os atributos mapeiam em variáveis ​​de membro (membros de dados) no código.

**Operações de Classe (Métodos):**

- As operações são mostradas na terceira partição. São serviços que a classe oferece.
- O tipo de retorno de um método é mostrado após os dois pontos no final da assinatura do método.
- O tipo de retorno dos parâmetros do método é mostrado após os dois pontos após o nome do parâmetro. As operações mapeiam em métodos de classe no código

![](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/img_6216dd7bde62d.png)

## Relações de classe

Uma classe pode estar envolvida em um ou mais relacionamentos com outras classes. Um relacionamento pode ser um dos seguintes tipos: (Consulte a figura à direita para a representação gráfica dos relacionamentos).

|Tipo de relacionamento|Representação gráfica|
|---|---|
|**Herança**  (ou Generalização):<br><br>- Representa uma relação “é-um”.<br>- Um nome de classe abstrata é mostrado em itálico.<br>- SubClass1 e SubClass2 são especializações da Super Class.<br>- Uma linha sólida com uma ponta de seta oca que aponta da classe filha para a classe pai|![Herança (ou Generalização)](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/08-inheritance-in-class-diagram.png)|
|**Associação simples** :<br><br>- Uma ligação estrutural entre duas classes de pares.<br>- Existe uma associação entre Class1 e Class2<br>- Uma linha sólida conectando duas classes|![Associação simples](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/04-simple-association.png)|
|**Agregação** :Um tipo especial de associação. Representa uma “parte de” relacionamento.<br><br>- A classe2 faz parte da classe1.<br>- Muitas instâncias (indicadas pelo *) de Class2 podem ser associadas a Class1.<br>- Objetos de Class1 e Class2 têm tempos de vida separados.<br>- Uma linha sólida com um diamante não preenchido na extremidade da associação conectada à classe de compósito|![Agregação](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/05-aggregation.png)|
|**Composição** :Um tipo especial de agregação onde as partes são destruídas quando o todo é destruído.<br><br>- Objetos de Class2 vivem e morrem com Class1.<br>- Class2 não pode ficar sozinho.<br>- Uma linha sólida com um diamante preenchido na associação ligada à classe de compósito|![](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/06-composition.png)|
|**Dependência** :<br><br>- Existe entre duas classes se as mudanças na definição de uma podem causar mudanças na outra (mas não o contrário).<br>- A classe1 depende da classe2<br>- Uma linha tracejada com uma seta aberta|![Dependência](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/07-dependency.png)|

### Nomes de relacionamento

- Os nomes dos relacionamentos são escritos no meio da linha de associação.
- Bons nomes de relacionamentos fazem sentido quando você os lê em voz alta:
    - “Toda planilha  **contém**  um certo número de células”,
    - “uma expressão é  **avaliada como**  um valor”
- Eles geralmente têm uma  **pequena ponta de seta para mostrar a direção**  em que direção ler o relacionamento, por exemplo, expressões são avaliadas como valores, mas valores não são avaliados como expressões.

![](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/img_6216dd9bda59a.png)

### Relacionamento – Funções

- Uma função é um propósito direcional de uma associação.
- Os papéis são escritos nas extremidades de uma linha de associação e descrevem o propósito desempenhado por essa classe no relacionamento.
    - Por exemplo, uma célula está relacionada a uma expressão. A natureza da relação é que a expressão é a  **fórmula**  da célula.

### Navegabilidade

As setas indicam se, dada uma instância participando de um relacionamento, é possível determinar as instâncias da outra classe que estão relacionadas a ela.

O diagrama acima sugere que,

- Dada uma planilha, podemos localizar todas as células que ela contém, mas que
    - não podemos determinar a partir de uma célula em qual planilha ela está contida.
- Dada uma célula, podemos obter a expressão e o valor relacionados, mas
    - dado um valor (ou expressão) não podemos encontrar a célula da qual esses são atributos.

## Visibilidade de atributos de classe e operações

No projeto orientado a objetos, há uma notação de visibilidade para atributos e operações. A UML identifica quatro tipos de visibilidade:  **public** ,  **protected** ,  **private** e  **package** .

Os símbolos +, -, # e ~ antes de um atributo e nome de operação em uma classe denotam a visibilidade do atributo e da operação.

- + denota atributos ou operações públicas
- – denota atributos ou operações privadas
- # denota atributos ou operações protegidas
- ~ denota atributos ou operações do pacote

### Exemplo de visibilidade de classe

![](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/img_6216ddbf82876.png)

No exemplo acima:

- attribute1 e op1 de MyClassName são públicos
- attribute3 e op3 são protegidos.
- attribute2 e op2 são privados.

O acesso para cada um desses tipos de visibilidade é mostrado abaixo para membros de diferentes classes.

|Direito de acesso|público (+)|privado (-)|protegido (#)|Pacote (~)|
|---|---|---|---|---|
|Membros da mesma classe|sim|sim|sim|sim|
|Membros de classes derivadas|sim|não|sim|sim|
|Membros de qualquer outra classe|sim|não|não|no mesmo pacote|

## Multiplicidade

Quantos objetos de cada classe fazem parte dos relacionamentos e a multiplicidade pode ser expressa como:

- Exatamente um – 1
- Zero ou um – 0..1
- Muitos – 0..* ou *
- Um ou mais – 1..*
- Número exato – por exemplo, 3..4 ou 6
- Ou uma relação complexa – por exemplo, 0..1, 3..4, 6.* significaria qualquer número de objetos diferente de 2 ou 5

### Exemplo de multiplicidade

- Requisito: Um Aluno pode fazer muitos Cursos e muitos Alunos podem estar matriculados em um Curso.
- No exemplo abaixo, o  **diagrama de classes**  (à esquerda), descreve a declaração do requisito acima para o modelo estático, enquanto o diagrama de objetos (à direita) mostra o instantâneo (uma instância do diagrama de classes) da matrícula do curso para os cursos Engenharia de Software e Gerenciamento de Banco de Dados, respectivamente)

![Diagrama de objeto](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/09-class-diagram-to-object-diagram.png)

![](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/img_6216da89a5981.png)

## Exemplo de agregação – Computador e peças

- Uma agregação é um caso especial de associação que denota uma hierarquia “consiste em”
- A agregação é a classe pai, os componentes são as classes filhas

![Exemplo de agregação](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/10-aggregation-example.png)

## Exemplo de herança – taxonomia celular

- A herança é outro caso especial de uma associação que denota um “tipo de” hierarquia
- A herança simplifica o modelo de análise introduzindo uma taxonomia
- As classes filhas herdam os atributos e operações da classe pai.

![Exemplo de herança](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/11-inheritance-example.png)

## Diagrama de Classe – Exemplo de Ferramenta de Diagrama

Um diagrama de classes também pode ter notas anexadas a classes ou relacionamentos. As notas são mostradas em cinza.

![Exemplo de diagrama de classe](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/12-uml-class-diagram-example.png)

No exemplo acima:

Podemos interpretar o significado do diagrama de classes acima lendo os pontos a seguir.

1. Shape é uma classe abstrata. É mostrado em itálico.
2. Forma é uma superclasse. Círculo, Retângulo e Polígono são derivados de Forma. Em outras palavras, um Círculo é uma Forma. Esta é uma relação de generalização/herança.
3. Existe uma associação entre DialogBox e DataController.
4. A forma faz parte da janela. Esta é uma relação de agregação. Shape pode existir sem Window.
5. Ponto é parte do Círculo. Esta é uma relação de composição. Ponto não pode existir sem um Círculo.
6. A janela depende do evento. No entanto, Event não depende de Window.
7. Os atributos de Círculo são raio e centro. Esta é uma classe de entidade.
8. Os nomes dos métodos de Circle são area(), circum(), setCenter() e setRadius().
9. O parâmetro radius em Circle é um parâmetro in do tipo float.
10. O método area() da classe Circle retorna um valor do tipo double.
11. Os atributos e nomes de métodos de Rectangle estão ocultos. Algumas outras classes no diagrama também têm seus atributos e nomes de métodos ocultos.

## Exemplo de diagrama de classes: sistema de pedidos

![Exemplo de diagrama de classes: sistema de pedidos](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/17-class-diagram-example-order-system.png)

## Exemplo de diagrama de classe: GUI

Um diagrama de classes também pode ter notas anexadas a classes ou relacionamentos.

![Exemplo de diagrama de classe: GUI](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/18-uml-class-diagram-example-gui.png)

## Lidando com Sistema Complexo – Diagrama de Classes Múltiplas ou Únicas?

Inevitavelmente, se você estiver modelando um grande sistema ou uma grande área de negócios, haverá várias entidades que você deve considerar. Devemos usar vários ou um único diagrama de classes para modelar o problema? A resposta é:

- Em vez de modelar cada entidade e seus relacionamentos em um único diagrama de classes, é melhor usar vários diagramas de classes.
- Dividir um sistema em vários diagramas de classes torna o sistema mais fácil de entender, especialmente se cada diagrama for uma representação gráfica de uma parte específica do sistema.

## Perspectivas do Diagrama de Classes no Ciclo de Vida de Desenvolvimento de Software

Podemos usar diagramas de classes em diferentes fases de desenvolvimento de um  ciclo de vida de [desenvolvimento de software](https://en.wikipedia.org/wiki/Systems_development_life_cycle)  e, normalmente, modelando diagramas de classes em três perspectivas diferentes (níveis de detalhes) progressivamente à medida que avançamos:

**Perspectiva conceitual** : Os diagramas são interpretados como descrevendo coisas no mundo real. Assim, se você tomar a perspectiva conceitual, você desenha um diagrama que representa os conceitos no domínio em estudo. Esses conceitos naturalmente se relacionam com as classes que os implementam. A perspectiva conceitual é  **considerada independente da linguagem** .

**Perspectiva de especificação** : Os diagramas são interpretados como descrevendo abstrações de software ou componentes com especificações e interfaces, mas sem compromisso com uma implementação específica. Assim, se você tomar a perspectiva de especificação, estamos  **olhando para as interfaces do software** , não para a implementação.

**Perspectiva de implementação** : Os diagramas são interpretados como descrevendo implementações de software em uma determinada tecnologia e  [linguagem](https://en.wikipedia.org/wiki/Programming_language) . Assim, se você tomar a perspectiva de implementação, estamos  **olhando para a implementação de software** .

### Procurando uma ferramenta gratuita de diagramação de classes?

Visual Paradigm Online (VP Online) Free Edition é um software de desenho online gratuito que suporta diagramas de classe, outros diagramas UML, ferramentas ERD e ferramentas de organograma. Possui um editor simples, porém poderoso, que permite criar diagramas de classes de maneira rápida e fácil. Este editor UML gratuito não possui anúncios, prazos de acesso e restrições, por exemplo, sobre o número de diagramas, o número de formas, etc. Você possui os diagramas que cria para fins pessoais e não comerciais.

![Ferramenta de diagrama de aula online](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/02-class-diagram-example-car.png)

Procurando uma modelagem UML mais formal em seu desktop?

O Visual Paradigm Community Edition foi lançado desde 2004 para fornecer um  **software UML gratuito**  para uso exclusivo e não comercial, dando suporte a usuários que estavam dando seus primeiros passos na modelagem UML e que precisam de um software de modelagem UML gratuito e multiplataforma para uso pessoal, como como aplicar UML em projetos de estudantes.

![Tela de Paradigma Visual](https://www.cybermedian.com/pt/wp-content/uploads/sites/11/2022/02/why-vp.png)