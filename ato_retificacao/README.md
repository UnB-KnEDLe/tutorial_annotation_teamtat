# Tutorial de anotação de atos de retificação

Primeiro é necessário verificar se existem atos de nomeação no DODF, para isso basta pressionar CTRL+F e pesquisar pelo termo "LEIA-SE". Desta forma, será possível encontrar os atos de retificação em todo o documento do DODF. Depois, verifique se o ato de retificação é de cargo comissionado ou de cargo efetivo, pois isso influencia nos tipos de entidades que terão que ser anotadas.

## 1. Retificação de Cargo Comissionado e Funções de Confiança

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

### Entidades 

As entidades que deverão ser identificadas são:
 
Descrição  | Padrão    
------- | -------
Nome do Servidor | Letras maiúsculas    
Cargo Efetivo | Sem padrão 
Matrícula | Após 'matrícula n°' 
Matrícula SIAPE | Após 'SIAPE' 
Símbolo | Após 'Símbolo'
LOTACAO | Lotação | 
Cargo em Comissão | Após o atributo Símbolo 
Hierarquia da Lotação | Após o atributo Cargo em Comissão 
Orgão | Após o atributo Hierarquia da Lotação 

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

#### 1.1. Exemplos de atos de retificação de cargo comissionado.

> NOMEAR ***VALÉRIA LEITE BERNIZ*** **(1)**, ***Professor*** **(2)**, matrícula ***211.341-4*** **(3)**, para exercer a Função Gratificada Escolar, Símbolo ***FGE-04*** **(5)**, de ***Diretor*** **(6)**, do ***Centro de Educação Infantil 01 de Brasília, da Coordenação Regional de Ensino do Plano Piloto*** **(7)**, da ***Secretaria de Estado de Educação do Distrito Federal*** **(8)**. 
>




#### 1.1. Exemplos de atos de retificação de cargo comissionado.

> NOMEAR ***VALÉRIA LEITE BERNIZ*** **(1)**, ***Professor*** **(2)**, matrícula ***211.341-4*** **(3)**, para exercer a Função Gratificada Escolar, Símbolo ***FGE-04*** **(5)**, de ***Diretor*** **(6)**, do ***Centro de Educação Infantil 01 de Brasília, da Coordenação Regional de Ensino do Plano Piloto*** **(7)**, da ***Secretaria de Estado de Educação do Distrito Federal*** **(8)**. 
>


**(1)** Nome do servidor  
**(2)** Cargo efetivo  
**(3)** Matrícula  
**(4)** Matrícula SIAPE  
**(5)** Símbolo  
**(6)** Cargo em comissão  
**(7)** Hierarquia da lotação  
**(8)** Órgão  

#### 1.2. Sugestão de como realizar a anotação de um ato de retificação:

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

## 2. Retificação de Cargo Efetivo

RETIFICAR o [TIPO_DO_DOCUMENTO] de [DATA_DOCUMENTO_ITEM_SEM_EFEITO], publicado no DODF No [NUMERO_DODF], de [DATA_DODF], referente [TIPO_DE_ATO] ao(à) servidor(a): [NOME_SERVIDOR], [CARGO_EFETIVO], matrícula [MATRÍCULA], [CARGO_EFETIVO], Classe [CLASSE], Padrão [PADRAO], do [LOTACAO], matrícula SIAPE no [MATRICULA_SIAPE], para constar onde se lê: [INFORMACAO_ERRADA], leia-se [INFORMACAO_CORRETA], mantendo-se os demais termos do [TIPO_DE_ATO].

As entidades que deverão ser identificadas são:
  
Entidades | Padrão   
-------- | ------- 
Edital Normativo | Começa com 'Edital Normativo' 
Data do Edital Normativo | Sem Padrão 
Número do DODF do Edital Normativo | Após 'publicado no DODF n°', logo após Edital Normativo 
Data do DODF do Edital Normativo | Após Número do DODF do Edital Normativo 
Edital de Resultado Final | Começa com 'Edital de Homologação' ou 'Edital de Resultado Final' 
Data do Edital de Resultado Final | Após Edital de Resultado Final 
Número do DODF do Edital de Resultado Final | Após 'publicado no DODF n°', logo após Data do Edital de Resultado Final 
Data do DODF do Edital de Resultado Final | Após Número do DODF do Edital de Resultado Final 
Cargo | Após 'cargo de' 
Especialidade | Sem padrão, geralmente antes dos Nomes dos Candidatos 
Carreira | Após 'carreira' 
Órgão | Após 'do Quadro de Pessoal'  
Nome do Candidato | Letras maiúsculas 
Classificação | Após Nome do Candidato   
Portador de deficiência/necessidades especiais | Começa com 'portador de deficiência' 
Processo GDF/SEI | Após 'SEI n°'   

