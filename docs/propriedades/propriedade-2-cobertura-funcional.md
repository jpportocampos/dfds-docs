# Propriedade 2: Cobertura funcional

Propriedade de conteúdo. O texto da DFDS deve descrever todas as funcionalidades da ferramenta sem apresentar texto não essencial. [Arya et al. 2024, Tiarks and Maalej 2014, Arya et al. 2022]

https://express-validator.github.io/docs

## Pré-Condições
Essa propriedade só é aplicável quando se tem alguma funcionalidade na ferramenta.

## Atributos

### Atributos de Conteúdo

#### 2.1 Completude
A cobertura funcional da ferramenta é considerada completa quando todas as funcionalidades da ferramenta estão descritas na DFDS. Ou seja, qualquer funcionalidade (métodos, implementações, variáveis, etc.) deve estar descrita e explicada considerando o contexto de aplicação da ferramenta.

**Consequências:**  
Quando a cobertura funcional não está completa, há falta de entendimento sobre as funcionalidades da ferramenta devido à falta de informações.

**Exemplo de boa aplicação:**  
Em [1] todas as funcionalidades possuem explicação.

**Exemplo de aplicação ruim:**  
As documentações de exemplos estão completas em relação à cobertura funcional. Se em [2] não houvesse a explicação da funcionalidade de “Schema”, a cobertura funcional estaria incompleta.

**Verificação:**  
As funcionalidades da ferramenta e seu uso estão descritos na DFDS.

---

#### 2.2 Corretude
A cobertura funcional da ferramenta é considerada correta quando as descrições de implementação não apresentam erros de uso e de funcionalidade.

**Consequências:**  
Quando a cobertura funcional não está correta, há entendimento equivocado sobre as funcionalidades da ferramenta devido à presença de informações equivocadas.

**Exemplo de boa aplicação:**  
Em [1], a cobertura funcional não apresenta uma descrição com erros, por exemplo, a função “open” está descrita corretamente:

https://pillow.readthedocs.io/en/stable/index.html  
https://express-validator.github.io/docs  
https://pillow.readthedocs.io/en/stable/index.html

**Imagem presente no PDF. Inserir aqui.**

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem problema de incorreção, porém em [1], usando a cobertura funcional do exemplo anterior, estaria incorreta se omitisse um dos parâmetros ou o descrevesse incorretamente.

**Verificação:**  
Todos os trechos de cobertura funcional não apresentam erros de uso e de funcionalidade em seu texto.

---

#### 2.3 Relevância
A cobertura funcional da ferramenta é considerada relevante quando as funcionalidades da ferramenta estão descritas considerando casos reais de uso da ferramenta. Ou seja, a descrição das funcionalidades usa exemplos e terminologia do contexto de aplicação da ferramenta.

**Consequências:**  
Quando a cobertura funcional não está relevante, há falta de entendimento sobre as funcionalidades da ferramenta devido à informação apresentada ser insuficiente para representar o uso da ferramenta.

**Exemplo de boa aplicação:**  
Em [1] a função “blend” possui cobertura funcional relevante por utilizar terminologia de acordo com desenvolvimento Python:

https://pillow.readthedocs.io/en/stable/index.html  
https://pillow.readthedocs.io/en/stable/index.html

**Imagem presente no PDF. Inserir aqui.**

**Exemplo de aplicação ruim:**  
Não há falta de relevância nas documentações de exemplo, porém se no exemplo de [1] acima da função “blend” faltasse relevância, seria por exemplo:

**Imagem presente no PDF. Inserir aqui.**

**Verificação:**  
Os textos de cobertura funcional apresentam exemplos e utilizam terminologia alinhados com casos reais de uso da ferramenta.

---

#### 2.4 Contextualização
A cobertura funcional da ferramenta é considerada contextualizada quando fica claro em que contexto de uso e implementação a funcionalidade é utilizada pela ferramenta. Ou seja, os textos de cobertura funcional explicita como e em que contextos se utiliza a funcionalidade descrita.

**Consequências:**  
Quando a cobertura funcional não está contextualizada, há entendimento equivocado sobre as funcionalidades da ferramenta devido à informação apresentada ser ambígua sobre o cenário de uso da funcionalidade.

