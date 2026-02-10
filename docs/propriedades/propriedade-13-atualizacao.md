# 13- Atributo: Atualização

Atributo de conteúdo. A DFDS é atualizada em conjunto com a ferramenta, impedindo que informações erradas (desatualizadas) sejam transmitidas para o desenvolvedor.

## Pré-Condições
Esse atributo só é aplicável quando a ferramenta passa por uma atualização que altera sua forma de uso.

#### Definição
A DFDS é considerada atualizada quando, ao atualizar a ferramenta, todas as alterações são incorporadas na DFDS. Ou seja, as Regras descritas anteriormente são revisitadas para garantir que não existe nenhuma inconsistência na DFDS em relação à ferramenta atualizada.

**Consequências:**  
Quando a DFDS não está atualizada, informações erradas são transmitidas para o desenvolvedor.

**Exemplo de boa aplicação:**  
Na documentação da ferramenta PIL a versão da documentação é a mesma da versão mais recente da biblioteca, 12.1.0.

**Exemplo de aplicação ruim:**  
As documentações de exemplo não possuem casos de problema de atualização, mas caso na documentação da ferramenta PIL a próxima versão da biblioteca, digamos 12.1.1, fosse lançada sem que uma nova versão da documentação fosse criada e disponibilizada, teríamos um erro de atualização.

**Verificação:**  
Todo o conteúdo da DFDS está de acordo com a versão mais atualizada da ferramenta.
