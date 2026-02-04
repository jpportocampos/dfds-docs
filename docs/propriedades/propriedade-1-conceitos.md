# Propriedade 1: Descrição dos conceitos da ferramenta

Propriedade de conteúdo. Descrição dos conceitos externos à ferramenta modelados por ela, explicando como estes conceitos são aplicados pela ferramenta.

## Pré-Condições
Essa propriedade só é aplicável quando se tem alguma funcionalidade da ferramenta que modela um conceito externo, ou seja, que existe além da ferramenta.

## Atributos

### Atributos de Conteúdo

#### 1.1 Completude
A descrição dos conceitos da ferramenta é considerada completa quando todos os conceitos modelados pela ferramenta estão descritos na DFDS. Ou seja, qualquer conceito externo à ferramenta (que não está relacionado à implementação) deve estar descrito e explicado considerando o contexto de aplicação da ferramenta.

**Consequências:**  
Quando a explicação conceitual não está completa, a DFDS não possui todas as informações necessárias para o entendimento da ferramenta por omitir informações sobre o domínio de aplicação dela.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca Pillow (PIL Fork), uma biblioteca de manipulação de imagem, todos os conceitos utilizados estão descritos e podem ser encontrados na seção “Concepts”.

**Exemplo de aplicação ruim:**  
Na documentação da bibliota express-validator, apesar de que na introdução da documentação é dito que a biblioteca é baseada em middlewares, em nenhum ponto da documentação esse conceito é descrito.

**Verificação:**  
Se para entender o uso de uma funcionalidade da ferramenta é necessário entender algum conceito externo à ferramenta, esse conceito deve ser explicado na DFDS.

---

#### 1.2 Corretude
A descrição dos conceitos da ferramenta é considerada correta quando não apresenta erros conceituais. Ou seja, a descrição está de acordo com a definição formal do conceito modelado.

**Consequências:**  
Quando a explicação conceitual não está correta, a DFDS apresenta informações ambíguas ou equivocadas sobre o domínio da ferramenta devido à presença de informações equivocadas sobre o domínio de aplicação da ferramenta.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca Pillow (PIL Fork), os conceitos estão descritos corretamente, seguindo a definição formal deles. Como por exemplo, a definição de "Bands":

![Screenshot](../imagens/img (1).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de incorreção na descrição dos conceitos da ferramenta. Um exemplo falso que poderia aparecer na documentação da biblioteca express-validator seria ao apresentar a definição de middleware, apresentar a definição de gateway.

**Verificação:**  
As explicações conceituais devem estar de acordo com as definições formais dos conceitos modelados.

---

#### 1.3 Relevância
A descrição dos conceitos da ferramenta é considerada relevante quando os conceitos modelados pela ferramenta estão descritos considerando casos reais de uso da ferramenta. Ou seja, a descrição dos conceitos externos à ferramenta usa exemplos e terminologia relacionada ao contexto de aplicação da ferramenta.

**Consequências:**  
Quando a explicação conceitual não é relevante, a informação é apresentada sem considerar o contexto de aplicação da ferramenta, criando uma dificuldade para atribuir o conceito à implementação.

**Exemplo de boa aplicação:**  
Na documentação da biblioteca Pillow (PIL Fork), a definição de “Size” utiliza terminologias relacionadas a programação em Python.

**Exemplo de aplicação ruim:**  
Se a definição não utilizasse terminologias relacionadas a programação em Python.

**Verificação:**  
As explicações conceituais devem apresentar exemplos e linguajar alinhados com casos reais de uso da ferramenta.

---

#### 1.4 Contextualização
A descrição dos conceitos da ferramenta é considerada contextualizada quando fica claro qual funcionalidade da ferramenta modela o conceito.

**Consequências:**  
Há entendimento equivocado sobre o domínio da ferramenta devido à informação apresentada ser ambígua.

**Exemplo de boa aplicação:**  
A definição explicita qual funcionalidade utiliza o conceito.

**Exemplo de aplicação ruim:**  
A ausência da referência à funcionalidade que utiliza o conceito.

**Verificação:**  
As explicações conceituais explicitam quais funcionalidades utilizam os conceitos explicados.

---

### Atributos de Apresentação

#### 1.5 Boa legibilidade
A descrição dos conceitos da ferramenta é considerada com boa legibilidade quando seu texto está bem escrito e não possui erros gramaticais.

**Consequências:**  
Dificuldade para encontrar informações sobre o domínio da ferramenta.

**Verificação:**  
Os textos dos conceitos modelados são bem escritos e não apresentam erros gramaticais.

---

#### 1.6 Clareza
A descrição é considerada clara quando é explicitado que o texto apresentado é uma explicação conceitual.

**Consequências:**  
Dificuldade para identificar que o texto se refere a conteúdo conceitual.

**Verificação:**  
As explicações conceituais explicitam que seu texto é uma explicação conceitual.

---

#### 1.7 Estrutura organizada
Existe uma estrutura padrão para todas as explicações conceituais.

**Consequências:**  
Dificuldade para encontrar informações sobre o domínio da ferramenta.

**Verificação:**  
Todas as explicações conceituais estão estruturadas no mesmo formato.
