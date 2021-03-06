# Ato Tornado sem Efeito

O ato de tornar sem efeito consiste na revogação, ou anulamento, de um ato administrativo.

_Refs:_
1. <a href="http://bibliotecadigital.fgv.br/ojs/index.php/rda/article/viewFile/8574/7312">http://bibliotecadigital.fgv.br/ojs/index.php/rda/article/viewFile/8574/7312</a>

Para fazer a anotação, primeiro é necessário verificar se existem atos tornados sem efeito no DODF, para isso basta pressionar CTRL+F e pesquisar “TORNAR SEM EFEITO”. Depois avalie um por um para ver se eles se referem a atos de nomeação, exoneração ou aposentadoria. Existirão outros tipos de atos tornados sem efeito, porém eles não precisam ser anotados.

## Link para o tutorial em vídeo
- <a href="https://youtu.be/ZfjiFIO-HGg">https://youtu.be/ZfjiFIO-HGg</a>

## Atos tornados sem efeito referentes a nomeação ou exoneração

Os atos de nomeação ou exoneração tornados sem efeito costumam seguir o mesmo padrão, tornando-os fáceis de serem identificados. Eles começam com 'TORNAR SEM EFEITO' e vão ter as palavras 'o ato que nomeou' ou 'o ato que exonerou' antes do Nome do Servidor.

### Tabela de entidades e padrões

As entidades que deverão ser identificadas são:

ID | Rótulo | Entidade (descrição)  | Padrão  
------- | ------- | ------- | -------
(1) | tipo_documento | Tipo de Documento | Após 'TORNAR SEM EFEITO'
(2) | data_documento | Data do documento onde está o item tornado sem efeito | Após Tipo de Documento  
(3) | tipo_edicao | Tipo de edição do DODF | Sem padrão, mas geralmente entre Data do Documento e Número do DODF
(4) | numero_dodf | Número do DODF |  Após 'n°'
(5) | data_dodf | Data do DODF |  Após Número do DODF
(6) | pagina_dodf | Página do DODF | Após Data do DODF
(7) | nome | Nome do Servidor |  Letras maiúsculas, perto de 'ato que nomeou' ou 'ato que exonerou'
(8) | cargo_efetivo | Cargo Efetivo | Sem padrão, mas geralmente aparece perto do Nome do Servidor
(9) | matricula | Matrícula | Após 'matrícula'
(10)| matricula_SIAPE | Matrícula SIAPE | Após SIAPE
(11)| simbolo | Símbolo | Após 'Símbolo'
(12)| cargo_comissionado | Cargo em Comissão | Após Símbolo
(13)| hierarquia_lotacao | Hierarquia da Lotação | Após Cargo em Comissão
(14)| orgao | Órgão | Após Hierarquia da Lotação

### Exemplos de atos tornados sem efeito referentes a nomeação ou exoneração.

> TORNAR SEM EFEITO, no ***Decreto*** **(1)** de ***05 de dezembro de 2019*** **(2)**, publicado na Edição ***Extra*** **(3)** n° ***85*** **(4)**, de ***05 de dezembro de 2019*** **(5)**, página ***01*** **(6)**, o ato que nomeou ***CLAUDIO JOSÉ TRINCHÃO SANTOS*** **(7)** para exercer o Cargo de Natureza Especial, Símbolo ***CNE-02*** **(11)**, de ***Secretário Geral*** **(12)**, da ***Secretaria Geral*** **(13)**, do ***Instituto do Meio Ambiente dos Recursos Hídricos do Distrito Federal - BRASÍLIA AMBIENTAL*** **(14)**.


> TORNAR SEM EFEITO no ***Decreto*** **(1)** de ***1° de outrubro de 2019*** **(2)**, publicado no DODF n° ***71*** **(4)**, de ***02 de outubro de 2019*** **(5)**, página ***02*** **(6)**, o ato que nomeou ***OSIEL ALEX FERREIRA PACHECO*** **(7)**, matrícula ***1.440.796-5*** **(9)**, para exercer o Cargo em Comissão, Símbolo ***DFG-07*** **(11)**, de ***Chefe*** **(12)**, do ***Núcleo de Gestão da Internação, da Gerência Interna de Regulação, da Diretoria do Hospital Regional do Gama, da Superintendência da Região de Saúde Sul*** **(13)**, da ***Secretaria de Estado de Saúde do Distrito Federal*** **(14)**.


> TORNAR SEM EFEITO no ***Decreto*** **(1)** de ***16 de dezembro de 2019*** **(2)**, publicado no DODF n° ***239*** **(4)**, de ***17 de dezembro de 2019*** **(5)**,  página ***16*** **(6)**, o ato que exonerou ***MARIA ROSANGELA PEREIRA E SILVA MARQUES*** **(7)**, matrícula ***01316540*** **(9)**, do Cargo em Comissão, Símbolo ***DFA-10*** **(11)**, de ***Assessor Técnico*** **(12)**, da ***Superintendência da Região de Saúde Centro-Sul*** **(13)**, da ***Secretaria de Saúde do Distrito Federal*** **(14)**.


