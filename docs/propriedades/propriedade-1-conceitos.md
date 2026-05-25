# 1- Propriedade: Descrição dos conceitos da ferramenta

Descrição dos conceitos externos à ferramenta modelados por ela, explicando como estes conceitos são aplicados pela ferramenta.

## Pré-Condições
Essa propriedade só é aplicável quando se tem alguma funcionalidade da ferramenta que modela um conceito externo, ou seja, que existe além da ferramenta.

## Atributos

### Atributos de Conteúdo

#### 1.1 Completude
A descrição dos conceitos da ferramenta é considerada completa quando todos os conceitos modelados pela ferramenta estão descritos na DFDS. Ou seja, qualquer conceito externo à ferramenta (que não está relacionado à implementação) deve estar descrito e explicado considerando o contexto de aplicação da ferramenta.

**Consequências:**  
Quando a explicação conceitual não está completa, a DFDS não possui todas as informações necessárias para o entendimento da ferramenta devido à falta de informações sobre o domínio de aplicação dela.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca Pillow (PIL Fork), uma biblioteca de manipulação de imagem, os conceitos utilizados estão descritos e podem ser encontrados na seção “Concepts” da documentação.

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Pillow (PIL Fork), mesmo existindo a seção “Concepts”, caso algum conceito utilizado não fosse descrito, faltaria completude.

**Verificação:**  
Se para entender o uso de uma funcionalidade da ferramenta é necessário entender algum conceito externo à ferramenta, esse conceito deve ser definido na DFDS.

---

#### 1.2 Corretude
A descrição dos conceitos da ferramenta é considerada correta quando não apresenta erros conceituais. Ou seja, a descrição está de acordo com a definição formal do conceito modelado.

**Consequências:**  
Quando a explicação conceitual não está correta, a DFDS apresenta informações ambíguas ou equivocadas sobre o domínio da ferramenta.

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
Na documentação da biblioteca Pillow (PIL Fork), a a definição de  “Bands” possui relevância por definir este conceito de acordo com o seu uso conceitual na ferramenta. Isso é feito nas frases “The Python Imaging Library allows you to store several bands in a single image, provided they all have the same dimensions and depth. For example, a PNG image might have ‘R’, ‘G’, ‘B’, and ‘A’ bands for the red, green, blue, and alpha transparency values.”:

![Screenshot](../imagens/img (1).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem casos de falta de relevância nas explicações conceituais. Usando o exemplo anterior, caso a definição de “Bands” não utilizasse as frases destacadas no exemplo anterior, faltaria relevância.

**Verificação:**  
As explicações conceituais devem apresentar exemplos e vocabulário alinhados com casos reais de uso da ferramenta e utilizar terminologia relacionada com a situação ou cenário de aplicação da ferramenta.

---

#### 1.4 Contextualização
A descrição dos conceitos da ferramenta é considerada contextualizada quando fica claro qual funcionalidade da ferramenta modela o conceito.

**Consequências:**  
Quando a explicação conceitual não está contextualizada, a informação sobre o domínio da ferramenta é apresentada sem indicar a funcionalidade relacionada a ela, deixando ambíguo o entendimento sobre como o conceito explicado é utilizado pela ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, a definição de Bands explicita, na última frase, qual funcionalidade (nesse caso, um método) utiliza esse conceito:

![Screenshot](../imagens/img (1).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem casos de falta de contextualização nas explicações conceituais. Utilizando o exemplo acima, caso a última frase da definição de Bands fosse removida, não haveria contextualização:

![Screenshot](../imagens/img (1) crop.png)

**Verificação:**  
As explicações conceituais devem estar diretamente relacionadas com funcionalidades da ferramenta.

---

### Atributos de Apresentação

#### 1.5 Legibilidade
A descrição dos conceitos da ferramenta é considerada como tendo boa legibilidade quando seu texto está bem escrito (utiliza fontes legíveis, bom contraste, parágrafos curtos, frases diretas, voz ativa) e não possui erros gramaticais.

**Consequências:**  
Quando a explicação conceitual não está com boa legibilidade, a informação sobre o conceito se torna difícil de compreender devido a dificuldade de leitura da explicação.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, as descrições conceituais possuem textos com fontes legíveis, bom contraste, parágrafos curtos, frases diretas, voz ativa e não apresentam erros de gramática:

![Screenshot](../imagens/img (5).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem casos de legibilidade ruim. Utilizando o exemplo acima, seria um caso de legibilidade ruim caso o texto de “Coordinate system” apresentasse erros gramaticais e frases mal escritas:

![Screenshot](../imagens/img (129).png)

**Verificação:**  
Os textos dos conceitos modelados são bem escritos e não apresentam erros gramaticais.

---

#### 1.6 Clareza
A descrição dos conceitos da ferramenta é considerada clara quando é explicitado para o leitor que o texto apresentado é uma explicação conceitual.

**Consequências:**  
Quando a explicação conceitual não está clara, há dificuldade para perceber que o texto apresenta uma explicação conceitual, dificultando o entendimento da ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, as definições de conceitos ficam em uma seção de nome “Concepts”, explicitando que o texto dessa seção é de definições conceituais:

![Screenshot](../imagens/img (7).png)

**Exemplo de aplicação ruim:**  
Na documentação da biblioteca scikit-learn, na seção “Linear Models”, as descrições de conceitos e de funcionalidades estão misturados sem nenhuma indicação qual parte do texto é uma explicação conceitual

**Verificação:**  
As explicações conceituais explicitam que seu texto é uma explicação conceitual.

---

#### 1.7 Organização da estrutura
A descrição dos conceitos da ferramenta é considerada organizada estruturalmente quando existe uma estrutura padrão para todas as explicações conceituais. Ou seja, todas as explicações de conceito possuem um mesmo padrão de formatação em seu texto em toda a DFDS.

**Consequências:**  
Quando a explicação conceitual não está organizada estruturalmente, há dificuldade para encontrar informações sobre os conceitos da ferramenta devido à diferença de formatação entre diferentes textos de explicações conceituais.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL, as definições conceituais seguem um mesmo padrão de formatação:

![Screenshot](../imagens/img (11).png)

**Exemplo de aplicação ruim:**  
Na documentação da biblioteca Matplotlib, as definições conceituais estão em diferentes formatações. Na primeira imagem, a explicação conceitual é apresentada junto com explicações de funcionalidades, na segunda não há nenhuma explicação de funcionalidade, levando a dois padrões diferentes de apresentação do conceito:

![Screenshot](../imagens/img (113).png)

![Screenshot](../imagens/img (114).png)

**Verificação:**  
Todas as explicações conceituais estão estruturadas no mesmo formato.