#### 2.1. Exemplos de atos de nomeação de cargo efetivo.

> NOMEAR, os candidatos abaixo aprovados, conforme instrução dos autos do processo SEI n.º ***00410-00020280/2017-14*** **(16)**, no concurso público a que se refere o ***Edital Normativo nº 01*** **(1)**, de ***22 de janeiro de 2014*** **(2)**, publicado no DODF nº ***19*** **(3)**, de ***24 de janeiro de 2014*** **(4)** e ***Edital de Resultado Final nº 07*** **(5)**, de ***25 de agosto de 2014*** **(6)**, publicado no DODF nº ***180*** **(7)**, de ***29 de agosto de 2014*** **(8)**, para exercerem o cargo de ***Técnico de Atividades Culturais*** **(9)**, da Carreira ***Atividades Culturais*** **(11)**, do Quadro de Pessoal do ***Distrito Federal*** **(12)**, conforme a seguir (especialidade, nome, classificação):
***AGENTE ADMINISTRATIVO*** **(10)**: ***DEBORA APARECIDA DE ALMEIDA REGO*** **(13)**, ***64***º **(14)**; ***MARIANA OLIVEIRA MACEDO*** **(13)**, ***65***º **(14)**; ***PHELIPE MAGO PONCIANO BORGES*** **(13)**, ***66***º **(14)**. ***Portador de Deficiência*** **(15)**: ***JANAINA AMARAL MAGALHAES*** **(13)**, ***17***º **(14)**. ***TÉCNICO EM CONTABILIDADE*** **(10)**: ***ROMERO PINTO PEDROSA*** **(13)**, ***19***º **(14)**.
>
> NOMEAR os candidatos abaixo, aprovados no concurso público a que se refere ***Edital Normativo n° 06/2018 - SES/DF*** **(1)**, publicado no DODF n° ***43*** **(3)**, de ***05 de março de 2018*** **(4)** e ***Edital de Homologação de Resultado Final n° 39/2018 - SES/DF*** **(5)**, publicado no DODF n° ***126*** **(7)**, de ***05 de julho de 2018*** **(8)**, para exercerem o cargo de ***MÉDICO*** **(9)**, da carreira ***Médica*** **(11)**, do Quadro de Pessoal da ***Secretaria de Estado de Saúde do Distrito Federal*** **(12)**, em substituição às nomeações tornadas sem efeito em decorrência do não comparecimento para tomar posse em tempo hábil e em substituição às exonerações e vacâncias ocorridas no período de 23/03/2018 a 12/07/2018, conforme instrução dos autos do processo SEI n° ***00060-00234428/2018-78*** **(16)**, conforme a seguir: (especialidade, nome e classificação) 
>***MÉDICO*** **(9)** - ***CANCEROLOGIA*** **(10)**: ***RAFAELA VELOSO RIBEIRO*** **(13)**, ***1***° **(14)**; ***RAQUEL BAPTISTA PIO*** **(13)**, **2**° **(14)**; ***CIBELLI NAVARRO RODRIGUES ALVES*** **(13)**, ***3***° **(14)**; ***ANDRE VICTOR TOMAZ JAPIASSU*** **(13)**, ***4***° **(14)**; ***FABIOLA VASCONCELOS ALVES*** **(13)**, ***5***° **(14)**.
>***MÉDICO*** **(9)** - ***CARDIOLOGIA*** **(10)**: ***CARLOS HENRIQUE REIS ESSELIN RASSI*** **(13)**, ***1***° **(14)**; ***ADRIANA ABREU RESENDE*** **(13)**, ***2***° **(14)**, ***XIMENA FERRUGEM ROSA*** **(13)**, ***3***° **(14)**; ***RENATO CABRAL DE PAULA*** **(13)**, ***4***° **(14)**; ***LORENA TAVEIRA AMARAL*** **(13)**, ***5***° **(14)**; ***BRUNO LEONARDO DUARTE PEREIRA*** **(13)**, ***6***° **(14)**; ***JOSE MAURICIO HIGASHI DE FREITAS*** **(13)**, ***7***° **(14)**; ***DIEGO MARTINS DE MESQUITA*** **(13)**, ***8***° **(14)**; ***PAMELA NOGUEIRA CAVALCANTE*** **(13)**, ***9***° **(14)**; ***ALEXANDRE ANDERSON DE SOUSA MUNHOZ SOARES*** **(13)**, ***10***° **(14)**.
>***MÉDICO*** **(9)** - ***CIRURGIA GERAL - TRAUMA***  **(10)**: ***LIANA CHAUL SFAIR*** **(13)**, ***1***° **(14)**; ***ANDRE DAVID DA SILVA*** **(13)**, ***2***° **(14)**; ***ITALO MOREIRA DAMASCENO*** **(13)**, ***3***° **(14)**; ***DIOGO BRAGA DE ALBUQUERQUE NUTELS*** **(13)**, ***4***° **(14)**; ***FERNANDO MARINHO MARQUES DA SILVA*** **(13)**, ***5***° **(14)**; ***FILIPE DIOGENIS DA CUNHA PEREIRA*** **(13)**, ***6***° **(14)**; ***EDGAR OLIVEIRA SARMENTO*** **(13)**, ***7***° **(14)**; ***DEBORA SARA DE ALMEIRA CARDOSO*** **(13)**, ***8***° **(14)**; ***MARCELO NEVES CARVALHO*** **(13)**, ***9***° **(14)**. ***Candidato que se declarou portador de deficiência*** **(15)**: ***OCTAVIO MAGALHAES DO VABO NETO*** **(13)**, ***1***° **(14)**.

