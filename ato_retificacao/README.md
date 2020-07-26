# Ato de Retificação

Primeiro é necessário verificar se existem atos de retificação no DODF, para isso basta pressionar CTRL+F e pesquisar pelo termo "LEIA-SE". Desta forma, será possível encontrar os atos de retificação em todo o documento do DODF. Depois, verifique se o ato de retificação é de **cargo comissionado** ou relativo a **aposentadoria**, pois isso influencia nos tipos de entidades que terão que ser anotadas.

## Retificação de Cargo Comissionado e Funções de Confiança


### Tabela de entidade e padrões 

As entidades que deverão ser identificadas são:
 
Entidade  | Padrão    
------- | -------
Tipo de documento (1) | Sem Padrão
Data do documento onde está o item tornado sem efeito (2) | Sem Padrão
Número do DODF (3) | Após 'n°'
Data do DODF (4) | Sem Padrão
Página do DODF  (5)| Após 'página'
Nome do Servidor (6) |	Letras maiúsculas
Lotação  (7)|	Sem Padrão
Informação Errada (8) |	Após 'ONDE SE LÊ'
Informação Corrigida (9) |	Após 'LEIA-SE'
Tipo de edição (10)	|	Sem Padrão
Tipo de Ato (11) |	Após 'ato que'


Os atos de retificação possuem os seguintes padrões, conforme o documento de requisitos do TCDF:

### Padrão 1

No [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado no DODF nro [NUMERO_DODF], de [DATA_DODF], página [PAGINA_DODF], o ato que [TIPO_DE_ATO] [NOME_SERVIDOR], do(a) [LOTACAO], onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA].

- TIPO_DO_DOCUMENTO (não obrigatório): Ordem de Serviço, Prestação de Contas
- DATA_DOCUMENTO_ITEM_SEM_EFEITO (obrigatório): data do documento onde está o item tornado sem efeito;
- NUMERO_DODF (no-obrigatório): número do DODF
- DATA_DODF (obrigatório): data do DODF
- PAGINA_DODF (não-obrigatório): página do DODF
- TIPO_DE_ATO (obrigatório): concessão de abono, aposentadoria, substituição, nomeação etc
- NOME_SERVIDOR (obrigatório): nome do servidor
- LOTACAO (não-obrigatório): local de exercício do cargo
- INFORMACAO_ERRADA (obrigatório): Informação errada
- INFORMACAO_CORRIGIDA (obrigatório): Informação corrigida

### Padrão 2

No [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado na Edição Extra nro [NUMERO_DODF], de [DATA_DODF], página [PAGINA_DODF], o ato que [TIPO_DE_ATO] [NOME_SERVIDOR], do(a) [LOTACAO], onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA].

- TIPO_DO_DOCUMENTO (não obrigatório): Ordem de Serviço, Prestação de Contas
- DATA_DOCUMENTO_ITEM_SEM_EFEITO (obrigatório): data do documento onde está o item tornado sem efeito;
- NUMERO_DODF (no-obrigatório): número do DODF
- DATA_DODF (obrigatório): data do DODF
- PAGINA_DODF (não-obrigatório): página do DODF
- TIPO_DE_ATO (obrigatório): concessão de abono, aposentadoria, substituição, nomeação etc
- NOME_SERVIDOR (obrigatório): nome do servidor
- LOTACAO (não-obrigatório): local de exercício do cargo
- INFORMACAO_ERRADA (obrigatório): Informação errada
- INFORMACAO_CORRIGIDA (obrigatório): Informação corrigida

### Padrão 3

No [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado no Suplemento ao DODF nro [NUMERO_DODF], de [DATA_DODF], página [PAGINA_DODF], o ato que [TIPO_DE_ATO] [NOME_SERVIDOR], do(a) [LOTACAO], onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA].

- TIPO_DO_DOCUMENTO (não obrigatório): Ordem de Serviço, Prestação de Contas
- DATA_DOCUMENTO_ITEM_SEM_EFEITO (obrigatório): data do documento onde está o item tornado sem efeito;
- NUMERO_DODF (no-obrigatório): número do DODF
- DATA_DODF (obrigatório): data do DODF
- PAGINA_DODF (não-obrigatório): página do DODF
- TIPO_DE_ATO (obrigatório): concessão de abono, aposentadoria, substituição, nomeação etc
- NOME_SERVIDOR (obrigatório): nome do servidor
- LOTACAO (não-obrigatório): local de exercício do cargo
- INFORMACAO_ERRADA (obrigatório): Informação errada
- INFORMACAO_CORRIGIDA (obrigatório): Informação corrigida


### Padrão 4

No [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado no DODF nro [NUMERO_DODF], de [DATA_DODF], página [PAGINA_DODF], o ato que [TIPO_DE_ATO] [NOME_SERVIDOR], do(a) [LOTACAO], onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA]; onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA].

- TIPO_DO_DOCUMENTO (não obrigatório): Ordem de Serviço, Prestação de Contas
- DATA_DOCUMENTO_ITEM_SEM_EFEITO (obrigatório): data do documento onde está o item tornado sem efeito;
- NUMERO_DODF (no-obrigatório): número do DODF
- DATA_DODF (obrigatório): data do DODF
- PAGINA_DODF (não-obrigatório): página do DODF
- TIPO_DE_ATO (obrigatório): concessão de abono, aposentadoria, substituição, nomeação etc
- NOME_SERVIDOR (obrigatório): nome do servidor
- LOTACAO (não-obrigatório): local de exercício do cargo
- INFORMACAO_ERRADA (obrigatório): Informação errada
- INFORMACAO_CORRIGIDA (obrigatório): Informação corrigida