> TORNAR SEM EFEITO no ***Decreto*** **(1)** de ***03 de abril de 2019*** **(2)**, publicado no DODF n° ***64*** **(4)**, de ***04 de abril de 2019*** **(5)**, o ato que nomeou o ***Agente de Polícia*** **(8)** ***ANTONIO DANIEL SILVA FARIA*** **(7)**, matrícula ***57.512.7*** **(9)**, SIAPE ***1411196*** **(10)**, para exercer o Cargo em Comissão, Símbolo ***DFG-10*** **(11)**, de ***Chefe*** **(12)**, da ***Seção de Investigação II, da Divisão de Repressão à Corrupção e aos Crimes contra a Administração Pública, da Coordenação Especia de Combate à Corrupção, ao Crime Organizado, aos Crimes contra a Administração e aos Crimes Contra Ordem Tributária, do Departamento de Polícia Especializada*** **(13)**, da ***Polícia Civil do Distrito Federal*** **(14)**.


> TORNAR SEM EFEITO no ***Decreto*** **(1)** de ***03 de abril de 2019*** **(2)**, publicado no DODF n° ***64*** **(4)**, de ***04 de abril de 2019*** **(5)**, o ato que exonerou o ***Agente de Polícia*** **(8)** ***JEUVANI MARQUES DE FARIA JUNIOR*** **(7)**, matrícula ***188.531-6*** **(9)**, SIAPE ***1479093*** **(10)**, para exercer o Cargo em Comissão, Símbolo ***DFG-10*** **(11)**, de ***Chefe*** **(12)**, da ***Seção de Investigação II, da Divisão de Repressão à Corrupção e aos Crimes contra a Administração Pública, da Coordenação Especia de Combate à Corrupção, ao Crime Organizado, aos Crimes contra a Administração e aos Crimes Contra Ordem Tributária, do Departamento de Polícia Especializada*** **(13)**, da ***Polícia Civil do Distrito Federal*** **(14)**.


> TORNAR SEM EFEITO, na ***Portaria*** **(1)** n°09, de ***09/01/2020*** **(2)**, publicada no DODF ***07*** **(4)**, de ***10/01/2020*** **(5)**, o ato que exonerou, por extinção do cargo, e nomeou ***ENIVALDO ERILANY FELIPE DOS SANTOS*** **(7)**, matrícula n° ***38.714-2*** **(9)**, do Cargo em Comissão, Símbolo ***DFA-05*** **(11)**, de ***Assessor Técnico*** **(12)**, da ***Gerência de Infraestrutura, da Coordenação de Inovação, Tecnologia da Informação e Comunicação, da Subsecretaria de Administração-Geral*** **(13)**, da ***Defensoria Pública do Distrito Federal*** **(14)**.


### Sugestão de como ralizar a anotação de um ato tornado sem efeito referente a nomeação ou exoneração:

1. **Identifique o ato que será anotado.** Por possuir várias entidades a serem anotadas, aconselho anotar um ato de nomeação de cargo efetivo de cada vez.  

2. **Anote o Tipo e a Data do documento onde está o item tornado sem efeito.** Aparecem logo após as palavras 'TORNAR SEM EFEITO'.

3. **Anote o Tipo de edição, o Número, a Data e a Página do DODF.**  Aparecem depois das entidades citadas acima. O tipo de edição do DODF pode ser 'Extra' ou 'Suplementar', se for normal não haverá menção. Anote as entidade Número, Data e Página do DODF seguindo a ordem em que elas aparecerem.

4. **Anote o Nome do Servidor, Cargo Efetivo, Matrícula e Matrícula SIAPE.** O Nome estará em letra maiúscula. Nem sempre tem o Cargo Efetivo, mas se tiver ele estará aao redor do nome. Depois terá a Matrícula e a Matrícula SIAPE, mas também existem casos em que essas entidades não estão presentes no ato a ser anotado.

5. **Anote Símbolo, Cargo, Hierarquia de Lotação e Órgão.** O símbolo fica após a palavra 'símbolo'. E em seguida estarão o Cargo, a Hierarquia de Lotação e o Órgão, respectivamente. Sendo que o Órgão são as últimas palavras, depois da última vírgula até o final do ato que está sendo anotado.

6. **Anote o ato tornado sem efeito como um todo.** Anote todas as palavras desde 'TORNAR SEM EFEITO' até o final do ato que está sendo anotado.

## Atos tornados sem efeito referente a aposentadoria.