**(1)** Edital Normativo  
**(2)** Data do Edital Normativo  
**(3)** Número do DODF do Edital Normativo    
**(4)** Data do DODF do Edital Normativo
**(5)** Edital de Resultado Final  
**(6)** Data do Edital de Resultado Final    
**(7)** Número do DODF do Edital de Resultado Final  
**(8)** Data do DODF do Edital de Resultado Final  
**(9)** Cargo  
**(10)** Especialidade  
**(11)** Carreira  
**(12)** Órgão  
**(13)** Nome do candidato  
**(14)** Classificação  
**(15)** Portador de deficiência/necessidades especiais  
**(16)** Processo GDF/SEI  

#### 2.2. Sugestão de como ralizar a anotação de um ato de nomeação de cargo efetivo:

1. **Identifique o ato que será anotado.** Por possuir mais entidades a serem anotadas e por muitas delas serem semelhantes, aconselho anotar um ato de nomeação de cargo efetivo de cada vez.

2. **Localize o processo GDF/SEI.** O posicionamento dele dentro do ato varia bastante, mas sempre estará logo após as palavras 'Processo SEI n°'. 

3. **Anote da entidade Edital Normativo até a entidade Data do DODF do Edital de Resultado Final.** Elas costumam aparecer uma após a outra, desta forma fica mais fácil de identificar e mais difícil de se confundir em relação as datas e DODF's.  
  Comece pelo Edital Normativo, depois anote a Data do Edital Normativo, Número do DODF do Edital Normativo, Data do DODF do Edital Normativo, Edital de Resultado Final e por último a Data do Edital de Resultado Final.

4. **Anote as entidades Cargo, Carreira e Orgão.** Elas aparecem uma após a outra, depois das entidades citadas no item anterior.

5. **Anote as Especialidades.** Às vezes pode ter mais de uma, elas aparecem antes da lista com os Nomes dos Candidatos, em letras maiúsculas. 

6. **Anote os Nomes dos Candidatos e suas respectivas Classificações.** Os nomes estarão em letras maiúsculas e a classificação estará logo em seguida. 

7. **Confira se há algum candidato portador de deficiência/ necessidades especiais, se tiver anote.** Estará escrito algo como 'Candidato que se declarou portador de deficiência' ou 'Portador de Deficiência'.

8. **Anote o ato de nomeação como um todo.** Anote todas as palavras desde ‘NOMEAR” até a classificação do último candidato.

### Observações Gerais sobre os Atos de Nomeação:

* Nem sempre o ato terá todos os atributos, mas anote todos os que você encontrar.  
* Não anote vírgulas e pontos, a não ser que eles estejam dentro do atributo, como acontece em Hierarquia de Loatação.  
* Tenha muito cuidado para não apagar todoas a anotações de um documento, mesmo tendo função de anotador.
* Recomendo sempre que for fazer uma pausa mais prolongada, que salve um arquivo xml com as suas anotações, por precaução. Desta forma, você terá um back up caso aconteça alguma coisa e você perca todas as anotações feitas no documento, e com isso não terá que começar a anotar do zero.
