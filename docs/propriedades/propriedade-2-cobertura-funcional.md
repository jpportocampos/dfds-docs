# 2- Propriedade: Cobertura funcional

Propriedade de conteúdo. O texto da DFDS deve descrever todas as funcionalidades da ferramenta e apresentar somente textos essenciais.

## Pré-Condições
Essa propriedade só é aplicável quando se tem alguma funcionalidade na ferramenta.

## Atributos

### Atributos de Conteúdo

#### 2.1 Completude
A cobertura funcional da ferramenta é considerada completa quando todas as funcionalidades da ferramenta estão descritas na DFDS. Ou seja, qualquer funcionalidade (métodos, implementações, variáveis, etc.) deve estar descrita e explicada considerando o contexto de aplicação da ferramenta.

**Consequências:**  
Quando a cobertura funcional não está completa, a DFDS não possui todas as informações necessárias para o entendimento da ferramenta devido à falta de informações sobre as suas funcionalidades.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, todas as funcionalidades possuem explicação.

**Exemplo de aplicação ruim:**  
As documentações de exemplos não apresentam incompletude em relação à cobertura funcional. Usando a documentação da biblioteca PIL como exemplo, caso uma funcionalidade existente não houvesse sua explicação presente na DFDS, a cobertura funcional estaria incompleta

**Verificação:**  
As funcionalidades da ferramenta e seu uso estão descritos na DFDS.

---

#### 2.2 Corretude
A cobertura funcional da ferramenta é considerada correta quando as descrições de implementação não apresentam erros de uso e de funcionalidade.

**Consequências:**  
Quando a cobertura funcional não está correta, a DFDS apresenta informações ambíguas ou equivocadas sobre o uso da ferramenta devido à presença de informações equivocadas sobre as funcionalidades da ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, a cobertura funcional não apresenta uma descrição com erros, por exemplo, a função “open” está descrita corretamente:

![Screenshot](../imagens/img (17).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem problema de incorreção. Usando a cobertura funcional do exemplo anterior, estaria incorreta se omitisse um dos parâmetros ou o descrevesse incorretamente.

**Verificação:**  
Nenhum trecho apresenta erro de uso e de funcionalidade em seu texto.

---

#### 2.3 Relevância
A cobertura funcional da ferramenta é considerada relevante quando as funcionalidades da ferramenta estão descritas considerando casos reais de uso da ferramenta. Ou seja, a descrição das funcionalidades usa exemplos e terminologia do contexto de aplicação da ferramenta.

**Consequências:**  
Quando a cobertura funcional não é relevante, a informação é apresentada sem considerar o contexto de aplicação da ferramenta, criando uma dificuldade para compreender os cenários de uso das funcionalidades.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL, a função “blend” possui cobertura funcional relevante por utilizar terminologia de acordo com desenvolvimento Python:

![Screenshot](../imagens/img (19).png)

**Exemplo de aplicação ruim:**  
Não há falta de relevância nas documentações de exemplo, porém se no exemplo anterior acima da função “blend” faltasse relevância, seria por exemplo:

![Screenshot](../imagens/img (20).png)

**Verificação:**  
Os textos de cobertura funcional apresentam exemplos e utilizam terminologia alinhados com casos reais de uso da ferramenta.

---

#### 2.4 Contextualização
A cobertura funcional da ferramenta é considerada contextualizada quando fica claro em que contexto de uso e implementação a funcionalidade é utilizada pela ferramenta. Ou seja, os textos de cobertura funcional explicita como e em que contextos se utiliza a funcionalidade descrita.

**Consequências:**  
Quando a cobertura funcional não está contextualizada, a informação sobre as funcionalidades da ferramenta é apresentada sem indicar o contexto de uso e implementação das funcionalidades, deixando ambíguo o entendimento sobre em que cenários de uso utilizar as funcionalidades descritas.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL as funcionalidades são descritas em uma seção chamada “Functions”. Na imagem, apenas a função Image.open está visivel, mas as outras funções existentes são descritas na mesma seção da documentação:

![Screenshot](../imagens/img (22).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios, na seção da funcionalidade “Interceptadores”, a cobertura funcional é apresentada como comentários de código no exemplo de código, dificultando a identificação de qual texto é a cobertura funcional:

![Screenshot](../imagens/img (115).png)

**Verificação:**  
Os textos de cobertura funcional explicitam os cenários de uso e aplicação da funcionalidade descrita.

---

### Atributos de Apresentação

#### 2.5 Boa legibilidade
A cobertura funcional da ferramenta é considerada com boa legibilidade quando seu texto está bem escrito (fácil de entender) e não possui erros gramaticais.

**Consequências:**  
Quando a cobertura funcional não está com boa legibilidade, a informação sobre as funcionalidades da ferramenta se torna difícil de compreender devido a dificuldade de leitura da explicação.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL os textos de cobertura funcional estão bem escritos e não apresentam erros de gramática:

![Screenshot](../imagens/img (23).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem legibilidade ruim na cobertura funcional, um exemplo de legibilidade ruim seria se o exemplo anterior apresentasse erros gramaticais e frases mal escritas.

**Verificação:**  
Os textos de cobertura funcional são bem escritos e não apresentam erros gramaticais.

---

#### 2.6 Clareza
A cobertura funcional da ferramenta é considerada clara quando é explicitado que o texto apresentado é uma explicação de funcionalidade que se refere ao uso e aplicação de uma funcionalidade específica da ferramenta.

**Consequências:**  
Quando a cobertura funcional não está clara, há dificuldade para perceber que o texto apresenta uma cobertura funcional, dificultando o entendimento da ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL as funcionalidades são explicitamente definidas ao serem apresentadas com título em formato de função e o texto conter campos que definem os parâmetros e retorno das funcionalidades:

![Screenshot](../imagens/img (25).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Matplotlib na explicação de “Figures” há tanto explicações conceituais quanto explicações funcionais, não deixando claro qual parte do texto apresenta qual explicação:

![Screenshot](../imagens/img (113).png)

**Verificação:**  
Os textos de cobertura funcional explicitam que seu conteúdo é uma explicação de funcionalidade.

---

#### 2.7 Estrutura organizada
A cobertura funcional é considerada organizada estruturalmente quando existe uma estrutura padrão para todos os textos de cobertura funcional. Ou seja, todas as explicações de funcionalidade estão estruturadas da mesma forma em toda a DFDS.

**Consequências:**  
Quando a cobertura funcional não está organizada estruturalmente, há dificuldade para encontrar informações sobre as funcionalidades da ferramenta devido à dificuldade de identificar o texto que se refere a esse conteúdo.

**Exemplo de boa aplicação:**  
Todas as definições de funcionalidades estão em um mesmo formato na documentação da ferramenta PIL:

![Screenshot](../imagens/img (27).png)

**Exemplo de aplicação ruim:**  
Em [3] as funcionalidades são apresentadas em diferentes formatações, na primeira imagem, a explicação funcional está em formato de texto, enquanto na segunda, em comentários de código:

![Screenshot](../imagens/img (116).png)

![Screenshot](../imagens/img (117).png)

**Verificação:**  
Todos os textos de cobertura funcional estão estruturados no mesmo formato.
