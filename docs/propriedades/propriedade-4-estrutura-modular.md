# 4- Propriedade: Estrutura modular

Propriedade de apresentação e estrutura. O conteúdo é separado em seções curtas e autônomas.

## Pré-Condições
Essa propriedade só é aplicável quando o conteúdo a ser documentado pode ser organizado em seções autônomas.

## OBSERVAÇÃO
Essa propriedade facilita o uso da DFDS por desenvolvedores que buscam apenas consultar a documentação para realizar tarefas específicas. O recomendado é combinar essa propriedade com a 5 (Estrutura linear), organizando as seções modulares em uma ordem específica de leitura.

## Atributos

### Atributos de Conteúdo

#### 4.1 Completude
A estrutura modular da DFDS é considerada completa quando todo o conteúdo da DFDS é dividido em seções. Ou seja, o conteúdo é inteiramente organizado em seções que, em conjunto, cobrem inteiramente a descrição da ferramenta.

**Consequências:**  
Quando a estrutura modular não está completa, há dificuldade para encontrar informações sobre tópicos específicos da ferramenta porque as seções não cobrem todo o conteúdo da DFDS.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL todo o conteúdo é dividido em páginas e cada página contém módulos autônomos.

**Exemplo de aplicação ruim:**  
Nas documentações de exemplo, o conteúdo está estruturado em seções modulares, ao acessar o github da ferramenta Axios, há uma versão não modularizada da documentação em um arquivo README.md. Caso essa fosse a única documentação da ferramenta, seria uma aplicação ruim.

**Verificação:**  
Todos os tópicos da ferramenta estão estruturados em seções modulares na DFDS.

---

#### 4.2 Corretude
A estrutura modular da DFDS é considerada correta quando as seções são autônomas e se referenciam quando possuem conteúdo em comum. Ou seja, as seções são completas, cobrem inteiramente um tópico da descrição da ferramenta sem a necessidade de ler outra seção para entender o tópico por completo, mas apontam para outras seções relevantes que possuam conteúdo em comum, quando for o caso.

**Consequências:**  
Quando a estrutura modular não está correta, a falta de autonomia das seções faz com que estas sejam muito longas ou com conteúdo incompleto para o entendimento.

**Exemplo de boa aplicação:**  
Em [1], no módulo de conceitos, as funcionalidades utilizadas são referenciadas com os nomes dos módulos e seções referenciados, no seguinte exemplo, isso ocorre na última frase:

![Screenshot](../imagens/img (46).png)

**Exemplo de aplicação ruim:**  
Caso o exemplo anterior não tivesse a última frase, a modularização estaria incorreta.

**Verificação:**  
Todas as seções modulares da DFDS que possuem assuntos em comum se referenciam.

---

#### 4.3 Relevância
A estrutura modular da ferramenta é considerada relevante quando as seções da DFDS são separadas de forma que o conteúdo de cada uma das seções represente pelo menos uma forma real de uso da ferramenta, facilitando a consulta de informações relevantes. Ou seja, as seções são separadas de acordo com os cenários reais de uso da ferramenta.

**Consequências:**  
Quando a estrutura modular não está relevante, há uma dificuldade de encontrar informações relevantes em um cenário real de uso da ferramenta devido à organização da documentação não apresentar o conteúdo de acordo com os cenários de uso da ferramenta.

**Exemplo de boa aplicação:**  
As páginas e módulos na documentação da ferramenta Matplotlib estão separados de acordo com o uso de cada funcionalidade, facilitando a consulta de informações relevantes.

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios um dos módulos iniciais é sobre Requisições POST e não existem módulos sobre as outras requisições HTTP utilizadas pela ferramenta.

**Verificação:**  
Os tópicos da ferramenta foram organizados em seções modulares de acordo com cenários reais de uso da ferramenta.

---

#### 4.4 Contextualização
A estrutura modular da DFDS é considerada contextualizada quando fica claro qual é o tópico coberto em cada seção. Ou seja, ao ler a DFDS, o desenvolvedor entende o que irá encontrar em cada seção sem precisar lê-la inteiramente.

**Consequências:**  
Quando a estrutura modular não está contextualizada, há dificuldade para encontrar informações na documentação devido à falta de clareza sobre o tópico coberto nas seções.

**Exemplo de boa aplicação:**  
Os títulos das seções e páginas na documentação da ferramenta PIL deixam claro qual tópico será coberto em cada um dos módulos.

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios, o módulo “Exemplos” possui nome que sugere que será um módulo com exemplos de uso da ferramenta, mas essa seção possui apenas uma explicação de como configurar a ferramenta para um ambiente específico de programação.

**Verificação:**  
Todas as seções da DFDS possuem título e um trecho curto que indicam o conteúdo presente nelas.

---

### Atributos de Apresentação

#### 4.5 Boa legibilidade
A estrutura modular da DFDS é considerada com boa legibilidade quando o texto que descreve as seções está bem escrito (fácil de entender) e não possui erros gramaticais.

**Consequências:**  
Quando a estrutura modular não está com boa legibilidade, há dificuldade com o entendimento da seção devido a dificuldade de leitura do texto de introdução.

**Exemplo de boa aplicação:**  
Os trechos introdutórios na documentação da ferramenta Axios estão bem escritos e não apresentam erros de gramática:

![Screenshot](../imagens/img (50).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem seções com legibilidade ruim, porém, se o exemplo usado anteriormente fosse mal escrito, seria:

![Screenshot](../imagens/img (51).png)

**Verificação:**  
Todos os trechos de contextualização das seções modulares da DFDS possuem texto bem escrito e não apresentam erros gramaticais em seu texto.

---

#### 4.6 Clareza
A estrutura modular da ferramenta é considerada clara quando está explícito quando uma seção começa e acaba.

**Consequências:**  
Quando a estrutura modular não está clara, há dificuldade para navegar na documentação devido à dificuldade de identificar o início e o final de uma seção.

**Exemplo de boa aplicação:**  
As documentações de exemplo possuem separações claras entre as seções, visto que cada seção possui uma página web diferente.

**Exemplo de aplicação ruim:**  
Caso as documentações fossem hospedadas em uma única página e não houvesse uma separação clara entre os módulos, não haveria clareza.

**Verificação:**  
Todas as seções modulares da DFDS são apresentadas com separações umas das outras e com títulos e subtítulos em seu conteúdo.

---

#### 4.7 Estrutura organizada
A estrutura modular da DFDS é considerada organizada estruturalmente quando existe uma estrutura padrão para as seções modulares. Ou seja, todas as seções estão estruturadas da mesma forma em toda a DFDS.

**Consequências:**  
Quando a estrutura modular não está organizada estruturalmente, há dificuldade dificuldade de navegação na documentação devido à falta de organização das seções.

**Exemplo de boa aplicação:**  
Os módulos da documentação da ferramenta PIL seguem uma mesma estrutura e formatação para títulos, subtítulos e exemplos.

**Exemplo de aplicação ruim:**  
Na documentação da ferrmenta Axios os módulos possuem mesma formatação, mas a organização de título, subtítulo e exemplo é diferente em cada seção.

**Verificação:**  
Todas as seções da DFDS possuem a mesma estrutura.