Os atos tordados sem efeito referentes a aposentadoria começam com 'TORNAR SEM EFEITO' e vão ter as palavras 'que concedeu aposentadoria a' antes do Nome do Servidor.

### Tabela de entidades e padrões

As entidades que deverão ser identificadas são:

ID | Rótulo | Entidade (descrição)  | Padrão  
------- | ------- | ------- | -------
(1) | tipo_documento | Tipo de Documento onde está o item tornado sem efeito | Após 'TORNAR SEM EFEITO
(2) | numero_documento | Número do Documento | Após Tipo de Documento
(3) | data_documento | Data do Documento | Após Número do Documento
(4) | numero_dodf | Número do DODF | Sem padrão, geralmente após 'DODF n°'
(5) | data_dodf | Data do DODF | Sem padrão, geralmente após Número do DODF
(6) | pagina_dodf | Página do DODF | Após Data do DODF
(7) | nome | Nome do Servidor |  Letras maiúsculas, após 'concedeu aposentadoria a'
(8) | matricula | Matrícula  |  Após 'matrícula'
(9) | matricula_SIAPE | Matricula SIAPE | Após 'SIAPE'
(10)| cargo_efetivo | Cargo Efetivo |  Sem padrão, às vezes após 'Cargo de'
(11)| classe | Classe | Após 'Classe'
(12)| padrao  | Padrão | Após 'Padrão'
(13)| quadro | Quadro de Pessoal permanente ou Suplementar | Após 'Quadro de Pessoal'   
(14)| orgao | Órgão |  Sem padrão, provavelmente após Quadro de Pessoal
(15)| processo_SEI | Processo GDF/SEI | Sem padrão, geralmente no final e após 'Processo'


### Exemplos de atos tornados sem efeito referentes a aposentadoria.

> TORNAR SEM EFEITO na ***Ordem de Serviço*** **(1)** n° ***42*** **(2)**, de ***14/02/2012*** **(3)**, publicada no DODF n° ***36*** **(4)**, de ***17/02/2012*** **(5)**, o ato que concedeu aposentadoria a ***GERALDO EUSTÁQUIO COUTO*** **(7)**, matrícula n° ***114.514-2*** **(8)**, em atendimento a Diligência Interna -CGDF n° 6/2016. Processo/SES: ***276.000.021/2012*** **(15)**.


> TORNAR SEM EFEITO na ***Ordem de Serviço*** **(1)** n° ***223*** **(2)**, de ***18/09/2017*** **(3)**, publicada no DODF n° ***186*** **(4)**, de ***27/09/2017*** **(5)**, o ato que concedeu aposentadoria a ***JOSE ANTONIO DE JESUS*** **(7)**, matrícula n° ***133;010-1*** **(8)**, por erro na contagem do tempo para aposentadoria. Processo SEI n° ***0060-004679/2017*** **(15)**.


> TORNAR SEM EFEITO, na ***Ordem de serviço*** **(1)** n° ***96*** **(2)**, de ***25/05/2016*** **(3)**, publicado no DODF n° ***109*** **(4)** de ***09/06/2016*** **(5)**, o ato de aposentadoria de ***SONIA APARECIDA CALDAS PETRUCCELE*** **(7)**, matrícula nº ***130.945-5*** **(8)**. Lotação: ***HRC*** **(14)**. Processo n° ***060.007.490/2015*** **(15)**


> TORNAR SEM EFEITO na ***Ordem de Serviço*** **(1)** n° ***344*** **(2)**, de ***27 de dezembro de 2019*** **(3)**, publicada no Diário Oficial do Distrito Federal, de ***03 de janeiro de 2020*** **(5)**, o ato que concedeu aposentadoria a ***ELIÃ AMBRÓSIO CÂNDIDO DA SILVA*** **(7)**, matrícula ***39.969-8*** **(8)**, no Cargo de ***Professor de Educação Básica*** **(10)**, Padrâo ***24*** **(12)**, Etapa IV, do ***Quadro de Pessoal do Distrito Federal*** **(13)**, a contar de 03 de janeiro de 2020. Processo ***00080.00087144/2019-92*** **(15)**.


> TORNAR SEM EFEITO na ***Ordem de Serviço*** **(1)** de ***26 de julho de 2016*** **(3)**, publicada no Diário Oficial do Distrito Federal de ***27 de julho de 2016*** **(5)**, o ato que concedeu aposentadoria a ***EDNA MARIA DA CRUZ SAMPAIO*** **(7)**, matricula ***62.842-5*** **(8)**, no cargo de ***Professor de Educação Básica*** **(10)**, Padrão ***25*** **(12)**, Etapa IV do ***Quadro de Pessoal do Distrito Federal*** **(13)**. Processo ***464.000084/2016*** **(15)**.