**Exemplo de boa aplicação:**  
Em [1] a cobertura funcional está em uma seção chamada “Functions”:

https://pillow.readthedocs.io/en/stable/index.html  
https://pillow.readthedocs.io/en/stable/index.html

**Imagem presente no PDF. Inserir aqui.**

**Exemplo de aplicação ruim:**  
Em [2], na seção da funcionalidade “Validation Chain”, o conceito de “Validation” é explicado junto com a funcionalidade, dificultando a identificação de que texto é a cobertura funcional.

**Imagem presente no PDF. Inserir aqui.**

**Verificação:**  
Os textos de cobertura funcional explicitam os cenários de uso e aplicação da funcionalidade descrita.

---

### Atributos de Apresentação

#### 2.5 Boa legibilidade
A cobertura funcional da ferramenta é considerada com boa legibilidade quando seu texto está bem escrito (fácil de entender) e não possui erros gramaticais.

**Consequências:**  
Quando a cobertura funcional não está com boa legibilidade, há dificuldade para encontrar informações sobre as funcionalidades da ferramenta devido a dificuldade de leitura do conteúdo.

https://express-validator.github.io/docs

**Exemplo de boa aplicação:**  
Em [1] os textos de cobertura funcional estão bem escritos e não apresentam erros de gramática.

**Imagem presente no PDF. Inserir aqui.**

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem legibilidade ruim na cobertura funcional, um exemplo de legibilidade ruim seria se em [2] a seguinte cobertura funcional fosse usada:

**Imagem presente no PDF. Inserir aqui.**

**Verificação:**  
Os textos de cobertura funcional são bem escritos e não apresentam erros gramaticais.

---

#### 2.6 Clareza
A cobertura funcional da ferramenta é considerada clara quando é explicitado que o texto apresentado é uma explicação de funcionalidade que se refere ao uso e aplicação de uma funcionalidade específica da ferramenta.

**Consequências:**  
Quando a cobertura funcional não está clara, há dificuldade para encontrar informações sobre as funcionalidades da ferramenta devido à dificuldade de identificar que o texto se refere a esse conteúdo.

**Exemplo de boa aplicação:**  
Em [1] as funcionalidades são explicitamente definidas ao serem apresentadas com título em formato de função e o texto conter campos que definem os parâmetros e retorno das funcionalidades:

https://pillow.readthedocs.io/en/stable/index.html  
https://express-validator.github.io/docs  
https://pillow.readthedocs.io/en/stable/index.html

**Imagem presente no PDF. Inserir aqui.**

**Exemplo de aplicação ruim:**  
Em [2] as coberturas funcionais não são explicitadas como explicações de funcionalidades, por exemplo, validation chain é uma funcionalidade, mas em sua explicação ela é dita como um conceito.

**Imagem presente no PDF. Inserir aqui.**

**Verificação:**  
Os textos de cobertura funcional explicitam que seu conteúdo é uma explicação de funcionalidade.

---

#### 2.7 Estrutura organizada
A cobertura funcional é considerada em uma estrutura organizada quando existe uma estrutura padrão para todos os textos de cobertura funcional. Ou seja, todas as explicações de funcionalidade estão estruturadas da mesma forma em toda a DFDS.

**Consequências:**  
Quando a cobertura funcional não está em uma estrutura organizada, há dificuldade para encontrar informações sobre as funcionalidades da ferramenta devido à dificuldade de encontrar o texto que se refere a esse conteúdo.

**Exemplo de boa aplicação:**  
Todas as definições de funcionalidades estão em um mesmo formato em [1]:

https://express-validator.github.io/docs  
https://pillow.readthedocs.io/en/stable/index.html

**Imagem presente no PDF. Inserir aqui.**

**Exemplo de aplicação ruim:**  
Em [2] as funcionalidades são apresentadas em diferentes formatações, na primeira imagem, a primeira subseção é uma explicação da funcionalidade, enquanto na segunda, a primeira subseção é uma exemplo:

https://express-validator.github.io/docs

**Imagem presente no PDF. Inserir aqui.**

**Verificação:**  
Todos os textos de cobertura funcional estão estruturados no mesmo formato.
