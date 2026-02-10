# 11- Propriedade: Integração com ferramentas de busca

Propriedade de uso. Utilização de ferramentas de busca textual para facilitar a consulta de informações específicas na documentação.

## Pré-Condições
Essa propriedade só é aplicável se o meio de apresentação escolhido para a DFDS não possuir um mecanismo de busca funcional próprio.

## Atributos

### Atributos de Conteúdo

#### 11.1 Completude
A integração de ferramentas de busca é considerada completa quando a ferramenta de busca integrada na documentação pode ser usada para realizar consultas a todo o conteúdo da documentação.

**Consequências:**  
Quando a integração de ferramentas de busca não está completa, há necessidade de busca manual de conteúdos devido à falta de uma ferramenta para consulta de uma informação específica.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL a ferramenta de busca realiza as consultas comparando o texto da busca com o da documentação, garantindo que todo o conteúdo relevante será incluído na busca.

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Axios não foi adicionada uma ferramenta de busca na própria documentação, deixando a tarefa para a busca integrada no navegador de internet, limitando a busca para a página atual ao invés de toda a documentação.

**Verificação:**  
Todo o conteúdo da DFDS pode ser consultado via ferramenta de busca.

---

#### 11.2 Corretude
A integração de ferramentas de busca é considerada correta quando as consultas realizadas na ferramenta de busca integrada retornam os conceitos e funcionalidades desejados.

**Consequências:**  
Quando a integração de ferramentas de busca não está correta, há necessidade de busca manual de conteúdos devido à falta de uma ferramenta funcional para consulta de informações.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL a busca funciona corretamente, apontando os resultados de acordo com o termo buscado.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não apresentam caso de incorreção na ferramenta de busca. Usando a documentação da ferramenta PIL como exemplo, se ao buscar “Color” aparecessem resultados para o termo “Filter” e nenhum relacionado ao termo “Color”, seria o caso de uma incorreção.

**Verificação:**  
Todas as buscas realizadas na ferramenta integrada apresentam resultados de acordo com a consulta realizada

---

#### 11.3 Relevância
A Relevância não afeta essa funcionalidade.

---

#### 11.4 Contextualização
A Contextualização não afeta essa funcionalidade.

---

### Atributos de Apresentação

#### 11.5 Boa legibilidade
A Boa legibilidade não afeta essa propriedade.

---

#### 11.6 Clareza
A integração de ferramentas de busca é considerada clara quando fica explícito que há uma ferramenta de busca na documentação.

**Consequências:**  
Quando a integração de ferramentas de busca não está clara, há dificuldade de navegação na DFDS devido à dificuldade de identificar que existe uma ferramenta de busca.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL a ferramenta de busca se encontra logo acima do índice da documentação e está presente em todas as páginas.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem casos de falta de clareza na ferramenta de busca. Usando a documentação da ferramenta PIL como exemplo, caso a ferramenta de busca ficasse visível apenas na página inicial, seria um caso de falta de clareza.

**Verificação:**  
A ferramenta de busca é visível por todo o tempo de acesso à documentação.

---

#### 11.7 Estrutura organizada
A integração de ferramentas de busca é considerada organizada estruturalmente quando o padrão visual adotado deixa explícito ao desenvolvedor que ali se encontra uma ferramenta de busca.

**Consequências:**  
Quando a integração de ferramentas de busca não está organizada estruturalmente, há dificuldade de navegação na DFDS devido à dificuldade de encontrar a ferramenta de busca.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL a ferramenta de busca está organizada estruturalmente por estar em uma formatação comumente adotada em  ferramentas de busca:

![Screenshot](../imagens/img (127).png)

**Exemplo de aplicação ruim:**  
Na documentação da ferramenta Matplotlib a ferramenta de busca está em formato diferente do padrão normalmente adotado, deixando-a um pouco escondida do desenvolvedor:

![Screenshot](../imagens/img (107).png)

**Verificação:**  
A ferramenta de busca está disponível em um padrão visual normalmente adotado em ferramentas de busca