> TORNAR SEM EFEITO na ***Ordem de Serviço*** **(1)** n° ***344*** **(2)**, de ***27 de dezembro de 2019*** **(3)**, publicada no Diário Oficial do Distrito Federal, de ***03 de janeiro de 2020*** **(5)**, o ato que concedeu aposentadoria a ***FLORIPES ALVES MACHADO DA SILVA*** **(7)**, matrícula ***40.911-1*** **(8)**, no Cargo de ***Agente de Gestão Educacional/Serviços Gerais*** **(10)**, Nível 10, Padrão ***3*** **(12)**, Etapa V, do ***Quadro de Pessoal do Distrito Federal*** **(13)**, a contar de 03 de janeiro de 2020. Processo ***00080.00129252/2019-40*** **(15)**.


> TORNAR SEM EFEITO na ***Ordem de Serviço*** **(1)** nº ***256*** **(2)** de ***28 de novembro de 2017*** **(3)**, publicada no DODF nº ***237*** **(4)** de ***05 de dezembro de 2017*** **(5)**, o ato que concedeu aposentadoria ***EVANDRO DIAS CABRAL*** **(7)**, matrícula nº ***114.714-5*** **(8)** na Carreira de Assistência Pública a Saúde, no Cargo de ***Técnico em Saúde - Técnico Administrativo*** **(10)**, Classe ***Especial*** **(11)**, Padrão ***V*** **(12)**, nos termos do artigo 6º da Emenda Constitucional nº 41/2003, combinado com o artigo 2º da Emenda Constitucional nº 47/2005, combinados com o artigo 43, da Lei Complementar nº 769, de
30/06/2008, do ***Quadro de Pessoal da Secretaria de Estado de Saúde do Distrito Federal*** **(13)**. Lotação: ***SRSOE*** **(14)**. Processo: ***060.00047003/2017-40*** **(15)**


> TORNAR SEM EFEITO a ***Ordem de Serviço*** **(1)** n° ***36*** **(2)**, de ***05/05/2011*** **(3)**, publicado no DODF n° ***87*** **(4)**, de ***09/05/2011*** **(5)**, que concedeu aposentadoria a ***HELIANA OLIVEIRA SOUZA*** **(7)**, matrícula ***102.824-3*** **(8)**, ***Especialista em Assistência Social*** **(10)**, Classe ***Especial*** **(11)**, Padrão ***V*** **(12)**, do ***Quadro de Pessoal do Distrito Federal*** **(13)**. Processo n° ***0400.001.442/2010*** **(15)**.


### Sugestão de como ralizar a anotação de um ato tornado sem efeito referente a aposentadoria:

1. **Identifique o ato que será anotado.** Por possuir várias entidades a serem anotadas, aconselho anotar um ato de nomeação de cargo efetivo de cada vez.  

2. **Anote o Tipo, o Número e a Data do documento onde está o item tornado sem efeito.** Aparecem logo após as palavras 'TORNAR SEM EFEITO'.

3. **Anote o Número, a Data e a Página do DODF.**  Aparecem após depois das entidades citadas acima. Anote as entidades seguindo a ordem em que elas aparecerem.

4. **Anote o Nome do Servidor, Matrícula, Matrícula SIAPE e Cargo Efetivo.** O Nome estará em letra maiúscula. O Cargo Efetivo geralmente aparece após a Matrícula, a qual aparece depois do Nome do Servidor. Nem sempre se tem a Matrícula SIAPE, mas se tiver ela aparecerá depois da palavra 'SIAPE'.

5. **Anote Classe, Padrão, Quadro de Pessoal e Órgão.** Geralmente essas entidades aparecem uma seguida da outra, nem sempre o ato terá todas elas, anote todas as que encontrar.

6. **Anote o Processo GDF/SEI.** Geralmente aparece por último, após a palavra 'Processo'.

6. **Anote o ato tornado sem efeito como um todo.** Anote todas as palavras desde 'TORNAR SEM EFEITO' até o final do ato que está sendo anotado.

### Observações Gerais sobre os atos tornados sem efeito:

* Existirão outros tipos de atos tornados sem efeito, porém eles não precisam ser anotados. Anote apenas os que se referem a atos de nomeação, exoneração ou aposentadoria.
* Nem sempre o ato terá todos os atributos, mas anote todos os que você encontrar.  
* Não anote vírgulas e pontos, a não ser que eles estejam dentro do atributo, como acontece em Hierarquia de Loatação.  
* Tenha muito cuidado para não apagar todoas a anotações de um documento, mesmo tendo função de anotador.
* Recomendo sempre que for fazer uma pausa mais prolongada, que salve um arquivo xml com as suas anotações, por precaução. Desta forma, você terá um back up caso aconteça alguma coisa e você perca todas as anotações feitas no documento, e com isso não terá que começar a anotar do zero.

Pronto! Agora é só por uma boa playlist e seguir com o bom trabalho
