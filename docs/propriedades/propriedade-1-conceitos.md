# 1- Propriedade: Descrição dos conceitos da ferramenta

Propriedade de conteúdo. Descrição dos conceitos externos à ferramenta modelados por ela, explicando como estes conceitos são aplicados pela ferramenta.

## Pré-Condições
Essa propriedade só é aplicável quando se tem alguma funcionalidade da ferramenta que modela um conceito externo, ou seja, que existe além da ferramenta.

## Atributos

### Atributos de Conteúdo

#### 1.1 Completude
A descrição dos conceitos da ferramenta é considerada completa quando todos os conceitos modelados pela ferramenta estão descritos na DFDS. Ou seja, qualquer conceito externo à ferramenta (que não está relacionado à implementação) deve estar descrito e explicado considerando o contexto de aplicação da ferramenta.

**Consequências:**  
Quando a explicação conceitual não está completa, a DFDS não possui todas as informações necessárias para o entendimento da ferramenta devido à falta de informações sobre o domínio de aplicação dela.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca Pillow (PIL Fork), uma biblioteca de manipulação de imagem, todos os conceitos utilizados estão descritos e podem ser encontrados na seção “Concepts” da documentação.

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios, uma biblioeca de cliente HTTP para o node.js, apesar de que na introdução da documentação é dito que a biblioteca é baseada em promessas, em nenhum ponto da documentação esse conceito é descrito.

**Verificação:**  
Se para entender o uso de uma funcionalidade da ferramenta é necessário entender algum conceito externo à ferramenta, esse conceito deve ser explicado na DFDS.

---

#### 1.2 Corretude
A descrição dos conceitos da ferramenta é considerada correta quando não apresenta erros conceituais. Ou seja, a descrição está de acordo com a definição formal do conceito modelado.

**Consequências:**  
Quando a explicação conceitual não está correta, a DFDS apresenta informações ambíguas ou equivocadas sobre o domínio da ferramenta devido à presença de informações equivocadas sobre o domínio de aplicação da ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca Pillow (PIL Fork), os conceitos estão descritos corretamente, seguindo a definição formal deles. Como exemplo, a definição de “Bands”:

![Screenshot](../imagens/img (1).png)

**Exemplo de aplicação ruim:**  
As documentações escolhidas para os exemplos não apresentam problemas de incorreção, logo, usando o exemplo acima, seria incorreto descrever “Bands” utilizando a descrição formal de “Colors”

**Verificação:**  
As explicações conceituais devem estar de acordo com as definições formais dos conceitos modelados

---

#### 1.3 Relevância
A descrição dos conceitos da ferramenta é considerada relevante quando os conceitos modelados pela ferramenta estão descritos considerando casos reais de uso da ferramenta. Ou seja, a descrição dos conceitos externos à ferramenta usa exemplos e terminologia relacionada ao contexto de aplicação da ferramenta.

**Consequências:**  
Quando a explicação conceitual não é relevante, a informação é apresentada sem considerar o contexto de aplicação da ferramenta, criando uma dificuldade para atribuir o conceito à implementação.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca Pillow (PIL Fork), a a definição de “Size” possui relevância por utilizar terminologias relacionadas a programação em Python, como “attribute” e “tuple”:

![Screenshot](../imagens/img (3).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem casos de falta de relevância nas explicações conceituais. Usando o exemplo anterior, caso a definição de Size não utilizasse terminologias relacionadas a programação em Python, faltaria relevância:

![Screenshot](../imagens/img (4).png)

**Verificação:**  
As explicações conceituais devem apresentar exemplos e vocabulário alinhados com casos reais de uso da ferramenta e utilizar terminologia relacionada com a situação ou cenário de aplicação da ferramenta.

---

#### 1.4 Contextualização
A descrição dos conceitos da ferramenta é considerada contextualizada quando fica claro qual funcionalidade da ferramenta modela o conceito. Ou seja, a descrição dos conceitos explicita quais funcionalidades da ferramenta utilizam o conceito descrito.

**Consequências:**  
Quando a explicação conceitual não está contextualizada, a informação sobre o domínio da ferramenta é apresentada sem indicar a funcionalidade relacionada a ela, deixando ambíguo o entendimento sobre como o conceito explicado é utilizado pela ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, a definição de Bands explicita qual funcionalidade (nesse caso, um método) utiliza o conceito explicado na última frase:

![Screenshot](../imagens/img (1).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem casos de falta de contextualização nas explicações conceituais. Utilizando o exemplo acima, caso a última frase da definição de Bands fosse removida, não haveria contextualização:

![Screenshot](../imagens/img (1) crop.png)

**Verificação:**  
As explicações conceituais explicitam quais funcionalidades utilizam os conceitos explicados.

---

### Atributos de Apresentação

#### 1.5 Boa legibilidade
A descrição dos conceitos da ferramenta é considerada com boa legibilidade quando seu texto está bem escrito (fácil de entender) e não possui erros gramaticais.

**Consequências:**  
Quando a explicação conceitual não está com boa legibilidade, a informação sobre o conceito se torna difícil de compreender devido a dificuldade de leitura da explicação.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, as descrições conceituais possuem textos bem escritos e não apresentam erros de gramática:

![Screenshot](../imagens/img (5).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem casos de legibilidade ruim. Utilizando o exemplo acima, seria um caso de legibilidade ruim caso o texto de “Coordinate system” apresentasse erros gramaticais e frases mal escritas.

**Verificação:**  
Os textos dos conceitos modelados são bem escritos e não apresentam erros gramaticais.

---

#### 1.6 Clareza
A descrição dos conceitos da ferramenta é considerada clara quando é explicitado que o texto apresentado é uma explicação conceitual que se refere a um conceito externo à ferramenta.

**Consequências:**  
Quando a explicação conceitual não está clara, há dificuldade para perceber que o texto apresenta uma explicação conceitual, dificultando o entendimento da ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, as definições de conceitos ficam em uma seção de nome “Concepts”, explicitando que o texto dessa seção é de definições conceituais:

![Screenshot](../imagens/img (7).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios, na introdução, o conceito de “isomórfico” é explicado rapidamente entre parênteses e sem nenhuma indicação que é uma explicação conceitual:

![Screenshot](../imagens/img.png)

**Verificação:**  
As explicações conceituais explicitam que seu texto é uma explicação conceitual.

---

#### 1.7 Estrutura organizada
A descrição dos conceitos da ferramenta é considerada organizada estruturalmente quando existe uma estrutura padrão para todas as explicações conceituais. Ou seja, todas as explicações de conceito estão estruturadas da mesma forma em toda a DFDS.

**Consequências:**  
Quando a explicação conceitual não está organizada estruturalmente, há dificuldade para encontrar informações sobre o domínio da ferramenta devido à dificuldade de identificar o texto que se refere a esse conteúdo.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, as definições conceituais seguem um mesmo padrão de formatação:

![Screenshot](../imagens/img (11).png)

**Exemplo de aplicação ruim:**  
Na documentação da biblioteca Matplotlib, as definições conceituais estão em diferentes formatações. No primeiro print, a explicação conceitual é apresentada junto com explicações de funcionalidades, no segundo de forma independente:

![Screenshot](../imagens/img (113).png)

![Screenshot](../imagens/img (114).png)

**Verificação:**  
Todas as explicações conceituais estão estruturadas no mesmo formato.
