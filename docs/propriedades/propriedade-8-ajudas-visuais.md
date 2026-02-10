# 8- Propriedade: Ajudas visuais

Propriedade de apresentação e estrutura. Utilização de diagramas, imagens, animações, entre outros, na explicação de workflows e conceitos complexos e exemplificação de resultados esperados.

## Pré-Condições
Essa propriedade só é aplicável quando se tem algum workflow ou conceito cujo uso de ajudas visuais facilitaria o entendimento necessário para o uso da ferramenta
**OU**
quando o uso da ferramenta compreende alterações de interface cujo uso de prints de tela para exemplificação de resultados facilita o entendimento necessário para o uso da ferramenta


## Atributos

### Atributos de Conteúdo

#### 8.1 Completude
A ajuda visual é considerada completa quando todos os conteúdos que se beneficiam de ajudas visuais possuem esses elementos (e.g. diagramas, imagens, animações).

**Consequências:**  
Quando a ajuda visual não está completa, há falta de entendimento sobre um conteúdo mais complexo da ferramenta devido à falta de informações.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL, por se tratar de uma biblioteca de manipulação de imagens, são utilizados diversos prints e GIFs para exemplificar a manipulação de uma imagem:

![Screenshot](../imagens/img (70).png)

![Screenshot](../imagens/img (71).png)

![Screenshot](../imagens/img (72).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem ajudas visuais incompletas. Usando a documentação da ferramenta PIL como exemplo, caso não fosse usada nenhuma imagem de exemplo para demonstrar as funcionalidades, seria um caso de incompletude

**Verificação:**  
Todos os conteúdos que se beneficiam de ajudas visuais possuem pelo menos um elemento de ajuda visual.

---

#### 8.2 Corretude
A ajuda visual é considerada correta quando os elementos de ajuda visual representam corretamente o conteúdo abordado.

**Consequências:**  
Quando a ajuda visual não está correta, há entendimento equivocado sobre um conteúdo mais complexo da ferramenta devido à presença de informações equivocadas.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL as ajudas visuais utilizadas representam corretamente o resultado da manipulação descrita nos exemplos de código:

![Screenshot](../imagens/img (73).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam incorreção de ajudas visuais. Usando o exemplo acima, caso a primeira e última imagens fossem trocadas, seria um caso de incorreção.

**Verificação:**  
Todos os elementos de ajuda visual utilizados representam o conteúdo correto.

---

#### 8.3 Relevância
A ajuda visual é considerada relevante quando os elementos de ajuda visual utilizados facilitam o entendimento do conteúdo sendo apoiado.

**Consequências:**  
Quando a ajuda visual não é relevante, há falta de entendimento sobre um conteúdo mais complexo da ferramenta devido à ajuda visual apresentada ser insuficiente para facilitar o entendimento do conteúdo.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL a imagem utilizada nas ajudas visuais é relevante por ser uma imagem complexa, ou seja, com muitos elementos que facilitam a visualização das mudanças.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam irrelevância nas ajudas visuais, usando a documentação da ferramenta PIL como exemplo, caso a imagem utilizada, ao invés de ser de uma pessoa, fosse uma imagem de uma cor sólida, seria irrelevante por não facilitar o entendimento de certas funcionalidades, como por exemplo, girar a imagem.

**Verificação:**  
Todos os elementos de ajuda visual facilitam o entendimento do conteúdo sendo apoiado.

---

#### 8.4 Contextualização
A ajuda visual da ferramenta é considerada contextualizada quando fica claro que tipo de conteúdo o elemento de ajuda visual representa. Ou seja, ao ler a DFDS, o desenvolvedor entende se a ajuda visual está associada a um conceito, uma funcionalidade, um caso de uso, entre outros.

**Consequências:**  
Quando a ajuda visual não está contextualizada, há dificuldade para compreender que tipo de conteúdo está sendo apoiado devido à ajuda visual ser ambígua sobre qual conteúdo ela referencia.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL, o seguinte exemplo contextualiza a ajuda visual ao colocar a imagem em um layout de janela, explicitando que o código acima da imagem abre uma janela com a imagem:

![Screenshot](../imagens/img (74).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta PIL o seguinte exemplo não contextualiza explicitamente que a ajuda visual representa o estado da imagem após rodar o código:

![Screenshot](../imagens/img (75).png)

**Verificação:**  
Todos os elementos de ajuda visual possuem alguma indicação que explicita que tipo de conteúdo está sendo representado.

---

### Atributos de Apresentação

#### 8.5 Boa legibilidade
A ajuda visual da ferramenta é considerada com boa legibilidade quando o texto da legenda e, caso presente, o texto do elemento visual está bem escrito (fácil de entender) e não possui erros gramaticais.

**Consequências:**  
Quando a ajuda visual não está com boa legibilidade, há dificuldade no entendimento sobre um conteúdo mais complexo da ferramenta devido a dificuldade de leitura da ajuda visual.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib a seguinte imagem é utilizada para explicar os diferentes componentes de uma Figure da biblioteca. O texto presente nela está bem escrito e não apresenta erros de gramática:

![Screenshot](../imagens/img (76).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de legibilidade ruim em ajudas visuais. Usando o exemplo anterior, seria o caso se existissem erros gramaticais no texto da imagem, como por exemplo, no título estar escrito “Anaomy of a igure” ao invés e “Anatomy of a figure”.

**Verificação:**  
Todo o texto presente nas ajudas visuais é bem escrito e não apresenta erros gramaticais.

---

#### 8.6 Clareza
A ajuda visual da ferramenta é considerada clara quando fica explícito para qual conteúdo o elemento utilizado é uma ajuda visual.

**Consequências:**  
Quando a ajuda visual não está clara, há dificuldade para relacionar a ajuda visual ao conteúdo sendo apoiado por ela devido à ajuda visual ser ambígua sobre qual conteúdo ela referencia.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib as ajudas visuais estão localizadas de forma que é claro para qual conteúdo as imagens se referem:

![Screenshot](../imagens/img (77).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem falta de clareza nas ajudas visuais. Na documentação da ferramenta Matplotlib haveria falta de clareza caso as imagens ficassem todas no final da página ao invés de cada uma em sua seção, por exemplo.

**Verificação:**  
Todas as ajudas visuais estão localizadas na mesma seção que os conteúdos correspondentes e a legenda, quando presente, explicita o conteúdo.

---

#### 8.7 Estrutura organizada
A ajuda visual é considerada organizada estruturalmente quando o elemento de ajuda visual está localizado de modo que o entendimento do restante da seção não seja prejudicado.

**Consequências:**  
Quando a ajuda visual não está organizada estruturalmente, há dificuldade de navegação na DFDS devido à ajuda visual prejudicar o entendimento do texto em volta.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib as ajudas visuais não interrompem o texto em volta e não prejudicam a formatação do restante da documentação.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem ajudas visuais em estrutura desorganizada. Em [4] seria o caso se as imagens fossem colocadas no meio dos parágrafos das seções de forma a prejudicar a formatação do texto.

**Verificação:**  
Todas as ajudas visuais estão estruturadas de modo que o restante da seção não possua seu entendimento e formatação prejudicados.
