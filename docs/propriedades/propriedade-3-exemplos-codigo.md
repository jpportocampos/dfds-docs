# 3- Propriedade: Exemplos e fragmentos de código

Propriedade de conteúdo. Trechos de código utilizados para demonstrar o uso de uma ou mais funcionalidades da ferramenta.

## Pré-Condições
Essa propriedade só é aplicável quando se tem alguma funcionalidade da ferramenta que pode ser apresentada em exemplos de código.

## Atributos

### Atributos de Conteúdo

#### 3.1 Completude
Um exemplo de código é considerado completo quando o código presente nele possui todos os seus elementos (funções, variáveis, etc.) inicializados ou contextualizados por comentários.

**Consequências:**  
Quando um exemplo de código não está completo, a DFDS não possui todas as informações necessárias para o entendimento da ferramenta devido à falta de informações sobre o uso das funcionalidades da ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL, o seguinte exemplo de código está completo por não só inicializar todos os elementos presentes mas também por demonstrar os imports:

![Screenshot](../imagens/img (31).png)

**Exemplo de aplicação ruim:**  
As dcumentações de exemplo não possuem casos de incompletude em exemplos de código. Usando o exemplo anterior, caso o import não estivesse presente no exemplo de código, ele estaria incompleto.

**Verificação:**  
Todos os elementos de código presentes nos exemplos de código estão inicializados ou contextualizados por comentários.

---

#### 3.2 Corretude
Um exemplo de código é considerado correto quando o código presente nele não apresenta erros de sintaxe e quando, ao copiar e colar em um ambiente configurado corretamente, o código compila sem erros.

**Consequências:**  
Quando um exemplo de código não está correto, a DFDS apresenta informações ambíguas ou equivocadas sobre o uso da ferramenta devido à presença de informações equivocadas presentes no exemplo incorreto.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL, o seguinte exemplo de código está correto pois não apresenta erro de sintaxe e ao copiar e colar em um ambiente Python com a biblioteca instalada, ele compilaria sem erros:

![Screenshot](../imagens/img (32).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de exemplos de código incorretos. Usando o exemplo anterior, caso houvesse nele um erro de sintaxe, como utilizar “;” ao invés de “,” na definição da variável “size”, ele estaria incorreto.

**Verificação:**  
Todos os exemplos de código apresentam código sem erros de sintaxe e que, ao copiar e colar em um ambiente devidamente configurado, o código compila sem apresentar erros e o resultado da compilação é igual ao apontado na DFDS.

---

#### 3.3 Relevância
Um exemplo de código é considerado relevante quando ele representa um caso real de uso da ferramenta.

**Consequências:**  
Quando um exemplo de código não é relevante, a informação é apresentada sem considerar o contexto de aplicação da ferramenta, criando uma dificuldade para compreender os cenários reais de uso das funcionalidades representadas no exemplo de código.

**Exemplo de boa aplicação:**  
O seguinte exemplo de código da documentação da ferramenta PIL possui relevância pois demonstra um caso de uso real da ferramenta, no caso, converter um arquivo de imagem para o formato jpeg:

![Screenshot](../imagens/img (33).png)

**Exemplo de aplicação ruim:**  
O seguinte exemplo de código da documentação da ferramenta PIL não é relevante pois não apresenta um caso real de uso da ferramenta:

![Screenshot](../imagens/img (34).png)

**Verificação:**  
Todos os exemplos de código apresentam código que representa um caso real de uso da ferramenta.

---

#### 3.4 Contextualização
Um exemplo de código é considerado contextualizado quando fica claro em que contexto de uso e implementação o exemplo é utilizado. Ou seja, os exemplos de código apresentam algum elemento que explicita como e em que contextos se utiliza o exemplo apresentado.

**Consequências:**  
Quando um exemplo de código não está contextualizado, a informação sobre o uso da funcionalidade representada no exemplo é apresentada sem indicar o contexto de uso em que o exemplo pudesse ser usado, deixando ambíguo o entendimento sobre os cenários de uso nos quais se utilizaria a funcionalidade exemplificada.

**Exemplo de boa aplicação:**  
O seguinte exemplo de código da documentação da ferramenta PIL possui um texto de introdução que o contextualiza:

![Screenshot](../imagens/img (35).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem exemplos de código não contextualizados, logo, se o exemplo acima, ao invés do título e introdução, fosse apresentado da seguinte forma, não haveria contextualização:

![Screenshot](../imagens/img (37).png)

**Verificação:**  
Todos os exemplos de código possuem algum elemento (comentário, nome de função, título, etc.) que deixe claro o cenário de uso do exemplo.

---

### Atributos de Apresentação

#### 3.5 Boa legibilidade
Um exemplo de código é considerado com boa legibilidade quando seu código está bem escrito (fácil de entender) e as nomenclaturas de variáveis e funções estão de acordo com boas práticas.

**Consequências:**  
Quando um exemplo de código não está com boa legibilidade, o entendimento do exemplo de código é prejudicado devido a dificuldade de leitura do código no exemplo.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL os exemplos apresentam boa legibilidade pois estão bem escritos e seguem boas práticas de codificação em Python:

![Screenshot](../imagens/img (38).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de exemplos de código com legibilidade ruim. Usando o exemplo anterior, o código teria legibilidade ruim caso fosse exrito da seguinte forma:

![Screenshot](../imagens/img (39).png)

**Verificação:**  
Todos os elementos de código dos exemplos de código apresentam boas práticas em suas nomenclaturas e o código está bem escrito.

---

#### 3.6 Clareza
Um exemplo de código é considerado claro quando é explicitada qual ou quais funcionalidades ele exemplifica.

**Consequências:**  
Quando um exemplo de código não está claro, há dificuldade para entender quais funcionalidades estão exemplificadas no código, dificultando o entendimento da ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL o seguinte exemplo está claro por estar localizado dentro da definição da função que ele exemplifica:

![Screenshot](../imagens/img (40).png)

**Exemplo de aplicação ruim:**  
O seguinte exemplo de código da documentação da ferramenta PIL não está claro pois não define qual ou quais funcionalidades da ferramenta estão sendo usadas:

![Screenshot](../imagens/img (42).png)

**Verificação:**  
Todos os exemplos de código possuem alguma indicação de qual funcionalidade está sendo exemplificada.

---

#### 3.7 Estrutura organizada
Um exemplo de código é considerado organizada estruturalmente quando existe uma estrutura padrão e específica para código para todos os exemplos de código. Ou seja, todos os exemplos de código estão estruturados da mesma forma em toda a DFDS.

**Consequências:**  
Quando um exemplo de código não está organizado estruturalmente, há dificuldade para encontrar informações sobre o uso das funcionalidades da ferramenta devido à dificuldade de identificar os exemplos de código.

**Exemplo de boa aplicação:**  
Os exemplos de código da documentação da ferramenta PIL estão organizados estruturalmente por estarem em formatação de código e a mesma formatação para diferentes exemplos:

![Screenshot](../imagens/img (43).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de exemplos de código desorganizados estruturalmente. Usando o exemplo anterior, o primeiro exemplo de código da imagem estaria em uma estrutura desorganizada caso utilizasse formatação de texto:

![Screenshot](../imagens/img (44).png)

**Verificação:**  
Todos os exemplos de código estão estruturados da mesma forma e em uma formatação específica para código.
