# Ato de Retificação

Primeiro é necessário verificar se existem atos de retificação no DODF, para isso basta pressionar CTRL+F e pesquisar pelo termo "LEIA-SE". Desta forma, será possível encontrar os atos de retificação em todo o documento do DODF. Depois, verifique se o ato de retificação é de **cargo comissionado** ou relativo a **aposentadoria**, pois isso influencia nos tipos de entidades que serão anotadas.

## Retificação de Cargo Comissionado e Funções de Confiança

### Tabela de entidade e padrões 

As entidades que deverão ser identificadas são:
 
ID | Label | Entidade (descrição)  | Padrão  | Obrigatoriedade
------- | ------- | ------- | ------- | -------
(1) | TIPO_DO_DOCUMENTO | Tipo de documento | Sem Padrão | (obrigatório)
(2) | DATA_DOCUMENTO_ITEM_SEM_EFEITO | Data do documento onde está o item tornado sem efeito (2) | Sem Padrão | (obrigatório)
(3) | NUMERO_DODF | Número do DODF | Após 'n°' | (não obrigatório)
(4) | DATA_DODF | Data do DODF | Sem Padrão | (obrigatório)
(5) | PAGINA_DODF | Página do DODF | Após 'página' | (não obrigatório)
(6) | TIPO_DE_ATO | Tipo de ato |	Tamanho e detalhamento variáveis, após 'ato que' | (obrigatório)
(7) | NOME_SERVIDOR | Nome do Servidor |	Letras maiúsculas | (obrigatório)
(8) | LOTACAO | Lotação |	Sem Padrão | (não obrigatório)
(9) | INFORMACAO_ERRADA | Informação Errada |	Após 'ONDE SE LÊ' | (obrigatório)
(10) | INFORMACAO_CORRIGIDA | Informação Corrigida |	Após 'LEIA-SE' | (obrigatório)
(11) | TIPO_EDICAO | Tipo de edição |	Sem Padrão | (não obrigatório)

Os atos de retificação possuem os seguintes padrões, conforme o documento de requisitos do TCDF:

### Padrão 1

No **[TIPO_DO_DOCUMENTO]** de **[DATA_DOCUMENTO_ITEM_SEM_EFEITO]**, publicado no DODF n° **[NUMERO_DODF]**, de **[DATA_DODF]**, página **[PAGINA_DODF]**, o ato que **[TIPO_DE_ATO]** **[NOME_SERVIDOR]**, do(a) **[LOTACAO]**, onde se lê: **[INFORMACAO_ERRADA]**, leia-se **[INFORMACAO_CORRETA]**.

### Padrão 2

No **[TIPO_DO_DOCUMENTO]** de **[DATA_DOCUMENTO_ITEM_SEM_EFEITO]**, publicado na Edição Extra n° **[NUMERO_DODF]**, de **[DATA_DODF]**, página **[PAGINA_DODF]**, o ato que **[TIPO_DE_ATO]** **[NOME_SERVIDOR]**, do(a) **[LOTACAO]**, onde se lê: **[INFORMACAO_ERRADA]**, leia-se **[INFORMACAO_CORRETA]**.

### Padrão 3

No **[TIPO_DO_DOCUMENTO]** de **[DATA_DOCUMENTO_ITEM_SEM_EFEITO]**, publicado no Suplemento ao DODF n° **[NUMERO_DODF]**, de **[DATA_DODF]**, página **[PAGINA_DODF]**, o ato que **[TIPO_DE_ATO]** **[NOME_SERVIDOR]**, do(a) **[LOTACAO]**, onde se lê: **[INFORMACAO_ERRADA]**, leia-se **[INFORMACAO_CORRETA]**.

### Padrão 4

No **[TIPO_DO_DOCUMENTO]** de **[DATA_DOCUMENTO_ITEM_SEM_EFEITO]**, publicado no DODF n° **[NUMERO_DODF]**, de **[DATA_DODF]**, página **[PAGINA_DODF]**, o ato que **[TIPO_DE_ATO]** **[NOME_SERVIDOR]**, do(a) **[LOTACAO]**, onde se lê: **[INFORMACAO_ERRADA]**, leia-se **[INFORMACAO_CORRETA]**; onde se lê: **[INFORMACAO_ERRADA]**, leia-se **[INFORMACAO_CORRETA]**.

### Exemplos de atos de retificação de cargo comissionado.

RETIFICAÇÃO ...

> No **Decreto(1)** de **18 de fevereiro de 2019(2)**, publicado no DODF nº **35(3)**, de **19 de fevereiro de 2019(4)**, página **23(5)**, o ato que **exonerou(6)** **PRISCILA SPINDOLA DA COSTA SIMPLICIO(7)**, da **Secretaria de Estado de Saúde do Distrito Federal(8)**, ONDE SE LÊ: **"EXONERAR PRISCILA SPINDOLA DA COSTA SIMPLICIO..."(9)**, LEIA-SE: **"EXONERAR, a pedido, PRISCILA SPINDOLA DA COSTA SIMPLICIO..."(10)**.

