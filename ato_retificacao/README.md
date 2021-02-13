# Ato de Retificação

Primeiro é necessário verificar se existem atos de retificação no DODF, para isso basta pressionar CTRL+F e pesquisar pelo termo "LEIA-SE". Desta forma, será possível encontrar os atos de retificação em todo o documento do DODF. Depois, verifique se o ato de retificação é de **cargo comissionado** ou relativo a **cargo efetivo**, pois isso influencia nos tipos de entidades que serão anotadas.

## Link para vídeo no YouTube

Clique [AQUI](https://www.youtube.com/watch?v=J57YgiIG2mg) para assistir um vídeo explicativo de como anotar os atos de retificação e suas entidades. O vídeo aborda tanto a fase da anotação, como a fase de revisão, em que as relações entre os atos e as entidades devem ser criadas.

## Padrão do ato: retificação de Cargo Comissionado e Funções de Confiança

### Tabela de entidade e padrões

As entidades que deverão ser identificadas são:

ID | Rótulo | Entidade (descrição)  | Padrão | Obrigatório?
------- | ------- | ------- | ------- | -------
(1) | tipo_documento | Tipo de documento | Sem Padrão | Sim
(2) | data_documento | Data do documento onde está o item tornado sem efeito | Sem Padrão | Sim
(3) | numero_dodf | Número do DODF | Após 'n°' | Não
(4) | data_dodf | Data do DODF | Sem Padrão | Sim
(5) | pagina_dodf | Página do DODF | Após 'página' | Não
(6) | tipo_ato | Tipo de ato |	Tamanho e detalhamento variáveis, após 'ato que' | Sim
(7) | nome | Nome do Servidor |	Letras maiúsculas | Não
(8) | lotacao | Lotação |	Sem Padrão | Sim
(9) | informacao_errada | Informação Errada |	Após 'ONDE SE LÊ' | Sim
(10) | informacao_corrigida | Informação Corrigida |	Após 'LEIA-SE' | Sim
(11) | tipo_edicao | Tipo de edição |	Sem Padrão | Não

Os atos de retificação possuem os seguintes padrões, conforme o documento de requisitos do TCDF:

#### Padrão 1

No **[tipo_documento] (1)** de **[data_documento] (2)**, publicado no DODF n° **[numero_dodf] (3)**, de **[data_dodf] (4)**, página **[pagina_dodf] (5)**, o ato que **[tipo_ato] (6)** **[nome] (7)**, do(a) **[lotacao] (8)**, onde se lê: **[informacao_errada] (9)**, leia-se **[informacao_corrigida] (10)**.

#### Padrão 2

No **[tipo_documento] (1)** de **[data_documento] (2)**, publicado na Edição Extra n° **[numero_dodf] (3)**, de **[data_dodf] (4)**, página **[pagina_dodf] (5)**, o ato que **[tipo_ato] (6)** **[nome] (7)**, do(a) **[lotacao] (8)**, onde se lê: **[informacao_errada] (9)**, leia-se **[informacao_corrigida] (10)**.

#### Padrão 3

No **[tipo_documento] (1)** de **[data_documento] (2)**, publicado no Suplemento ao DODF n° **[numero_dodf] (3)**, de **[data_dodf] (4)**, página **[pagina_dodf] (5)**, o ato que **[tipo_ato] (6)** **[nome] (7)**, do(a) **[lotacao] (8)**, onde se lê: **[informacao_errada] (9)**, leia-se **[informacao_corrigida] (10)**.

#### Padrão 4

No **[tipo_documento] (1)** de **[data_documento] (2)**, publicado no DODF n° **[numero_dodf] (3)**, de **[data_dodf] (4)**, página **[pagina_dodf] (5)**, o ato que **[tipo_ato] (6)** **[nome] (7)**, do(a) **[lotacao] (8)**, onde se lê: **[informacao_errada] (9)**, leia-se **[informacao_corrigida] (10)**; onde se lê: **[informacao_errada] (9)**, leia-se **[informacao_corrigida] (10)**.

### Exemplos de atos de retificação de cargo comissionado.

RETIFICAÇÃO ...

> No **Decreto(1)** de **18 de fevereiro de 2019(2)**, publicado no DODF nº **35(3)**, de **19 de fevereiro de 2019(4)**, página **23(5)**, o ato que **exonerou(6)** **PRISCILA SPINDOLA DA COSTA SIMPLICIO(7)**, da **Secretaria de Estado de Saúde do Distrito Federal(8)**, ONDE SE LÊ: **"EXONERAR PRISCILA SPINDOLA DA COSTA SIMPLICIO..."(9)**, LEIA-SE: **"EXONERAR, a pedido, PRISCILA SPINDOLA DA COSTA SIMPLICIO..."(10)**.

> No **Decreto(1)** de **19 de novembro de 2019(2)**, publicado no DODF nº **220(3)**, de **20 de novembro de 2019(4)**, página **20(5)**, o ato que **exonerou(6)**, a pedido, **SÉRGIO ROBERTO DE SOUZA LIMA(7)**, ONDE SE LÊ: **"...da Secretaria de Estado de Saúde do Distrito Federal."(9)**, LEIA-SE: **"...da Secretaria de Estado de Saúde do Distrito Federal, a contar de 25 de setembro de 2019."(10)**.

> No **Decreto(1)** de **17 de janeiro de 2020(2)**, publicado no DODF nº **13(3)**, de **20 de janeiro de 2020(4)**, página **11(5)**, o ato que **nomeou(6)** **DENISE RIBEIRO DE ALEXANDRIA ARAUJO(7)**, da **Secretaria de Estado de Saúde do Distrito Federal(8)**. ONDE SE LÊ: **"...matrícula 1.682.701-35..."(9)** LEIA-SE: **"...1.682.701-5..."(10)**.

> No **Decreto(1)** de **11 de fevereiro de 2019(2)**, publicado no DODF nº **30(3)**, de **12 de fevereiro de 2019(4)**, página **14(5)**, o ato que **nomeou(6)** **CELIA MACHADO DE SOUZA(7)** do **Instituto de Defesa do Consumidor do Distrito Federal - PROCON/DF(8)**, ONDE SE LÊ: **"...de Assessor..."(9)**, LEIA-SE:**"...de Assessor Técnico..."(10)**; o ato que **exonerou(6)** **MAURICIO ANTÔNIO DE MEDEIROS(7)**, ONDE SE LÊ: **"...de Assessor..."(9)**, LEIA-SE:**".... de Assessor Técnico..."(10)**; o ato que **nomeou(6)** **MAURICIO ANTÔNIO DE MEDEIROS(7)**, ONDE SE LÊ: **"...de Assessor..."(9)**, LEIA-SE:**"....de Assessor Técnico..."(10)**; o ato que **exonerou(6)** **BRENDA CARVALHO DE ARAÚJO(7)**, ONDE SE LÊ: **"...de Assessor..."(9)**, LEIA-SE:**"...de Assessor Técnico..."(10)**;

Casos não contemplados no documento de requisitos do TCDF:

> Na **Portaria(1)** nº 07(2), de **15 de janeiro de 2020(2)**, publicada no DODF nº **15(3)**, de **22 de janeiro de 2020(4)**, página **25(5)**, no Art 2º, Inciso I ONDE SE LÊ: **"...VALÉRIA DE SOUZA ROCHA..."(9)**, LEIA-SE: **"...VALÉRIA DE SOUSA ROCHA..."(10)** e ONDE SE LÊ **"...Subsecretaria Adjunta"(9)** LEIA-SE: **"...Secretaria Adjunta..."(10)**.

## Retificação - Cargo efetivo

No **[tipo_documento] (1)** de **[data_documento] (3)**, publicado no DODF n° **[numero_dodf] (4)**, de **[data_dodf] (5)**, página **[pagina_dodf] (6)**, o ato que **[tipo_ato] (7)** **[nome] (8)**, do(a) **[lotacao] (14)**, onde se lê: **[informacao_errada] (15)**, leia-se **[informacao_corrigida] (16)**; onde se lê: **[informacao_errada] (16)**, leia-se **[informacao_corrigida] (17)**.

RETIFICAR o **[tipo_documento] (1)** de **[data_documento] (3)**, publicado no DODF nº **[numero_dodf] (4)**, de **[data_dodf] (5)**, referente **[tipo_ato] (7)** ao(à) servidor(a): **[nome] (8)**, matrícula **[matricula] (9)**, **[cargo_efetivo] (10)**, Classe **[classe] (11)**, Padrão **[padrao] (13)**, do **[lotacao] (14)**, matrícula SIAPE no **[matricula_siape] (12)**, para constar onde se lê: **[informacao_errada] (15)**, leia-se **[informacao_corrigida] (16)**, mantendo-se os demais termos do **[tipo_de_ato] (7)**.

### Tabela de entidades e padrões

As entidades que deverão ser identificadas são:

ID | Rótulo | Entidade (descrição)  | Padrão  
------- | ------- | ------- | -------
(1) | tipo_documento | Tipo de documento | Sem Padrão
(2) | numero_documento | Número do documento onde está o item tornado sem efeito (2) | Sem Padrão
(3) | data_documento | Data do documento onde está o item tornado sem efeito (2) | Sem Padrão
(4) | numero_dodf | Número do DODF | Após 'n°'
(5) | data_dodf | Data do DODF | Sem Padrão
(6) | pagina_dodf | Página do DODF | Após 'página'
(7) | tipo_ato | Tipo de ato |	Tamanho e detalhamento variáveis, após 'ato que'
(8) | nome | Nome do Servidor |	Letras maiúsculas
(9) | matricula | Matrícula do Servidor |	Após 'matrícula n°'
(10) | cargo_efetivo | Cargo Efetivo do Servidor |	Letras maiúsculas
(11) | classe | Nome do Servidor |	Após cargo
(12) | matricula_SIAPE | Nome do Servidor |	Após cargo
(13) | padrao | Padrão do Servidor |	Após Classe
(14) | lotacao | Lotação |	Sem Padrão
(15) | informacao_errada | Informação Errada |	Após 'ONDE SE LÊ'
(16) | informacao_corrigida | Informação Corrigida |	Após 'LEIA-SE'
(17) | tipo_edicao | Tipo de edição |	Sem Padrão

### Exemplos de atos de retificação de cargo efetivo

> RETIFICAÇÃO No **Despacho do Secretário(1)**, de **21 de novembro de 2018(3)**, publicado no DODF nº **223(4)**, de **25 de novembro de 2019(5)**, pág. **08(6)**, vinculado ao Processo: 00002-00006250/2019-15, de interesse do servidor **WILSON GOMES DE OLIVEIRA(8)**, matrícula nº **1.431.009-0(9)**, **Analista em Políticas Públicas e Gestão Governamental(10)**, desta **Secretaria de Estado de Economia do Distrito Federal(13)**, ONDE SE LÊ: **"...para ter exercício no Cargo em Comissão, Símbolo DAS-04, de Superintendente de Gestão Administrativa..."(14)** LEIA-SE: **"...para ter exercício no Cargo em Comissão, Símbolo DAS-04, de Superintendente de Gestão e Desenvolvimento de Pessoas..."(15)**.

> RETIFICAR, na **Ordem de Serviço(1)** de **06 de junho de 1989(3)**, publicada no DODF nº **108(4)** - Suplemento, de **09/06/1989(5)**, pág. **15(6)**, o ato que **averbou(7)** o tempo de serviço militar do Servidor **MANOEL SANTOS DE SOUZA(8)**, matrícula nº **30.218-X(9)**, para fazer constar: ONDE SE LÊ:**"...Averba 303 dias prestados ao Ministério do Exército no período de 15.01.75 a 13.11.75, contados para fins de adicionais e aposentadoria..."(15)**. LEIA-SE: **"...Averba 304 dias líquidos prestados ao Ministério do Exército como Serviço Militar no período de 15.01.75 a 13.11.75, conforme demonstrado na Certidão de Tempo de Serviço emitida pelo Ministério da Defesa, para fins de adicionais e aposentadoria..."(16)**.

> RETIFICAR, na **Ordem de Serviço(1)** coletiva nº **98(2)**, de **26/11/2019(3)**, publicada no DODF nº **225(4)**, de **27/11/2019(5)**, o ato que **concedeu(7)** pensão vitalícia a MARIA SOCORRO FERREIRA DE BARROS, cônjuge do ex-servidor **JERÔNIMO JANUÁRIO DE BARROS(8)**, matrícula nº **00.662-X(9)**, **Técnico em Políticas Públicas e Gestão Governamental(10)**, Classe **Única(11)**, Padrão **IX(13)**, do **Quadro de Pessoal do Distrito Federal(14)**, para corrigir a matrícula do ex-servidor, onde se lê: **"matrícula nº 00.662-X"(15)**, leia-se: **"matrícula nº 00.622X"(16)**, ficando ratificados os demais termos da concessão inicial. Processo nº 00413-00005231/2019-21.

## Sugestão de como realizar a anotação de um ato de retificação (ambos casos):

1. **Delimite o espaço visual de anotação:** Posicione o texto do DODF na tela do computador que contemple, no mínimo, 1 bloco de texto relacionado ao ato;

2. **Selecione as palavras do tipo de documento(1).** São todas as palavras em caixa alta que aparecem logo após a palavra “RETIFICAR/RETIFICAÇÃO na”;

3. **Anote as informaçes do DODF original da publicação:** anote o **numero_documento**, **data_documento**, **numero_dodf**, **data_dodf** e **pagina_dodf**;

4. **Anote o nome do servidor:** aparece após as informações do DODF de origem;

5. **Anote as informações do servidor:** onde o servidor trabalha, onde está lotado e alguns dados, como **nome**, **matricula**, **cargo_efetivo**, **classe**, **padrao**, **lotacao**;

6. **Anote as informações errada e corrigida, respectivamente**.

7. **Anote os atos de nomeação como um todo.** Anote todas as palavras desde "RETIFICAÇÃO/RETIFICAR” até o ponto final mais próximo após a **informacao_corrigida** ou Processo SEI.