### Exemplos de atos de retificação de cargo comissionado.

> 


### Sugestão de como realizar a anotação de um ato de retificação:

1. **Delimite o espaço visual de anotação:** Posicione o texto do DODF na tela do computador que contemple, no mínimo, 1 bloco de texto relacionado ao ato.

2. **Anote todos os nomes dos servidores.** São todas as palavras em caixa alta que aparecem logo após a palavra “NOMEAR”, ficar atento porque às vezes o cargo efetivo aparece aparece antes do nome, mas ela estará em caixa baixa. Anote apenas as palavras em caixa alta.

3. **Anote os cargos efetivos.** Eles aparecerão perto do nome, ou antes ou depois.

4. **Anote as matrículas.** Sempre aparecem logo depois da palavra “matrícula”.

5. **Anote as matrículas SIAPE.** Aparecem depois de “SIAPE”. São bem raras, só se aplicam à Polícia Civil, à Polícia Militar e ao Corpo de Bombeiros Militar.

6. **Anote os símbolos.** Sempre aparecem logo depois da palavra “símbolo”.

7. **Anote os cargos em comissão.** Sempre aparecem depois dos símbolos.

8. **Anote os orgãos** Sempre são as últimas palavras, ficam entre a última vírgula e o ponto final.

9. **Anote as hierarquias das lotações.** São todas as palavras que ficam entre o cargo em comissão e o órgão. O tamanho deste atributo varia bastante.  

10. **Anote os atos de nomeação como um todo.** Anote todas as palavras desde ‘NOMEAR” até o ponto final mais próximo.



## Retificação - Aposentadorias

RETIFICAR o [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado no DODF No [NUMERO_DODF], de [DATA_DODF], referente [TIPO_DE_ATO] ao(à) servidor(a): [NOME_SERVIDOR], [CARGO_EFETIVO], matrícula [MATRÍCULA], [CARGO_EFETIVO], Classe [CLASSE], Padrão [PADRAO], do [LOTACAO], matrícula SIAPE no [MATRICULA_SIAPE], para constar onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA], mantendo-se os demais termos do [TIPO_DE_ATO].

## Tabela de entidades e padrões

As entidades que deverão ser identificadas são:
  
Entidades | Padrão   
-------- | ------- 
Tipo de documento (1) | Sem Padrão
Número do documento onde está o item tornado sem efeito (2) | Sem Padrão
Data do documento onde está o item tornado sem efeito (3) | Sem Padrão
Número do DODF (4) | Após 'n°'
Data do DODF (5) |	Sem Padrão
Página do DODF (6) |	Após 'página'
Nome do Servidor (7) |	Letras maiúsculas
Matrícula (8) |	Após 'matrícula n°'
Cargo Efetivo  (9)|	Sem Padrão
Classe (10) |	Após cargo
Padrão (11) |	Após Classe
Matricula SIAPE (12) |	SIAPE
Informação Errada (13) |	Após 'ONDE SE LÊ'
Informação Corrigida (14) |	Após 'LEIA-SE'  


### Exemplos de atos de retificação - aposentdorias.

> 


### Sugestão de como ralizar a anotação de um ato de retificação - aposentadorias:

1. **Identifique o ato que será anotado.** Por possuir mais entidades a serem anotadas e por muitas delas serem semelhantes, aconselho anotar um ato de nomeação de cargo efetivo de cada vez.

2. **Localize o processo GDF/SEI.** O posicionamento dele dentro do ato varia bastante, mas sempre estará logo após as palavras 'Processo SEI n°'. 

3. **Anote da entidade Edital Normativo até a entidade Data do DODF do Edital de Resultado Final.** Elas costumam aparecer uma após a outra, desta forma fica mais fácil de identificar e mais difícil de se confundir em relação as datas e DODF's.  
  Comece pelo Edital Normativo, depois anote a Data do Edital Normativo, Número do DODF do Edital Normativo, Data do DODF do Edital Normativo, Edital de Resultado Final e por último a Data do Edital de Resultado Final.

4. **Anote as entidades Cargo, Carreira e Orgão.** Elas aparecem uma após a outra, depois das entidades citadas no item anterior.

5. **Anote as Especialidades.** Às vezes pode ter mais de uma, elas aparecem antes da lista com os Nomes dos Candidatos, em letras maiúsculas. 

6. **Anote os Nomes dos Candidatos e suas respectivas Classificações.** Os nomes estarão em letras maiúsculas e a classificação estará logo em seguida. 

7. **Confira se há algum candidato portador de deficiência/ necessidades especiais, se tiver anote.** Estará escrito algo como 'Candidato que se declarou portador de deficiência' ou 'Portador de Deficiência'.

8. **Anote o ato de nomeação como um todo.** Anote todas as palavras desde ‘NOMEAR” até a classificação do último candidato.



### Observações Gerais sobre os Atos de Retificação:

* Nem sempre o ato terá todos os atributos, mas anote todos os que você encontrar.  
* Não anote vírgulas e pontos, a não ser que eles estejam dentro do atributo, como acontece em Hierarquia de Loatação.  
* Tenha muito cuidado para não apagar todoas a anotações de um documento, mesmo tendo função de anotador.
* Recomendo sempre que for fazer uma pausa mais prolongada, que salve um arquivo xml com as suas anotações, por precaução. Desta forma, você terá um back up caso aconteça alguma coisa e você perca todas as anotações feitas no documento, e com isso não terá que começar a anotar do zero.