> No **Decreto(1)** de **19 de novembro de 2019(2)**, publicado no DODF nº **220(3)**, de **20 de novembro de 2019(4)**, página **20(5)**, o ato que **exonerou(6)**, a pedido, **SÉRGIO ROBERTO DE SOUZA LIMA(7)**, ONDE SE LÊ: **"...da Secretaria de Estado de Saúde do Distrito Federal."(9)**, LEIA-SE: **"...da Secretaria de Estado de Saúde do Distrito Federal, a contar de 25 de setembro de 2019."(10)**.

> No **Decreto(1)** de **17 de janeiro de 2020(2)**, publicado no DODF nº **13(3)**, de **20 de janeiro de 2020(4)**, página **11(5)**, o ato que **nomeou(6)** **DENISE RIBEIRO DE ALEXANDRIA ARAUJO(7)**, da **Secretaria de Estado de Saúde do Distrito Federal(8)**. ONDE SE LÊ: **"...matrícula 1.682.701-35..."(9)** LEIA-SE: **"...1.682.701-5..."(10)**.

> No **Decreto(1)** de **11 de fevereiro de 2019(2)**, publicado no DODF nº **30(3)**, de **12 de fevereiro de 2019(4)**, página **14(5)**, o ato que **nomeou(6)** **CELIA MACHADO DE SOUZA(7)** do **Instituto de Defesa do Consumidor do Distrito Federal - PROCON/DF(8)**, ONDE SE LÊ: **"...de Assessor..."(9)**, LEIA-SE:**"...de Assessor Técnico..."(10)**; o ato que **exonerou(6)** **MAURICIO ANTÔNIO DE MEDEIROS(7)**, ONDE SE LÊ: **"...de Assessor..."(9)**, LEIA-SE:**".... de Assessor Técnico..."(10)**; o ato que **nomeou(6)** **MAURICIO ANTÔNIO DE MEDEIROS(7)**, ONDE SE LÊ: **"...de Assessor..."(9)**, LEIA-SE:**"....de Assessor Técnico..."(10)**; o ato que **exonerou(6)** **BRENDA CARVALHO DE ARAÚJO(7)**, ONDE SE LÊ: **"...de Assessor..."(9)**, LEIA-SE:**"...de Assessor Técnico..."(10)**;

Casos não contemplados no documento de requisitos do TCDF:

> Na **Portaria(1)** nº 07(2), de **15 de janeiro de 2020(2)**, publicada no DODF nº **15(3)**, de **22 de janeiro de 2020(4)**, página **25(5)**, no Art 2º, Inciso I ONDE SE LÊ: **"...VALÉRIA DE SOUZA ROCHA..."(9)**, LEIA-SE: **"...VALÉRIA DE SOUSA ROCHA..."(10)** e ONDE SE LÊ **"...Subsecretaria Adjunta"(9)** LEIA-SE: **"...Secretaria Adjunta..."(10)**.

## Retificação - Cargo efetivo

RETIFICAR o **[TIPO_DO_DOCUMENTO]** de **[DATA_DOCUMENTO_ITEM_SEM_EFEITO]**, publicado no DODF nº **[NUMERO_DODF]**, de **[DATA_DODF]**, referente **[TIPO_DE_ATO]** ao(à) servidor(a): **[NOME_SERVIDOR]**, **[CARGO_EFETIVO]**, matrícula **[MATRÍCULA]**, Classe **[CLASSE]**, Padrão **[PADRAO]**, do **[LOTACAO]**, matrícula SIAPE no **[MATRICULA_SIAPE]**, para constar onde se lê: **[INFORMACAO_ERRADA]**, leia-se **[INFORMACAO_CORRETA]**, mantendo-se os demais termos do **[TIPO_DE_ATO]**.

### Tabela de entidades e padrões

As entidades que deverão ser identificadas são:
 
ID | Label | Entidade (descrição)  | Padrão  | Obrigatoriedade
------- | ------- | ------- | ------- | -------
(1) | TIPO_DO_DOCUMENTO | Tipo de documento | Sem Padrão | (obrigatório)
(2) | NUMERO_DOCUMENTO_ITEM_SEM_EFEITO | Número do documento onde está o item tornado sem efeito (2) | Sem Padrão | (obrigatório)
(3) | DATA_DOCUMENTO_ITEM_SEM_EFEITO | Data do documento onde está o item tornado sem efeito (2) | Sem Padrão | (obrigatório)
(4) | NUMERO_DODF | Número do DODF | Após 'n°' | (não obrigatório)
(5) | DATA_DODF | Data do DODF | Sem Padrão | (obrigatório)
(6) | PAGINA_DODF | Página do DODF | Após 'página' | (não obrigatório)
(7) | TIPO_DE_ATO | Tipo de ato |	Tamanho e detalhamento variáveis, após 'ato que' | (obrigatório)
(8) | NOME_SERVIDOR | Nome do Servidor |	Letras maiúsculas | (obrigatório)
(9) | CARGO_SERVIDOR | Cargo Efetivo do Servidor |	Letras maiúsculas | (obrigatório)
(10) | MATRICULA_SERVIDOR | Matrícula do Servidor |	Após 'matrícula n°' | (obrigatório)
(11) | CLASSE_SERVIDOR | Nome do Servidor |	Após cargo | (não obrigatório)
(12) | PADRAO_SERVIDOR | Padrãodo Servidor |	Após Classe | (não obrigatório)
(13) | LOTACAO | Lotação |	Sem Padrão | (não obrigatório)
(14) | INFORMACAO_ERRADA | Informação Errada |	Após 'ONDE SE LÊ' | (obrigatório)
(15) | INFORMACAO_CORRIGIDA | Informação Corrigida |	Após 'LEIA-SE' | (obrigatório)
(16) | TIPO_EDICAO | Tipo de edição |	Sem Padrão | (não obrigatório)
  
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


