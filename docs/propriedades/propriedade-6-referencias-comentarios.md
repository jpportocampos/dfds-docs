# 6- Propriedade: Referências conceituais em comentários de código

Propriedade de apresentação e estrutura. Os conceitos modelados pela ferramenta são referenciados nos exemplos de código através de comentários de código.

## Pré-Condições
Essa propriedade só é aplicável quando já existe uma explicação conceitual (Regra 1) e um exemplo de código (Regra 3) da funcionalidade que usa o conceito documentado.

## Atributos

### Atributos de Conteúdo

#### 6.1 Completude
As referências conceituais em comentários de código são consideradas completas quando todos os conceitos de um exemplo de código da DFDS possuem comentários referenciando-os. Ou seja, em todos os exemplos de código cuja funcionalidade exemplificada modela um conceito descrito em uma descrição conceitual na DFDS, esse conceito é referenciado e apontado no exemplo via comentários de código.

**Consequências:**  
Quando as referências conceituais em comentários de código não estão completas, há dificuldade no entendimento da relação entre as funcionalidades e os conceitos da ferramenta devido à falta de referências.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL os comentários de código no seguinte exemplo mencionam os conceitos utilizados:

![Screenshot](../imagens/img (52).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Matplotlib os comentários no código do seguinte exemplo não mencionam ou referenciam todos os conceitos utilizados:

![Screenshot](../imagens/img (118).png)

**Verificação:**  
Todos os exemplos de código cuja funcionalidade exemplificada modele um conceito externo à ferramenta possuem comentários que referenciam os conceitos utilizados pela funcionalidade exemplificada.

---

#### 6.2 Corretude
As referências conceituais em comentários de código são consideradas corretas quando o conceito referenciado pelos comentários é aquele modelado pela funcionalidade exemplificada.

**Consequências:**  
Quando as referências conceituais em comentários de código não estão corretas, há entendimento equivocado sobre o domínio das funcionalidades da ferramenta devido à presença de referências equivocadas.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca PIL o seguinte exemplo referencia os conceitos corretos:

![Screenshot](../imagens/img (52).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam referências conceituais incorretas em comentários de código. Usando o exemplo anterior, seria incorreto:

![Screenshot](../imagens/img (55).png)

**Verificação:**  
Todos os comentários de código presentes nos exemplos de código que mencionam conceitos, mencionam os utilizados pelo código presente no exemplo.

---

#### 6.3 Relevância
A relevância não afeta essa propriedade.

---

#### 6.4 Contextualização
As referências conceituais em comentários de código são consideradas contextualizadas quando fica claro que parte do código utiliza o conceito mencionado. Ou seja, a posição do comentário facilita o entendimento de qual trecho do código utiliza o conceito referenciado.

**Consequências:**  
Quando as referências conceituais em comentários de código não estão contextualizadas, há falta de entendimento sobre o domínio das funcionalidades da ferramenta devido às referências apresentadas serem ambíguas sobre a funcionalidade a qual a referência pertence.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL o exemplo a seguir deixa claro pelo posicionamento dos comentários que trechos de código utilizam os conceitos mencionados e como:

![Screenshot](../imagens/img (52).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem referências conceituais em comentários de código não contextualizadas, usando o exemplo anterior, a não contextualização poderia ser da seguinte forma:

![Screenshot](../imagens/img (57).png)

**Verificação:**  
Os comentários de referências conceituais estão posicionados de acordo com a funcionalidade que utiliza o conceito referenciado.

---

### Atributos de Apresentação

#### 6.5 Boa legibilidade
As referências conceituais em comentários de código são consideradas com boa legibilidade quando os comentários estão bem escritos (fácil de entender).

**Consequências:**  
Quando as referências conceituais em comentários de código não estão com boa legibilidade, há dificuldade no entendimento da referência feita devido a dificuldade de leitura das referências.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL há boa legibilidade das referências conceituais no seguinte exemplo de código:

![Screenshot](../imagens/img (52).png)

**Exemplo de aplicação ruim:**  
Nas documentações de exemplo não há legibilidade ruim em referências conceituais em exemplos de código, usando o exemplo acima, uma legibilidade ruim poderia ser:

![Screenshot](../imagens/img (58).png)

**Verificação:**  
Todos os comentários de código dos exemplos de código estão bem escritos e não apresentam erros gramaticais.

---

#### 6.6 Clareza
As referências conceituais em comentários de código são consideradas claras quando fica explícito qual conceito é referenciado pelos comentários de código.

**Consequências:**  
Quando as referências conceituais em comentários de código não estão claras, há dificuldade de identificar a qual conceito o comentário de código se refere devido à falta de concordância entre o texto do comentário e o restante da documentação em relação ao conceito.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL o seguinte exemplo possui referências claras por usar o mesmo nome para o conceito como em outras partes da documentação:

![Screenshot](../imagens/img (52).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo possuem clareza em todas as referências conceituais em comentários de código. Usando o exemplo acima, a falta de clareza poderia ser ao invés de usar o nome utilizado em “Concepts” usar um sinônimo:

![Screenshot](../imagens/img (59).png)

**Verificação:**  
Todos os comentários de referências conceituais possuem em seu texto o nome do conceito referenciado assim como está na explicação conceitual (Regra 1)

---

#### 6.7 Estrutura organizada
Verificar 3.7
