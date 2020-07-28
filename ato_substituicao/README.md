# Ato de Substituição de Funções

Primeiro é necessário verificar se existem atos de substituiçaõ no DODF, bastando pressionar CTRL+F e pesquisar pelo termo "para substituir". Após encontrar um ou mais blocos relacionados a substituição, deve-se fazer a correspondência de cada bloco de texto em relação a um dos padrões definidos a seguir.

## Padrão

DESIGNAR o **[NOME_SERVIDOR_SUBSTITUTO]**, matrícula nº **[MATRICULA_SERVIDOR_SUBSTITUTO]**, para substituir **[NOME_SERVIDOR_SUBSTITUIDO]**, matrícula nº **[MATRICULA_SERVIDOR_SUBSTITUIDO]**, **[CARGO_SERVIDOR_SUBSTITUTO]**, **[SIMBOLO_CARGO_SUBSTITUTO]**, de **[DATA_DODF]**, referente **[TIPO_DE_ATO]** ao(à) servidor(a): **[NOME_SERVIDOR]**,  , Classe **[CLASSE]**, Padrão **[PADRAO]**, do **[LOTACAO]**, matrícula SIAPE no **[MATRICULA_SIAPE]**, para constar onde se lê: **[INFORMACAO_ERRADA]**, leia-se **[INFORMACAO_CORRETA]**, mantendo-se os demais termos do **[TIPO_DE_ATO]**.

## Tabela de entidades e padrões

As entidades que deverão ser identificadas são:
 
ID | Label | Entidade (descrição)  | Padrão  | Obrigatoriedade
------- | ------- | ------- | ------- | -------
(1) | NOME_SERVIDOR_SUBSTITUTO | Nome do Servidor | Letras maiúsculas | (obrigatório)
(2) | MATRICULA_SERVIDOR_SUBSTITUTO | Matrícula do Servidor Substituto | Letras maiúsculas aṕos 'DESIGNAR' | (obrigatório)
(3) | NOME_SERVIDOR_SUBSTITUIDO | Nome do Servidor a ser Substituido | Após 'para substituir' | (obrigatório)
(4) | MATRICULA_SERVIDOR_SUBSTITUIDO | Matrícula do Servidor a ser Substituido | Após 'matrícula n°' | (não obrigatório)
(5) | CARGO_SERVIDOR_SUBSTITUTO | Cargo efetivo ou comissionado do servidor substituto | Sem Padrão | (não obrigatório)
(6) | SIMBOLO_CARGO_SUBSTITUTO | Símbolo do cargo do servidor substituto | Após 'Símbolo' | (não obrigatório)
(7) | CARGO_COMISSIONADO_OBJETO | Cargo comissionado objeto da substituição |	Sem padrão | (não obrigatório)
(8) | SIMBOLO_CARGO_OBJETO | Símbolo do cargo comissionado objeto da substituição |	Após 'Símbolo' | (não obrigatório)
(9) | HIERARQUIA_LOTACAO | Hierarquia da Lotação|	Sem Padrão | (não obrigatório)
(10) | ORGAO | Órgão |	Sem Padrão | (obrigatório)
(11) | DATA_INICIAL | Data Inicial da Vigência |	Após 'no período de' | (não obrigatório)
(12) | DATA_FINAL | Data Final de Vigência |	Após Data Inicial da Vigência| (não obrigatório)
(13) | MATRICULA_SIAPE | Matrícula SIAPE |	Após 'SIAPE' | (não obrigatório)
(14) | MOTIVO | Motivo da substituição |	'em virtude ou a pedido' | (não obrigatório)
  
## Exemplos de atos de substituição de função

> Art. 1º Designar **ANA PAULA VEIGA TRIERS(1)**, matrícula **1402016-5(2)**, como **executora substituta do Convênio nº 008/2019 - NCC/CODAG/FHB(5)**, em substituição a **Ysis Martins Aquino(3)**, matrícula: **1681885-7($)**, objeto do processo nº 00063-00002158/2019-34. Art. 2º Designar ANA PAULA VEIGA TRIERS, matrícula 1402016-5, como executora principal do Convênio nº 001/2019 NCC/CODAG/FHB, em substituição a Ysis Martins Aquino, matrícula: 1681885-7, e Ana Louise Ferreira de Araújo, matrícula 1694463-1, como executora substituta do Convênio nº 001/2019 NCC/CODAG/FHB, em substituição a Madellon Melo de Assis, matrícula: 1681964-0, objeto do processo nº 00063-00000127/2019-49. Art. 3º Esta Instrução entra em vigor na data de sua publicação. BARBARA DE JESUS SIMÕES

> DESIGNAR LUCILENE RODRIGUES DE OLIVEIRA DO NASCIMENTO, matrícula nº 1.690.884-8, Assessor Técnico, do Gabinete, Símbolo DFA-08, para substituir, sem acumular vencimentos e sem prejuízos de suas atribuições, a servidora JAMEL REIS AL-HAKIM SALGADO, matrícula nº 1.690.175-4, Chefe, do Núcleo de Atendimento, Protocolo e Arquivo, Símbolo DFG-12, da Administração Regional de Planaltina, da Secretaria de Estado de Governo do Distrito Federal, no período de 03 de fevereiro de 2020 a 12 de fevereiro de 2020, por motivo de férias regulamentares da titular. GILSON AMORIM SOBRINHO
 

## Sugestão de como realizar a anotação de um ato de retificação:

1. **Delimite o espaço visual de anotação:** Posicione o texto do DODF na tela do computador que contemple, no mínimo, 1 bloco de texto relacionado ao ato.

2. **Anote todos os nomes dos servidores.** São todas as palavras em caixa alta que aparecem logo após a palavra “NOMEAR”, ficar atento porque às vezes o cargo efetivo aparece aparece antes do nome, mas ela estará em caixa baixa. Anote apenas as palavras em caixa alta.

3. **Anote os cargos efetivos.** Eles aparecerão perto do nome, ou antes ou depois.

4. **Anote as matrículas.** Sempre aparecem logo depois da palavra “matrícula”.

5. **Anote os símbolos.** Sempre aparecem logo depois da palavra “símbolo”.

6. **Anote os cargos em comissão.** Sempre aparecem depois dos símbolos.

7. **Anote os orgãos** Sempre são as últimas palavras, ficam entre a última vírgula e o ponto final.

8. **Anote as hierarquias das lotações.** São todas as palavras que ficam entre o cargo em comissão e o órgão. O tamanho deste atributo varia bastante.  

9. **Anote os atos de nomeação como um todo.** Anote todas as palavras desde ‘NOMEAR” até o ponto final mais próximo.
