# 12- Propriedade: Versionamento

Propriedade de uso. As documentações das diferentes versões disponíveis e mantidas da ferramenta estão disponíveis.

## Pré-Condições
Essa propriedade só é aplicável quando a ferramenta possui mais de uma versão disponível e mantida para uso.

## Atributos

### Atributos de Conteúdo

#### 12.1 Completude
O versionamento é considerado completo quando as documentações de todas as versões da ferramenta estão disponíveis para os desenvolvedores.

**Consequências:**  
Quando o versionamento não está completo, a DFDS se torna inutilizável para desenvolvedores que desejam utilizar as versões que não possuem sua versão contemplada na DFDS.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib todas as versões mantidas e disponíveis da biblioteca possuem documentação:

![Screenshot](../imagens/img (108).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios apenas uma documentação está disponível, porém existe mais de uma versão da ferramenta disponível para uso:

![Screenshot](../imagens/img (109).png)

**Verificação:**  
Todas as versões mantidas e disponíveis da ferramenta possuem documentação disponível para uso.

---

#### 12.2 Corretude
O versionamento é considerado correto quando as documentações disponíveis são referentes às versões disponíveis e mantidas da ferramenta.

**Consequências:**  
Quando o versionamento não está correto, a DFDS se torna inutilizável para as versões disponíveis da ferramenta cujas versões na DFDS refletem a versão incorreta.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib as documentações de cada versão correspondem à versão correta da ferramenta.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam casos de incorreção para o versionamento da documentação. Na documentação da ferramenta Matplotlib seria uma incorreção caso a documentação da versão 3.9 fosse disponibilizada como a documentação da versão 3.8.1

**Verificação:**  
Todas as documentações disponibilizadas são referentes apenas às versões disponíveis da ferramenta.

---

#### 12.3 Relevância
A Relevância não afeta essa propriedade.

---

#### 12.4 Contextualização
O versionamento é considerado contextualizado quando fica claro de qual versão é a documentação que está sendo apresentada durante todo o acesso.

**Consequências:**  
Quando o versionamento não está contextualizado, há falta de entendimento quanto à versão sendo consultada devido à falta de indicação sobre a versão da DFDS.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib no header da documentação está sempre exibida a versão da documentação sendo acessada.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem caso de falta de contextualização de versionamento. Usando Na documentação da ferramenta Matplotlib de exemplo seria um caso de falta de contextualização se a versão da documentação sendo acessada fosse exibida apenas na página inicial.

**Verificação:**  
A versão apresentada da DFDS é visível durante todo o acesso à DFDS.

---

### Atributos de Apresentação

#### 12.5 Boa legibilidade
A Boa legibilidade não afeta essa propriedade.

---

#### 12.6 Clareza
O versionamento é considerado claro quando fica explícito que existem diferentes versões da documentação disponíveis.

**Consequências:**  
Quando o versionamento não está claro, há dificuldade para encontrar informações sobre uma versão da ferramenta devido à dificuldade de identificar que há diferentes versões da DFDS disponíveis.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta Matplotlib a versão da documentação é exibida em uma caixa de seleção, deixando claro que é possível alterar a versão a qualquer momento:

![Screenshot](../imagens/img (111).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta PIL a versão da documentação é exibida, mas para alterá-la é necessário acessar a página “Release notes”:

![Screenshot](../imagens/img (128).png)

**Verificação:**  
Todas as versões da documentação possuem um indicador de que existem outras versões disponíveis.

---

#### 12.7 Estrutura organizada
A Estrutura organizada não afeta essa propriedade.