### Exemplos de atos de retificação de cargo efetivo

> RETIFICAÇÃO No **Despacho do Secretário(1)**, de **21 de novembro de 2018(2)**, publicado no DODF nº **223(3)**, de **25 de novembro de 2019(4)**, pág. **08(5)**, vinculado ao Processo: 00002-00006250/2019-15, de interesse do servidor **WILSON GOMES DE OLIVEIRA(7)**, matrícula nº **1.431.009-0(8)**, **Analista em Políticas Públicas e Gestão Governamental**, desta Secretaria de Estado de Economia do Distrito Federal, ONDE SE LÊ: "...para ter exercício no Cargo em Comissão, Símbolo DAS-04, de Superintendente de Gestão Administrativa..." LEIA-SE: "...para ter exercício no Cargo em Comissão, Símbolo DAS-04, de Superintendente de Gestão e Desenvolvimento de Pessoas..."

> RETIFICAR, na Ordem de Serviço de 06 de junho de 1989, publicada no DODF nº 108 - Suplemento, de 09/06/1989, pág. 15, o ato que averbou o tempo de serviço militar do Servidor MANOEL SANTOS DE SOUZA, matrícula nº 30.218-X, para fazer constar: ONDE SE LÊ:"...Averba 303 dias prestados ao Ministério do Exército no período de 15.01.75 a 13.11.75, contados para fins de adicionais e aposentadoria...". LEIA-SE: "...Averba 304 dias líquidos prestados ao Ministério do Exército como Serviço Militar no período de 15.01.75 a 13.11.75, conforme demonstrado na Certidão de Tempo de Serviço emitida pelo Ministério da Defesa, para fins de adicionais e aposentadoria..."

> 
> Na **Ordem de Serviço(1)** n° **03(2)**, de **08 de janeiro de 2020(3)**, publicada no DODF n° **10(4)** de **15 de janeiro de 2020(5)**, página **12(6)**, solicitamos a republicação, tendo em vista o erro apresentado no nome do Membro **LIEZER ROSA DE FREITAS(8)**, matrícula: 35.493-7. ONDE SE LÊ: "...LIEZER ROSA DA SILVA, matrícula: 35.493-7...", LEIA-SE: "...LIEZER ROSA DE FREITAS, matrícula: 35.493-7...". Documento assinado digitalmente conforme MP nº 2.200-2 de 24/08/2001, que institui a Infraestrutura de Chaves Públicas Brasileira - ICP-Brasil.


### Sugestão de como ralizar a anotação de um ato de retificação - aposentadorias:

### Sugestão de como realizar a anotação de um ato de retificação:

1. **Delimite o espaço visual de anotação:** Posicione o texto do DODF na tela do computador que contemple, no mínimo, 1 bloco de texto relacionado ao ato.

2. **Anote todos os nomes dos servidores.** São todas as palavras em caixa alta que aparecem logo após a palavra “NOMEAR”, ficar atento porque às vezes o cargo efetivo aparece aparece antes do nome, mas ela estará em caixa baixa. Anote apenas as palavras em caixa alta.

3. **Anote os cargos efetivos.** Eles aparecerão perto do nome, ou antes ou depois.

4. **Anote as matrículas.** Sempre aparecem logo depois da palavra “matrícula”.

5. **Anote os símbolos.** Sempre aparecem logo depois da palavra “símbolo”.

6. **Anote os cargos em comissão.** Sempre aparecem depois dos símbolos.

7. **Anote os orgãos** Sempre são as últimas palavras, ficam entre a última vírgula e o ponto final.

8. **Anote as hierarquias das lotações.** São todas as palavras que ficam entre o cargo em comissão e o órgão. O tamanho deste atributo varia bastante.  

9. **Anote os atos de nomeação como um todo.** Anote todas as palavras desde ‘NOMEAR” até o ponto final mais próximo.

### Observações Gerais sobre os Atos de Retificação:

* Nem sempre o ato terá todos os atributos, mas anote todos os que você encontrar.  
* Não anote vírgulas e pontos, a não ser que eles estejam dentro do atributo, como acontece em Hierarquia de Loatação.  
* Tenha muito cuidado para não apagar todoas a anotações de um documento, mesmo tendo função de anotador.
* Recomendo sempre que for fazer uma pausa mais prolongada, que salve um arquivo xml com as suas anotações, por precaução. Desta forma, você terá um back up caso aconteça alguma coisa e você perca todas as anotações feitas no documento, e com isso não terá que começar a anotar do zero.
