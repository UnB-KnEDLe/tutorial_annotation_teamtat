# Ato de Retificação

Primeiro é necessário verificar se existem atos de retificação no DODF, para isso basta pressionar CTRL+F e pesquisar pelo termo "LEIA-SE". Desta forma, será possível encontrar os atos de retificação em todo o documento do DODF. Depois, verifique se o ato de retificação é de **cargo comissionado** ou relativo a **aposentadoria**, pois isso influencia nos tipos de entidades que serão anotadas.

## Retificação de Cargo Comissionado e Funções de Confiança

### Tabela de entidade e padrões 

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
(9) | MATRICULA_SERVIDOR | Matrícula do Servidor |	Após 'matrícula n°' | (não obrigatório)
(10) | LOTACAO | Lotação |	Sem Padrão | (não obrigatório)
(11) | INFORMACAO_ERRADA | Informação Errada |	Após 'ONDE SE LÊ' | (obrigatório)
(12) | INFORMACAO_CORRIGIDA | Informação Corrigida |	Após 'LEIA-SE' | (obrigatório)
(13) | TIPO_EDICAO | Tipo de edição |	Sem Padrão | (não obrigatório)

Os atos de retificação possuem os seguintes padrões, conforme o documento de requisitos do TCDF:

### Padrão 1

No **[TIPO_DO_DOCUMENTO]** de **[DATA_DOCUMENTO_ITEM_SEM_EFEITO]**, publicado no DODF nro **[NUMERO_DODF]**, de **[DATA_DODF]**, página **[PAGINA_DODF]**, o ato que **[TIPO_DE_ATO]** **[NOME_SERVIDOR]**, matrícula n° **[MATRICULA_SERVIDOR]**, do(a) **[LOTACAO]**, onde se lê: **[INFORMACAO_ERRADA]**, leia-se **[INFORMACAO_CORRETA]**.

### Padrão 2

No [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado na Edição Extra n° [NUMERO_DODF], de [DATA_DODF], página [PAGINA_DODF], o ato que [TIPO_DE_ATO] [NOME_SERVIDOR], do(a) [LOTACAO], onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA].

### Padrão 3

No [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado no Suplemento ao DODF n° [NUMERO_DODF], de [DATA_DODF], página [PAGINA_DODF], o ato que [TIPO_DE_ATO] [NOME_SERVIDOR], do(a) [LOTACAO], onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA].

### Padrão 4

No [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado no DODF n° [NUMERO_DODF], de [DATA_DODF], página [PAGINA_DODF], o ato que [TIPO_DE_ATO] [NOME_SERVIDOR], do(a) [LOTACAO], onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA]; onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA].

### Exemplos de atos de retificação de cargo comissionado.

> No **Decreto(1)** de **18 de fevereiro de 2019(3)**, publicado no DODF nº **35(4)**, de **19 de fevereiro de 2019(5)**, página **23(6)**, o ato que **exonerou(7)** **PRISCILA SPINDOLA DA COSTA SIMPLICIO(8)**, da **Secretaria de Estado de Saúde do Distrito Federal(10)**, ONDE SE LÊ: **"EXONERAR PRISCILA SPINDOLA DA COSTA SIMPLICIO..."(11)**, LEIA-SE: **"EXONERAR, a pedido, PRISCILA SPINDOLA DA COSTA SIMPLICIO..."(12)**.

> No **Decreto(1)** de **19 de novembro de 2019(3)**, publicado no DODF nº **220(4)**, de **20 de novembro de 2019(5)**, página **20(6)**, o ato que **exonerou(7)**, a pedido, **SÉRGIO ROBERTO DE SOUZA LIMA(8)**, ONDE SE LÊ: **"...da Secretaria de Estado de Saúde do Distrito Federal."(11)**, LEIA-SE: **"...da Secretaria de Estado de Saúde do Distrito Federal, a contar de 25 de setembro de 2019."(12)**.

> No **Decreto(1)** de **17 de janeiro de 2020(3)**, publicado no DODF nº **13(4)**, de **20 de janeiro de 2020(5)**, página **11(6)**, o ato que **nomeou(7)** **DENISE RIBEIRO DE ALEXANDRIA ARAUJO(8)**, da **Secretaria de Estado de Saúde do Distrito Federal(10)**. ONDE SE LÊ: **"...matrícula 1.682.701-35..."(11)** LEIA-SE: **"...1.682.701-5..."(12)**.


