# 7- Propriedade: Destaques visuais

Propriedade de apresentação e estrutura. Utilização de elementos de destaque na documentação para apresentar informações importantes para o desenvolvedor.

## Pré-Condições
Essa propriedade só é aplicável quando é necessário atentar o desenvolvedor para um conteúdo da documentação sem a necessidade do desenvolvedor acessar outra parte da DFDS.

## Atributos

### Atributos de Conteúdo

#### 7.1 Completude
Os destaques visuais da DFDS são considerados completos quando algum elemento de destaque é utilizado para chamar atenção para um conteúdo sem a necessidade de redirecionar para outras seções.

**Consequências:**  
Quando os destaques visuais não estão completos, não há forma de chamar atenção para informações importantes devido à falta de elementos de destaque.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL o elemento de destaque utilizado é em forma de avisos e notas em diferentes partes da documentação, atentando o desenvolvedor para alguma informação importante sobre o conteúdo relacionado:

![Screenshot](../imagens/img (61).png)

![Screenshot](../imagens/img (62).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam elementos de destaque incompletos. Usando como exemplo a documentação da ferramenta PIL, caso não existissem as notas e avisos e nenhum tipo de elemento de destaque fosse utilizado para isso ou essas informações estivessem disponíveis apenas em outra parte da DFDS, seria uma incompletude dos destaques visuais.

**Verificação:**  
Todo conteúdo que exige atenção na documentação apresenta elementos de destaque para apresentar esse conteúdo sem a necessidade de redirecionar o desenvolvedor para outra seção da documentação.

---

#### 7.2 Corretude
Os destaques visuais da DFDS são considerados corretos quando as explicações presentes nos elementos de destaque estão de acordo com o conteúdo referenciado.

**Consequências:**  
Quando os destaques visuais não estão corretos, há presença de informações incorretas com maior atenção devido à presença de informações equivocadas no elemento de destaque.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL os elementos de destaque utilizados apresentam informações de acordo com a definição dos conteúdos relacionados:

![Screenshot](../imagens/img (63).png)

**Exemplo de aplicação ruim:**  
As documentações não apresentam destaques visuais incorretos. Usando o exemplo acima, caso a informação na nota apresentasse uma informação equivocada, seria incorreto. No exemplo abaixo, a nota nega a informação do exemplo anterior:

![Screenshot](../imagens/img (64).png)

**Verificação:**  
O texto dos destaques visuais apresentam explicações corretas de acordo com o conteúdo referenciado.

---

#### 7.3 Relevância
Os destaques visuais são considerados relevantes quando as explicações apresentadas seguem as regras de relevância do conteúdo apresentado (verificar 1.3 para explicações conceituais e 2.3 para cobertura funcional)

---

#### 7.4 Contextualização
Os destaques visuais são considerados contextualizados quando a referência que possui o elemento de destaque deixa claro qual é o conteúdo referenciado.

**Consequências:**  
Quando os destaques visuais não estão contextualizados, há dificuldade no entendimento da informação destacada devido ao elemento de destaque ser ambíguo sobre qual conteúdo ele referencia.

**Exemplo de boa aplicação:**  
Na documentação da bilbioteca Matplotlib os elementos de destaque estão contextualizados por estarem posicionados logo após o conteúdo que estão relacionados:

![Screenshot](../imagens/img (119).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam elementos de destaque sem contextualização. Usando o exemplo anterior, seria falta de contextualização se ao invés de logo após o conteúdo, o elemento de destaque fosse localizado no final da página.

**Verificação:**  
Todos os elementos de destaque estão localizados junto ao conteúdo referenciado.

---

### Atributos de Apresentação

#### 7.5 Boa legibilidade
Os destaques visuais são considerados com boa legibilidade quando as explicações apresentadas seguem as regras de boa legibilidade do conteúdo apresentado (verificar 1.5 para explicações conceituais e 2.5 para cobertura funcional)

---

#### 7.6 Clareza
Os destaques visuais são considerados claros quando fica explícito qual é o tipo de conteúdo referenciado

**Consequências:**  
Quando os destaques visuais não estão claros, há dificuldade no entendimento da informação destacada devido à dificuldade de identificar que tipo de conteúdo está presente no elemento de destaque.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL o seguinte elemento de destaque deixa claro que é sobre uma funcionalidade ao utilizar uma a mesma formatação de texto para o nome da funcionalidade que no restante da documentação:

![Screenshot](../imagens/img (120).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Matplotlib o seguinte elemento de destaque não deixa claro que seu conteúdo é sobre uma funcionalidade ou um conceito de imagens interativas:

![Screenshot](../imagens/img (121).png)

**Verificação:**  
Todas as explicações nos elementos de destaque possuem em seu texto ou título um trecho explicitando o tipo de conteúdo referenciado.

---

#### 7.7 Estrutura organizada
Os destaques visuais da DFDS são considerados organizados estruturalmente quando os elementos de destaque utilizados são do mesmo tipo e formatação em toda a documentação.

**Consequências:**  
Quando os destaques visuais não estão organizados estruturalmente, há falta de entendimento sobre as informações destacadas devido à dificuldade de entender o uso dos diferentes elementos de destaque para os mesmos conteúdos.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL todos os elementos de destaque são do mesmo tipo e de mesma formatação, alterando apenas a cor para avisos.

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios os elementos de destaque, no caso notas, possuem formatações diferentes em partes diferentes da documentação, com e sem o título “Nota”:

![Screenshot](../imagens/img (68).png)

![Screenshot](../imagens/img (69).png)

**Verificação:**  
Todos os elementos de destaque utilizados são do mesmo tipo e com a mesma formatação.
