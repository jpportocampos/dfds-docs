# 10- Propriedade: Referências e links externos

Propriedade de conteúdo. Utilização de links externos para explicações mais detalhadas de conceitos externos. Links externos são usados para referências a conceitos externos além da modelagem da ferramenta.

## Pré-Condições
Essa propriedade só é aplicável quando existem conceitos externos à ferramenta que podem necessitar de explicações mais completas, porém que fogem do escopo da DFDS.

## OBSERVAÇÃO
Essa propriedade **NÃO** substitui a propriedade 1 (explicação conceitual), ela adiciona um explicação a mais quando necessário, ou seja, quando a explicação completa do conceito foge do escopo da DFDS mas ainda pode ser útil para um desenvolvedor que não conhece o conceito previamente.

## Atributos

### Atributos de Conteúdo

#### 10.1 Completude
As referências e links externos são considerados completos quando todos os conteúdos relacionados à ferramenta que necessitam de explicação extra que fuja do escopo da DFDS possuem links externos para essa explicação.

**Consequências:**  
Quando as referências e links externos não estão completos, há dificuldade de compreensão de um conceito mais complexo devido à falta de links.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Axios os conteúdos externos ao escopo da DFDS possuem links que direcionam para suas respectivas explicações:

![Screenshot](../imagens/img (122).png)

![Screenshot](../imagens/img (123).png)

![Screenshot](../imagens/img (124).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem exemplos de falta de completude relacionado aos links externos. Usando o exemplo anterior, a incompletude poderia ser não adicionar link para “XMLHttpRequest” ou para http no node.js.

**Verificação:**  
Todas as seções na documentação que possuem conteúdos relacionados à ferramenta que necessitam de explicação extra que fuja do escopo da DFDS possuem links externos para essa explicação.

---

#### 10.2 Corretude
As referências e links externos são considerados corretos quando os links levam para explicações do conteúdo referenciado.

**Consequências:**  
Quando as referências e links externos não estão corretos, há presença de informações incorretas devido à presença de links que direcionam para explicações equivocadas dos conceitos.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL os links externos levam à páginas relacionadas aos conteúdos referenciados:

![Screenshot](../imagens/img (94).png)

![Screenshot](../imagens/img (95).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam exemplos de incorreção nos links externos. Usando o exemplo anterior, um caso de incorreção seria, ao invés de levar para a página específica do conteúdo referenciado, levar para a página inicial do site com a explicação:

![Screenshot](../imagens/img (94).png)

![Screenshot](../imagens/img (96).png)

**Verificação:**  
Todas as referências e links externos levam para explicações dos conteúdos referenciados nos links.

---

#### 10.3 Relevância
A Relevância não afeta essa propriedade.

---

#### 10.4 Contextualização
As referências e links externos são considerados contextualizados quando fica claro qual conteúdo o link referencia.

**Consequências:**  
Ver consequências em 9.4.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib os links externos estão localizados em trechos com os nomes dos conteúdos que referenciam, contextualizando que este conteúdo será explicado mais a fundo na página direcionada:

![Screenshot](../imagens/img (97).png)

![Screenshot](../imagens/img (98).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de falta de contextualização nos links externos, mas usando o exemplo anterior, poderíamos ter o link “online notebooks” ao invés de especificamente o link “Jupyter” e ainda direcionar para a página do Jupyter especificamente:

![Screenshot](../imagens/img (99).png)

![Screenshot](../imagens/img (98).png)

**Verificação:**  
Todas as referências e links externos explicitam quais conceitos são referenciados pelos links.

---

### Atributos de Apresentação

#### 10.5 Boa legibilidade
As referências e links externos são considerados com boa legibilidade quando o texto que possui o link está bem escrito (fácil de entender) e não possui erros gramaticais.

**Consequências:**  
Quando as referências e links externos não estão com boa legibilidade, há dificuldade no entendimento de qual conteúdo será explicado no link devido a dificuldade de leitura dele.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Axios os links externos estão bem escritos e não apresentam erros gramaticais.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam legibilidade ruim nos links externos. Na documentação da ferramenta Axios, um caso de legibilidade ruim poderia ser:

![Screenshot](../imagens/img (125).png)

**Verificação:**  
Todos os trechos das referências e links externos possuem texto bem escrito e não apresentam erros gramaticais em seu texto.

---

#### 10.6 Clareza
As referências e links externos são considerados claros quando fica explícito que o texto apresentado é uma referência para um conteúdo fora do DFDS.

**Consequências:**  
Quando as referências e links externos não estão claros, há dificuldade de navegação na DFDS devido à dificuldade de identificar que há um link externo presente no texto.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Axios os links externos estão todos em formatação de link.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam problema de clareza nos links externos. Usando a documentação da ferramenta Axios como exemplo poderíamos ter como falta de clareza o caso da formatação dos links externos serem iguais a do restante do texto.

**Verificação:**  
Todas as referências e links externos possuem formatação de link.

---

#### 10.7 Estrutura organizada
As referências e links são considerados organizados estruturalmente quando a formatação de link utilizada é a mesma para todos os links.

**Consequências:**  
Ver consequências em 9.7

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib os links externos estão todos em formatação de link e com a mesma formatação:

![Screenshot](../imagens/img (102).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam problema de clareza nos links externos. Usando o exemplo anterior poderíamos ter como falta de clareza o caso de dois links externos possuírem formatação diferente:

![Screenshot](../imagens/img (126).png)

**Verificação:**  
Todas as referências e links externos estão estruturadas no mesmo formato.
