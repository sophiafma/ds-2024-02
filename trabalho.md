## Repositório para registrar dúvidas, questões, anotações, links e assuntos sobre o trabalho prático 

#### Tema: Attribute Driven Design (ADD) 

##### Links:
https://higordiego.medium.com/projetando-arquitetura-de-software-attribute-driven-design-add-e5fb0ec4b5ee \
https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=8661a83e778314709a610940af04296647a5c0c4 \
https://edisciplinas.usp.br/pluginfile.php/5922722/mod_resource/content/1/2013%20-%20Book%20-%20Bass%20%20Kazman-Software%20Architecture%20in%20Practice%20%281%29.pdf \
https://insights.sei.cmu.edu/library/attribute-driven-design-add-version-20/ 

##### Dúvidas: 
O que são atributos de qualidade de um sistema?\
Atributo de qualidade é uma propriedade mensurável ou testável de um sistema que é usado para indicar quão bem o sistema satisfaz as necessidades de suas partes interessadas. Você pode pensar em um atributo de qualidade como uma forma de  medir a “qualidade” de um produto ao longo de alguma dimensão de interesse para uma parte interessada.\
A norma ISO/IEC 9126 (NBR 13596) fornece um modelo de propósito geral o qual define 6 categorias de características de qualidade de software, que são: funcionalidade, confiabilidade, usabilidade, eficiência, manutenibilidade e portabilidade. Esse método é apropriado para qualquer atributo de qualidade, mas tem sido elaborado particularmente para esses atributos definidos pela ISO.\
O que é time-to-market?\
Time to Market (TTM) é um conceito crucial no desenvolvimento de sistemas, que se refere ao tempo necessário para transformar uma ideia em um produto totalmente funcional e disponível para o mercado. Ele representa a velocidade com que uma empresa pode conceber, desenvolver e lançar uma solução no mercado.

##### Assuntos: 
A origem do Attribute Driven Design (ADD) pode ser rastreada até a década de 90, quando foi desenvolvido pelo Software Engineering Institute (SEI) do Carnegie Mellon University. Ele foi criado como uma abordagem para o projeto de software que se concentra em identificar e modelar atributos (características) de um sistema que são importantes para seus usuários e stakeholders, com o objetivo de criar sistemas que sejam altamente adaptáveis, fáceis de manter e escaláveis, e que atendam às necessidades dos usuários e stakeholders. \
De acordo com o Carnegie Mellon Software Engineering Institute, instituto desenvolvedor do método ADD, ADD é um método para projetar a arquitetura de software de um sistema ou coleção de sistemas com base em uma articulação explícita das metas de atributos de qualidade para o sistema. O método segue um processo de design recursivo que decompõe um sistema ou elemento de sistema por aplicando táticas arquitetônicas e padrões que satisfaçam seus requisitos de condução comentários. O ADD segue essencialmente uma estratégia de “Planejar, Fazer e Verificar”:
1. Planejar: atributos de qualidade e restrições de projeto são considerados para selecionar quais tipos de elementos serão usados ​​na arquitetura.
2. Do: Os elementos são instanciados para satisfazer os requisitos dos atributos de qualidade assim como requisitos funcionais.
3. Verificação: O projeto resultante é analisado para determinar se os requisitos foram atentidos.\
Este processo é repetido até que todos os requisitos arquitetônicos significativos sejam atendidos.\
O método tem sido usado para projetar arquiteturas de software de produtos desde sistemas embarcados até sistemas de informação.
De acordo com o livro “Quality Attribute Design Primitives”, o método ADD é baseado no entendimento da relação entre qualidades de um software e os mecanismos arquisteturais usados para atingir tais qualidades. Esse método tem como foco atingir duas metas principais: dar suporte aos estágios iniciais do processo de design, nos quais a capacidade de atingir os atributos de qualidade desejados é determinada; e permitir que o projeto comece cedo o suficiente no ciclo de vida para apoiar as modernas necessidades time-to-market.\
Antes de iniciar o esboço da arquitetura, deve-se avaliar os atributos de qualidade como: escopo do sistema, interfaces internas/externas, objetivo do projeto, requisitos funcionais, cenários de qualidade, restrições e preocupações.\
A imagem abaixo indica as etapas e o processo iterativo que o método propôe:\
![diagrama das etapas](https://miro.medium.com/v2/resize:fit:720/format:webp/0*N_m9jvFkwpekvAOp.png)
\
Pode-se perceber, através da imagem, que o processo começa com a revisão de entradas, garantindo que as etapas de finalidade do projeto, requisitos funcionais e preocupações anteriores estejam claras. Em seguida, escolhe-se um elemento do sistema para ser o foco da iteração. Esse elemento é refinado, priorizando os requisitos dos stakeholders. Após isso, define-se o conceito de design, identificando os principais tipos de elementos e seus relacionamentos. Os elementos de software são então atribuídos responsabilidades baseadas nos requisitos funcionais. A seguir, as interfaces são detalhadas, incluindo sintaxe, semântica, dados e atributos de qualidade. Finalmente, é feita uma análise de performance para verificar se é necessário voltar às etapas anteriores ou seguir para a próxima iteração.\
O Attribute Driven Design foi originalmente desenvolvido para aplicações de software de missão crítica, como sistemas de controle de tráfego aéreo e sistemas de gerenciamento de energia, mas tem sido utilizado em uma variedade de outros tipos de projetos de software desde então. Ele tem sido amplamente utilizado e pesquisado no setor aeroespacial, militar e de defesa, mas também tem aplicações em outros setores, incluindo transporte, saúde, finanças e tecnologia da informação.\
O método foca em identificar e modelar atributos importantes para usuários e stakeholders, garantindo que o sistema atenda às suas expectativas. Ele permite uma arquitetura flexível e adaptável, facilitando a manutenção e a escalabilidade. Além disso, promove uma comunicação eficaz entre desenvolvedores e stakeholders, alinhando expectativas e contribuindo para a redução de custos a longo prazo.\
Assim, podemos concluir que o ADD é uma abordagem útil para o projeto de software, pois permite que os desenvolvedores criem sistemas que sejam altamente adaptáveis, fáceis de manter e escaláveis, e que atendam às necessidades dos usuários e stakeholders.

##### Referências:
- BASS; CLEMENTS; KAZMAN, 2013) BASS, L.; CLEMENTS, P.; KAZMAN, R. Software Architecture in Practice Architecture. 3a
Edição. SEI Series in Software Engineering, 2013.
- Bass, L., Klein, M., Bachmann, F. “Quality Attribute Design Primitives” CMU/SEI-2000-TN-017, Carnegie Mellon, Pittsburgh, December, 2000.