Casos não contemplados no documento de requisitos do TCDF:

> Na **Portaria(1)** nº **07(2)**, de **15 de janeiro de 2020(3)**, publicada no DODF nº **15(4)**, de **22 de janeiro de 2020(5)**, página **25(6)**, no Art 2º, Inciso I ONDE SE LÊ: **"...VALÉRIA DE SOUZA ROCHA..."(11)**, LEIA-SE: **"...VALÉRIA DE SOUSA ROCHA..."(12)** e ONDE SE LÊ "...Subsecretaria Adjunta" LEIA-SE: "...Secretaria Adjunta..."


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


## Retificação - Cargo efetivo

RETIFICAR o [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado no DODF No [NUMERO_DODF], de [DATA_DODF], referente [TIPO_DE_ATO] ao(à) servidor(a): [NOME_SERVIDOR], [CARGO_EFETIVO], matrícula [MATRÍCULA], [CARGO_EFETIVO], Classe [CLASSE], Padrão [PADRAO], do [LOTACAO], matrícula SIAPE no [MATRICULA_SIAPE], para constar onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA], mantendo-se os demais termos do [TIPO_DE_ATO].

## Tabela de entidades e padrões

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

> RETIFICAÇÃO No ***Decreto*** de ***11 de fevereiro de 2019***, publicado no DODF nº ***30***, de ***12 de fevereiro de 2019***, página 14, o ato que nomeou CELIA MACHADO DE SOUZA do Instituto de Defesa do Consumidor do Distrito Federal - PROCON/DF, ONDE SE LÊ: "...de Assessor...", LEIA-SE:"...de Assessor Técnico..."; o ato que exonerou MAURICIO ANTÔNIO DE MEDEIROS, ONDE SE LÊ: "...de Assessor...", LEIA-SE:".... de Assessor Técnico..."; o ato que nomeou MAURICIO ANTÔNIO DE MEDEIROS, ONDE SE LÊ: "...de Assessor...", LEIA-SE:"....de Assessor Técnico..."; o ato que exonerou BRENDA CARVALHO DE ARAÚJO, ONDE SE LÊ: "...de Assessor...", LEIA-SE:"...de Assessor Técnico..."; o ato que nomeou BRENDA CARVALHO DE ARAÚJO, ONDE SE LÊ: "...de Assessor...", LEIA-SE:"...de Assessor Técnico..."; o ato que exonerou CRISTIAN JUNIO DO NASCIMENTO, ONDE SE LÊ: "...de Assessor...", LEIA-SE:"...de Assessor Técnico..."; o ato que nomeou CRISTIAN JUNIO DO NASCIMENTO, ONDE SE LÊ: "...de Assessor..." LEIA-SE:"...de Assessor Técnico...";

> RETIFICAÇÃO No **Despacho do Secretário(1)**, de **21 de novembro de 2018(2)**, publicado no DODF nº **223(3)**, de **25 de novembro de 2019(4)**, pág. **08(5)**, vinculado ao Processo: 00002-00006250/2019-15, de interesse do servidor **WILSON GOMES DE OLIVEIRA(7)**, matrícula nº **1.431.009-0(8)**, **Analista em Políticas Públicas e Gestão Governamental**, desta Secretaria de Estado de Economia do Distrito Federal, ONDE SE LÊ: "...para ter exercício no Cargo em Comissão, Símbolo DAS-04, de Superintendente de Gestão Administrativa..." LEIA-SE: "...para ter exercício no Cargo em Comissão, Símbolo DAS-04, de Superintendente de Gestão e Desenvolvimento de Pessoas..."

> RETIFICAR, na Ordem de Serviço de 06 de junho de 1989, publicada no DODF nº 108 - Suplemento, de 09/06/1989, pág. 15, o ato que averbou o tempo de serviço militar do Servidor MANOEL SANTOS DE SOUZA, matrícula nº 30.218-X, para fazer constar: ONDE SE LÊ:"...Averba 303 dias prestados ao Ministério do Exército no período de 15.01.75 a 13.11.75, contados para fins de adicionais e aposentadoria...". LEIA-SE: "...Averba 304 dias líquidos prestados ao Ministério do Exército como Serviço Militar no período de 15.01.75 a 13.11.75, conforme demonstrado na Certidão de Tempo de Serviço emitida pelo Ministério da Defesa, para fins de adicionais e aposentadoria..."


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
