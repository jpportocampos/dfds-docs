# 9- Propriedade: Referências e links internos

Propriedade de conteúdo. Utilização de links internos para facilitar navegação. Links internos conectam seções com conceitos ou funcionalidades em comum.

## Pré-Condições
Essa propriedade só é aplicável quando se tem seções que possuam conceitos ou funcionalidades em comum

## Atributos

### Atributos de Conteúdo

#### 9.1 Completude
As referências e links internos são considerados completos quando todas as seções que possuem conceitos ou funcionalidades em comum possuem links internos entre si.

**Consequências:**  
Quando as referências e links internos não estão completos, há a necessidade de encontrar conteúdos de diferentes seções manualmente devido à falta de links.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL as funcionalidades e conceitos mencionados em outras seções possuem links para as respectivas páginas:

![Screenshot](../imagens/img (79).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios as funcionalidades mencionadas, apesar de estarem com formatação diferente, não possuem links para suas respectivas definições:

![Screenshot](../imagens/img (80).png)

**Verificação:**  
Todas as seções na DFDS que possuem conceitos ou funcionalidades em comum possuem links internos entre si.

---

#### 9.2 Corretude
As referências e links internos são considerados corretos quando os links internos levam para as seções corretas.

**Consequências:**  
Quando as referências e links internos não estão corretos, há necessidade de encontrar conteúdos de diferentes seções manualmente devido à presença de links que direcionam para o trecho errado da DFDS.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL ao selecionar o link em “See Colors” na primeira imagem, somos direcionados para a seção correspondente no módulo de “Concepts”, na segunda imagem:

![Screenshot](../imagens/img (80).png)

![Screenshot](../imagens/img (81).png)

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem exemplos de links internos incorretos. Usando o exemplo anterior, se ao clicarmos em “See Colors” fossemos direcionados para a seção “Color names”, seria uma incorreção:

![Screenshot](../imagens/img (80).png)

![Screenshot](../imagens/img (82).png)

**Verificação:**  
Todos os links internos levam para as seções correspondentes à referência feita.

---

#### 9.3 Relevância
A Relevância não afeta essa propriedade

---

#### 9.4 Contextualização
As referências e links internos são considerados contextualizados quando fica claro para qual seção o link interno direciona e qual o conceito ou funcionalidade em comum entre as seções.

**Consequências:**  
Quando as referências e links internos não estão contextualizados, há necessidade de verificar se o conteúdo referenciado é o que se espera ao clicar no link devido aos links serem ambíguos sobre o conteúdo que eles referenciam.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL os links internos são localizados no trecho com o nome da seção correspondente, deixando claro para qual seção será feito o redirecionamento.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem exemplos de falta de contextualização em links internos. Usando a documentação da ferramenta PIL como exemplo, uma possível falta de contextualização seria usar “here” ao invés do nome das seções no trecho com link:

![Screenshot](../imagens/img (85).png)

**Verificação:**  
Todas as referências e links internos explicitam para quais conteúdos as referências são, assim como para qual seção o link direciona.

---

### Atributos de Apresentação

#### 9.5 Boa legibilidade
As referências e links internos da ferramenta são considerados com boa legibilidade quando o texto que possui o link interno está bem escrito (fácil de entender) e não possui erros gramaticais.

**Consequências:**  
Quando as referências e links internos não estão com boa legibilidade, há dificuldade no entendimento sobre a relação entre as seções linkadas devido a dificuldade de leitura dos links.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL os links internos não apresentam erros gramaticais e estão bem escritos.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de legibilidade ruim nos links internos. Usando a documentação da ferramenta PIL como exemplo, um caso de legibilidade ruim poderia ser:

![Screenshot](../imagens/img (86).png)

**Verificação:**  
O texto dos trechos das referências e links internos é bem escrito e não apresenta erros gramaticais.

---

#### 9.6 Clareza
As referências e links internos são considerados claros quando fica explícito que o texto apresentado é uma referência com link interno.

**Consequências:**  
Quando as referências e links internos não estão claros, a navegação é prejudicada devido à dificuldade de identificar que há um link interno presente no texto.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL os links internos estão com formatação de link, deixando explícito que os textos servem como âncoras para o conteúdo referenciado.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de falta de clareza nos links internos. Um exemplo de falta de clareza na documentação da ferramenta PIL poderia ser:

![Screenshot](../imagens/img (87).png)

**Verificação:**  
Todas as referências e links internos possuem formatação de link.

---

#### 9.7 Estrutura organizada
As referências e links são considerados organizados estruturalmente quando a formatação de link utilizada é a mesma para todos os links de mesmo tipo de conteúdo.

**Consequências:**  
Quando as referências e links não estão organizados estruturalmente, a navegação é prejudicada devido à dificuldade de identificar os links presentes no texto.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL os links utilizados para referências conceituais são os mesmos em toda a documentação, assim como os links utilizados para referências de funcionalidades.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de links internos em uma estrutura ruim. Um exemplo utilizando a documentação da ferramenta PIL seria caso a formatação para links de referências conceituais fosse diferente para conceitos diferentes:

![Screenshot](../imagens/img (88).png)

**Verificação:**  
Todas as referências e links internos para conteúdos de mesmo tipo estão estruturadas no mesmo formato.
